# Especificação de Requisitos (ERSw)

---

## Especificação de Requisitos

- Documenta os diferentes tipos de requisitos.
- O formato da documentação resultante da especificação de requisitos depende da organização, das necessidades do projeto e do ciclo de vida utilizado.
- Enunciado completo, claro e preciso dos requisitos de um produto de software.

---

# Conteúdo da ERSw

---

## Funcionalidade

- O que o produto deverá fazer?

---

## Interfaces Externas

- Como o produto interage com as pessoas, hardware do sistema e outros produtos?

---

## Desempenho

- Quais requisitos de velocidade de processamento.
- Tempo de resposta.
- E quais os demais parâmetros de desempenho?

---

## Outras Informações

- Que considerações devem ser observadas sobre:
- Portabilidade.
- Manutenibilidade.
- Confiabilidade?

---

## Restrições de Desenho

- Informa os padrões que o software deve seguir.
- Linguagem de implementação.
- Banco de dados.
- Ambiente de operação.
- Etc.

---

## Alteração de Requisitos

- Os requisitos podem sofrer alterações ao longo do tempo.
- Descoberta de defeitos e inadequações nos requisitos originais.
- Falta de detalhes suficientes.
- Alterações incontornáveis (Mudanças na legislação).

---

## Alteração de Requisitos

- Uma bom levantamento de requisitos **diminui** a necessidade de alteração.
- No entanto, deve ser possível alterar caso necessário.
- Deve manter o controle das alterações realizadas na especificação.

---

## Limites da ERSw

- Definir **correta** e **completamente** todos os requisitos.
- Não descrever aspectos gerenciais do projeto (custos, prazo, etc).

---

## Características da Especificação (Qualidade)

- **Correta**;
- **Precisa**;
- **Completa**;
- **Consistente**;
- **Priorizada**;
- Verificável;
- **Modificável**;
- Rastreável.

---

## Correta

- Todo requisito presente na especificação é realmente um requisito do produto.
- Solicitar aprovação formal por parte do cliente.

---

## Precisa

- Todo requisito presente possui apenas uma única interpretação.
- Essa interpretação é aceita tanto pelos desenvolvedores quanto pelos usuários.

---

## Completa

- Contém todos os requisitos significativos para o software.
- Funcionalidade, desempenho, restrições de desenho, interfaces externas.
- Define as entradas válidas e inválidas.
- Define a resposta do software para todas as entradas válidas e inválidas.
- Contém glossário de todos os termos técnicos.

---

## Consistente

- Não há conflitos entre requisitos.

**Exemplos:**

- Conflito lógico ou temporal entre ações.
- Uso de diferentes termos para designar o mesmo objeto.
- Etc.

---

## Priorizada

- Requisitos devem ser classificados quanto a estabilidade e importância.

**Essencial:** Sem ele o produto é inaceitável.
**Desejável:** Atendimento aumenta o valor do produto, mas ausência pode ser relevada caso necessário.
**Opcional:** Cumprido se houver disponibilidade de tempo e recursos.

---

## Verificável

**Requisitos verificáveis**

- Existe um processo finito, com custo compensador executado por pessoa ou máquina que mostre conformidade do produto final com o requisito.

**Requisitos não verificáveis**

- Requisitos ambiguos;
- Requisitos contrários a termos técnicos e científicos.

---

## Modificável

- Uma boa especificação de requisitos deve ser fácil de modificar.

**Para que isso seja possível, a especificação precisa ter algumas características:**

- **Bem organizada:** com índice, seções claras e referências entre partes relacionadas.
- **Sem repetição desnecessária:** evitar o mesmo requisito escrito em vários lugares.
- **Requisitos separados:** cada requisito deve estar descrito de forma independente, facilitando alterações pontuais.

---

## Rastreável

- Deve ser possível acompanhar a origem de cada requisito e também entender o que ele afeta no sistema.

**Rastreabilidade para trás**

- Qual foi a origem (cliente, usuário, lei, sistema, etc.).
- Por que ele existe.
- Quem ou o que pediu.

**Rastreabilidade para frente**

- Quais partes do sistema serão afetadas.
- Quais funcionalidades, módulos ou testes dependem dele.

