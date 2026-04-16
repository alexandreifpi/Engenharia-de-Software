# Engenharia de Requisitos

- Disciplina da Engenharia de Software que consiste no uso sistemático e repetitivo de técnicas para cobrir atividades de obtenção, documentação e manutenção de um conjunto de requisitos para software que atendam aos objetivos de negócio e sejam de qualidade.

- Foco na qualidade do processo, já que se trata de uma fase importante.

## Papel do Analista de Requisitos
- Realiza o levantamento de requisitos e especificação de projetos de TI, desenvolvendo soluções para processos,
mapeamento e análise de negócio. Elabora a documentação técnica de especificação de requisitos de softwares e status report para gestão de projetos.

## Subprocessos da Engenharia de Requisitos:
  1. Estudo de viabilidade
  2. Elicitação e análise dos requisitos
  3. Especificação
  4. Validação

# Conceitos Importantes

## **Requisitos**

- Uma condição ou capacidade que deve ser alcançada ou possuída por um sistema, produto, serviço, resultado ou componente para satisfazer um contrato, padrão, especificação ou outro documento formalmente imposto. Requisitos incluem as necessidades quantificadas e documentadas, desejos e expectativas do patrocinador, clientes e outras partes interessadas.

## Tipos de Requisitos

### Requisitos de Usuários

- São declarações, em uma linguagem natural com diagramas, de quais serviços o sistema deverá fornecer a seus usuários e as restrições com as quais este deve operar.

---

- **Exemplo:**

1. O sistema XPTO deve gerar relatórios gerenciais mensais que mostrem o custo dos medicamentos prescritos por cada clínica durante aquele mês.
2. O usuário deve ser capaz de consultar seu saldo.

---

### Requisitos de Sistema

- Descrições mais detalhadas das funções, serviços e restrições operacionais do sistema de software.
- Descreva os requisitos de forma mais técnica, dando indícios de implementação.

---

- **Exemplo**:
  
1.1. No último dia útil de cada mês deve ser gerado um resumo dos medicamentos prescritos, seus custos e as prescrições de cada clínica.

1.2. Após 17:30h do último dia útil do mês, o sistema deve gerar automaticamente o relatório para impressão.

1.3. Um relatório será criado para cada clínica, listando os nomes dos medicamentos, o número total de prescrições, o número de doses prescritas e o custo total dos medicamentos prescritos.

1.4. Se os medicamentos estão disponíveis em diferentes unidades de dosagem (por exemplo, 10 mg, 20 mg), devem ser criados relatórios separados para cada unidade.

1.5. O acesso aos relatórios de custos deve ser restrito a usuários autorizados por uma lista de controle de gerenciamento de acesso.

2.1. O sistema deve consultar o saldo do usuário baseado nas transações armazenadas no banco de dados.

---

## Requisitos Funcionais x Requisitos Não Funcionais

- Os requisitos de software são frequentemente classificados como requisitos funcionais e requisitos não funcionais.

### Requisitos Funcionais

- São declarações de serviços que o sistema deve fornecer, de como o sistema deve reagir a entradas específicas e de como o sistema deve se comportar em determinadas situações.
  
- Também podem explicitar o que o sistema não deve fazer.

- Os requisitos funcionais podem ser escritos em diversos níveis de detalhamento (Comparar requisito 1 e 3).

- **Exemplo**:
  
  - O sistema deve calcular o saldo do usuaŕio somando os valores das entradas e subtraindo os valores das saídas.   

---
- **Exemplo de Requisitos Funcionais de um sistema que mantém informações sobre pacientes em tratamentos de saúde:**

1. Um usuário deve ser capaz de pesquisar as listas de agendamentos para todas as clínicas.
2. O sistema deve gerar a cada dia, para cada clínica, a lista dos pacientes para as consultas daquele dia.
3. Cada membro da equipe que usa o sistema deve ser identificado apenas por seu número de oito dígitos.
---

- **Especificação dos requisitos funcionais de um sistema deve ser:**

1. Completa: significa que todos os serviços requeridos pelo usuário devem ser definidos.
2. Consistente: significa que os requisitos não devem ter definições contraditórias.

- Para sistemas grandes e complexos, é praticamente impossível alcançar completude e consistência dos requisitos.

#### Requisitos funcionais com objetivo de usuário

- Ao final da tarefa, o usuário cumpre seu objetivo, fica satisfeito, não há nada mais a se fazer.

- Se um trabalho envolve mais de um indivíduo, é porque há mais de uma tarefa presente.

- **Exemplos**

  - Efetuar baixa do título na relação de contas a receber.
  - Emitir carta de renovação de contrato.
  - Emitir certificado de participação do aluno no curso.

