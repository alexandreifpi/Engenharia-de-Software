# Procedure e Functions

- É um bloco de código SQL salvo no próprio banco de dados, que executa tarefas quando chamado.
  
- Semalhante a criação de um método em uma linguagem de programação, reutilizável.

## Função reutilizável, que:

- Pode receber parâmetros;
  
- Pode executar comandos complexos;
  
- Evita repetição de código;
  
- Melhora a segurança e a manutenção.

## Exemplos de utilização:

- Rotinas de limpeza no banco de dados;
- Correção de dados;
- Atualização de registros automaticamente;
- Etc.

## Sintaxe Básica

### Criar Procedure

```bash
DELIMITER //
CREATE PROCEDURE nome_da_procedure(parametros)
BEGIN
	 // bloco de código
END;//
DELIMITER ;
```

### Excluir Procedure

```bash
DROP PROCEDURE nome_da_procedure;
```

### Chamar Procedure

```bash
CALL nome_da_procedure();
```

## Parâmetros da Procedure

- São opicionais, quando não precisar de parâmetros, os parênteses permanecem vazios na declaração da procedure.

- A passagem de parâmetros deve respeitar a seguinte sintaxe:
  - (MODO nome_do_parametro TIPO)

- MODO
  - Indica a forma que os parâmetros serão tratados, se é um dados de entrada, de saída ou ambos.
  - IN: Parâmetro apenas de entrada.
  - OUT: Parâmetro apenas de saída.
  - INOUT: Parâmetro de entrada e de saída.

- TIPO
  - Indica qual é o tipo de determinado parâmetro (INT, VARCHAR, DECIMAL, ...).

### Procedure com parâmetro de entrada

```bash
DELIMITER //
CREATE PROCEDURE listar_pacientes(IN limite INT)
BEGIN
	 SELECT * FROM pacientes LIMIT limite;
END;//
DELIMITER ;
```

```bash
CALL lista_pacientes(5);
```

### Procedure com parâmetro de saída

```bash
DELIMITER //
CREATE PROCEDURE calcular_quantidade_pacientes(OUT quantidade INT)
BEGIN
	 SELECT COUNT(*) INTO quantidade FROM pacientes;
END;//
DELIMITER ;
```

```bash
CALL calcular_quantidade_pacientes(@quantidade);
SELECT @quantidade;
```