---

## Estrutura Básica de uma ERSw

- Introdução;
- Descrição geral do produto;
- Requisitos específicos;
- Informação de suporte.

---

## Introdução

- Objetivo do documento
- Escopo do sistema
- Definições, acrônimos e abreviações
- Referências
- Visão geral do documento
- Histórico de versões

---

## Descrição Geral do Produto

- Perspectiva do produto
- Características dos usuários
- Ambiente operacional
- Restrições

---

## Requisitos Funcionais

- Casos de uso
- Fluxos (principal e alternativos)
- Entradas e saídas
- Regras de negócio

---

## Requisitos Não Funcionais

- Desempenho
- Segurança
- Usabilidade
- Disponibilidade
- Escalabilidade
- Manutenibilidade

---

## Interfaces

- Interface com usuário
- Interfaces externas
- Interfaces de hardware
- Interfaces de software

---

## Modelos e Diagramas

- Diagrama de casos de uso
- Diagrama de classes
- Diagrama de sequência
- Modelo de dados

---

## Apêndices

- Glossário
- Dicionário de dados
- Protótipos / wireframes

---

# Análise de Requisitos

---

## Análise de Requisitos

- Identificação dos atores;
- Identificação dos casos de uso;
- Identificação dos relacionamentos entre atores e casos de uso;
- Confecção do diagrama de casos de uso.
- Descrição dos cenários de casos de uso.

---

## Casos de Uso

- Representam funções completas do produto;
- É uma técnica de modelagem de requisitos;
- Descreve o que um sistema faz;
- Um caso de uso é um "documento narrativo que descreve a sequência de eventos de um ator que usa um sistema para completar um processo" (Ivan Jacobson).

---

## Casos de Uso

- Descrevem como os usuários interagem com o sistema (as funcionalidades do sistema);
- Dão uma visão externa do sistema;
- O conjunto de casos de uso deve ser capaz de comunicar a funcionalidade e o comportamento do sistema para o cliente;
- Descrevem o que o sistema faz, mas NÃO especificam como isso deve ser feito.

---

## Atores

- Modelam papéis dos usuários do produto;
- Modelam papéis e não pessoas: um ator pode modelar vários usuários físicos;
- Podem também modelar outros sistemas.

---

## Atores: Caracterização

- Descrição sucinta das responsabilidades do respectivo papel;
- Características mais importantes do respectivo grupo de usuários:
-- cargo ou função;
-- frequência de uso;
-- nível de instrução;
-- proficiência no processo de negócio;
-- proficiência em informática.

---

## Diagrama de Casos de Uso

<img width="521" height="343" alt="Captura de tela de 2026-05-14 16-06-16" src="aula-7-imagens/img-1.png" />

---

## Descrição de Casos de uso

- Um caso de uso descreve o que um sistema deve fazer. 
- O diagrama de casos de uso provê uma visão apenas parcial disso, uma vez que mostra as funcionalidades por perspectiva externa.
- Já a descrição de casos de uso captura uma visão interna de cada caso de uso, especificando o comportamento do caso de uso pela descrição do fluxo de eventos que ocorre internamente (passos do caso de uso).
- Assim, uma parte fundamental do modelo de casos de uso é a descrição dos casos de uso.

---

## Descrição de Casos de uso

- Deve-se especificar o comportamento de um caso de uso pela descrição textual de seu fluxo de eventos, de modo que outros interessados possam compreendê-lo.
- Cada passo do fluxo de eventos de um caso de uso tipicamente descreve uma das seguintes situações:
-- (i) uma interação entre um ator e o sistema,
-- (ii) uma ação que o sistema realiza para atingir o objetivo do ator primário ou
-- (iii) uma ação que o sistema realiza para proteger os interesses de um interessado.
- Essas ações podem incluir validações e mudanças do estado interno do sistema

---

## Descrição de Casos de uso