#### Requisitos funcionais com objetivo de agregador

- São requisitos que agregam vários objetivos de usuários individuais em uma única especificação de alto nível.

- Quanto maior o nível, mais geraissão seus objetivos.

- **Exemplos**

  - Controlar fluxo de caixa.
  - Gerir relacionamento com clientes.
  - Efetuar gestão dos cursos.

### Requisitos Não Funcionais

- São restrições aos serviços ou funções oferecidos pelo sistema.
  
- Incluem restrições de tempo, restrições no processo de desenvolvimento e restrições impostas pelas normas.
  
- Muitas vezes, aplicam-se ao sistema como um todo.

- Relacionados às propriedades emergentes do sistema, como confiabilidade, tempo de resposta e ocupação de área.

- São algumas vezes mais críticos que requisitos funcionais.

- Surgem das necessidades dos usuários, devido a restrições de orçamento, políticas organizacionais, necessidade de interoperabilidade com outros sistemas de software ou hardware, ou a partir de fatores externos, como regulamentos de segurança ou legislações de privacidade.

- Dividem-se em 3 categorias:

#### **1. Requisitos de Produto:** 

- Especificam ou restringem o comportamento do software.

**Exemplo**: requisitos de desempenho quanto à rapidez, quanta memória ele requer, confiabilidade que estabelecem a taxa aceitável de falhas, os requisitos de proteção e os requisitos de usabilidade.

#### **2. Requitos Organizacionais:** 

- São os requisitos gerais de sistemas derivados das políticas e procedimentos da organização do cliente e do desenvolvedor.

**Exemplo**: requisitos do processo operacional, que definem como o sistema será usado, do processo de desenvolvimento que especificam a linguagem de programação, o ambiente de desenvolvimento ou normas de processo a serem usadas, bem como os requisitos ambientais que especificam o ambiente operacional do sistema.

#### **3. Requisitos Externos**: 

- Requisitos que derivam de fatores externos ao sistema e seu processo de desenvolvimento. 

**Exemplo**: Podem incluir requisitos reguladores, que definem o que deve ser feito para que o sistema seja aprovado para uso, por um regulador, tal como um banco central; requisitos legais, que devem ser seguidos para garantir que o sistema opere dentro da lei; e requisitos éticos, que asseguram que o sistema será aceitável para seus usuários e o público em geral.

---

<img width="1184" height="637" alt="image" src="https://github.com/user-attachments/assets/302646d5-9314-4c97-8506-e5a3276691a7" />

- **Exemplos:**
  
- Se um sistema de aeronaves não cumprir seus requisitos de confiabilidade, não será certificado como um sistema seguro para operar;
  
- Se um sistema de controle embutido não atender aos requisitos de desempenho, as funções de controle não funcionarão corretamente.

---

### Requisitos de Domínio/Regras de Negócio

- São provenientes do domínio de aplicação do sistema e refletem características e restrições desse domínio.
- Derivados do negócio que o sistema se propõe a apoiar.
- Podem restringir requisitos funcionais existentes ou estabelecer como cálculos específicos devem ser realizados, refletindo fundamentos do domínio de aplicação.

- **Exemplo:** O saldo não pode ficar negativo.

## **Especificação de Requisitos**
- Contrato entre clientes e equipe de desenvolvimento.
- Deve esclarecer aos clientes o que será entregue como produto do trabalho da equipe de desenvolvimento.
- Documentar de forma fiel e completa todas as necessidades dos clientes e obter um aceite (aprovação) sobre o que se está propondo entregar em termos de produto.

### Composição de uma Especificação de Requisitos

**1. Visão Geral**
- Cita os objetivos do projeto, principais partes interessadas, um escopo preliminar com uma breve descrição das funções que o sistema deverá desempenhar.

**2. Glossário**
- Definição dos termos técnicos (do negócio), sinônimos e acrônimos (siglas) usados ao longo do documento.

**3. Modelos do Sistema**
- Mostram o relacionamento entre os componentes do sistema e entre o sistema e seu ambiente (exemplos: diagrama de contexto, diagrama de caso de uso, modelo de processo etc).

**4. Requisitos Funcionais**
- Descreve tarefas e serviços que serão fornecidos pelo sistema aos seus usuários (exemplo: lista de casos de uso, histórias do usuário). Inclui também as interfaces externas do software.

**5. Requisitos Não Funcionais**
- Descreve as restrições impostas sobre o software e as relaciona aos requisitos funcionais.

**6. Especificação detalhada de requisitos**
- Detalha os requisitos funcionais (por exemplo, especificações de caso de uso, regras de negócio).
