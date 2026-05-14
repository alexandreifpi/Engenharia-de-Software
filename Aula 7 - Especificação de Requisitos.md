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

- Correta;
- Precisa;
- Completa;
- Consistente;
- Priorizada;
- Verificável;
- Modificável;
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

## Introdução

- Objetivo do documento
- Escopo do sistema
- Definições, acrônimos e abreviações
- Referências
- Visão geral do documento
- Histórico de versões

## Descrição Geral do Produto

- Perspectiva do produto
- Características dos usuários
- Ambiente operacional
- Restrições

## Requisitos Funcionais

- Casos de uso
- Fluxos (principal e alternativos)
- Entradas e saídas
- Regras de negócio

## Requisitos Não Funcionais

- Desempenho
- Segurança
- Usabilidade
- Disponibilidade
- Escalabilidade
- Manutenibilidade

## Interfaces

- Interface com usuário
- Interfaces externas
- Interfaces de hardware
- Interfaces de software

## Modelos e Diagramas

- Diagrama de casos de uso
- Diagrama de classes
- Diagrama de sequência
- Modelo de dados

## Apêndices

- Glossário
- Dicionário de dados
- Protótipos / wireframes

# Análise de Requisitos

---

## Análise de Requisitos

- Identificação dos atores;
- Identificação dos casos de uso;
- Identificação dos relacionamentos entre atores e casos de uso;
- Confecção do diagrama de contexto.
- Descrição dos cenários de casos de uso.

## Casos de Uso

- Representam funções completas do produto;
- É uma técnica de modelagem de requisitos;
- Descreve o que um sistema faz;
- Um caso de uso é um "documento narrativo que descreve a sequência de eventos de um ator que usa um sistema para completar um processo" (Ivan Jacobson).

## Casos de Uso

- Descrevem como os usuários interagem com o sistema (as funcionalidades do sistema);
- Dão uma visão externa do sistema;
- O conjunto de casos de uso deve ser capaz de comunicar a funcionalidade e o comportamento do sistema para o cliente;
- Descrevem o que o sistema faz, mas NÃO especificam como isso deve ser feito.

## Atores

- Modelam papéis dos usuários do produto;
- Modelam papéis e não pessoas: um ator pode modelar vários usuários físicos;
- Podem também modelar outros sistemas.

## Atores: Caracterização

- Descrição sucinta das responsabilidades do respectivo papel;
- Características mais importantes do respectivo grupo de usuários:
-- cargo ou função;
-- frequência de uso;
-- nível de instrução;
-- proficiência no processo de negócio;
-- proficiência em informática.

## Diagrama de Casos de Uso

<img width="521" height="343" alt="Captura de tela de 2026-05-14 16-06-16" src="aula-7-imagens/img-1.png" />

# Referências

- https://moodle.unesp.br/pluginfile.php/25934/mod_resource/content/1/diagrama_casos_uso.pdf