- **Nome:** nome do caso de uso;
- **Escopo:** diz respeito ao que está sendo documentado pelo caso de uso.
- **Descrição do Propósito:** uma descrição sucinta do caso de uso, na forma de um único parágrafo, procurando descrever o objetivo do caso de uso.
- **Ator Primário:** nome do ator primário, ou seja, o interessado que tem um objetivo em relação ao sistema, o qual pode ser atingido pela execução do caso de uso.
- **Interessados e Interesses:** um interessado é alguém ou algo (um outro sistema) que tem um interesse no comportamento do caso de uso sendo descrito.
- **Pré-condições:** o que deve ser verdadeiro antes da execução do caso de uso.
- **Pós-condições:** o que deve ser verdadeiro após a execução do caso de uso, considerando que o fluxo de eventos normal é realizado com sucesso.
- **Fluxo de Eventos Alternativos:** descreve formas alternativas de realizar certos passos do caso de uso.
 - **Fluxos variantes**, que são considerados dentro da normalidade do caso de uso;
 - **Fluxos de exceção**, que se referem ao tratamento de erros durante a execução de um passo do fluxo normal (ou de um fluxo variante ou até mesmo de um outro fluxo de exceção).
 - **Fluxo de Eventos Normal:** descreve os passos do caso de uso realizados em situações normais, considerando que nada acontece de errado e levando em conta a maneira mais comum do caso de uso ser realizado.

## Descriçã de Casos de uso

- A maioria das exceções ocorre nos passos em que alguma informação é passada dos atores para o sistema, pois, quando uma informação é passada para o sistema, muitas vezes ele realiza **validações**.
- Quando uma dessas validações falha, tipicamente ocorre uma exceção.
- Cada exceção deve ser tratada por um fluxo alternativo de exceção.
- Fluxos alternativos de exceção devem ser descritos contendo as seguintes informações:
- um identificador, uma descrição sucinta da exceção que ocorreu, os passos para tratar a exceção (ações corretivas) e uma indicação de como o caso de uso retorna ao fluxo principal (se for o caso) após a execução das ações corretivas.


## Descrição de Casos de Uso

### Nome do Caso de Uso

- Realizar Login.

### Escopo

- Sistema Acadêmico.

### Descrição do Propósito

- Este caso de uso tem como objetivo permitir que um usuário acesse o sistema por meio da autenticação utilizando login e senha válidos.

### Atores

- Os atores envolvidos neste caso de uso são o Usuário, responsável por informar as credenciais de acesso, e o Sistema de Autenticação, responsável por validar as informações fornecidas.

### Pré-condições

- Para que este caso de uso possa ser executado, o usuário deve estar previamente cadastrado no sistema, possuir login e senha válidos e o sistema deve estar disponível para acesso.

### Pós-condições

- Caso o processo seja realizado com sucesso, o usuário será autenticado, uma sessão será criada e o sistema redirecionará o usuário para a página inicial.
- Em caso de falha, o acesso ao sistema não será permitido e uma mensagem de erro será apresentada ao usuário.

### Fluxo de Eventos Normal

1. O usuário acessa a tela de login do sistema.
2. Em seguida, o sistema exibe o formulário de autenticação contendo os campos de **usuário** e **senha**.
3. O usuário informa suas credenciais e clica no botão “Entrar”.
4. O sistema valida os dados fornecidos e verifica se as credenciais são válidas.
5. Após a validação, o sistema autentica o usuário e redireciona para a página inicial do sistema.

### Fluxos de Eventos Alternativos

1. Caso o usuário informe uma senha incorreta durante a validação das credenciais, o sistema exibirá uma mensagem informando que o usuário ou senha são inválidos e retornará para a tela de login para uma nova tentativa.
2. Quando o usuário esquece sua senha, poderá selecionar a opção “Esqueci minha senha”.
3. O sistema solicitará o e-mail cadastrado e, após o preenchimento, enviará instruções para recuperação da senha.

### Fluxos de Exceção

1. Se ocorrer indisponibilidade do sistema durante o processo de autenticação, o sistema exibirá uma mensagem informando que o serviço está temporariamente indisponível e o processo de login será cancelado.
2. Se o usuário tenta realizar login sem preencher os campos obrigatórios, o sistema exibirá mensagens solicitando o preenchimento correto das informações e permanecerá na tela de login aguardando a correção dos dados.

# Referências

- https://moodle.unesp.br/pluginfile.php/25934/mod_resource/content/1/diagrama_casos_uso.pdf

