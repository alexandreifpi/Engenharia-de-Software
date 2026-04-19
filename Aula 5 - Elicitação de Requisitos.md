# Processo de Engenharia de Requisitos

# Elicitação de Requisitos

## O que é?

- Envolve as atividades de descoberta de requisitos de um software.
- Engenheiros de software interage com clientes e usuários finais do sistema para obter informações sobre o:
  - domínio da aplicação;
  - serviços que o sistema deve oferecer;
  - desempenho do sistema;
  - restrições de hardware, etc.

## Pessoas envolvidas (Stackholders)

- usuários
- gerentes
- desenvolvedores
- especialistas de domínio
- sindicatos

## Dificuldades

- Em geral, stakeholders não sabem o que querem de fato
  - dificuldade de expressão
  - pedidos não realistas
  
- Stakeholders expressam requisitos em sua própria terminologia
- Stakeholders distintos podem ter requisitos conflitantes
- Fatores políticos podem influenciar os requisitos do sistema
- Ambientes econômicos e de negócios são dinâmicos
- Requisitos mudam durante o processo de análise
- Novos requisitos podem surgir (novos stakeholders)

## Atividades do Processo:

- Compreensão do domínio
- Coleta de requisitos
- Classificação
- Resolução de conflitos
- Definição de Prioridades
- Verificação de requisito

### Compreensão do Domínio

- Os analistas devem desenvolver sua compreensão do domínio da aplicação
- Se estiver desenvolvendo um sistema de supermercado deverá descobrir como este funciona
- Utilizar técnicas para descobrir este funcionamento
- Aprender a linguagem do usuário
  - Elaborar um Glossário

### Coleta de Requisitos

- Interagir com stakeholders para descobrir os requisitos
- A coleta de requisitos é feita através de técnicas
- Os requisitos são simplesmente documentados à medida que são coletados
  - resulta em documento preliminar (rascunho)

### Classificação dos Requisitos

- Consiste basicamente em agrupar os diversos requisitos coletados em categorias bem-definidas

- Classificação:
  
  - Funcional
  - Ex.: Deve ser possível consultar o preço de uma mercadoria

  - Não Funcional
  - Ex.: A consulta deve retornar uma resposta em no máximo 5s

  - Restrições
  - Ex.: O sistema não fará controle de estoque.

### Resolução de Conflitos

- É normal que ocorram requisitos conflitantes

- Por exemplo
  – R-23: O sistema deve ...
  – R-45: O sistema não deve ...
  
- Cliente é o responsável por resolver conflitos e ambiguidade.

### Atribuição de Prioridade

- Alguns requisitos são mais urgentes que outros
- É essencial determinar a prioridade dos requisitos junto ao cliente
- Requisitos de maior prioridade são considerados em primeiro lugar

### Prioridade

- Requisitos podem ser agrupados em classes, por exemplo:
  – Essenciais
  – Importantes
  – Desejáveis
- Em princípio, o sistema deve abranger todos os requisitos de essenciais para desejáveis.

### Exemplo de Prioridade

- **Essencial**
- A consulta ao extrato bancário deve retornar dados do movimento até o dia anterior

- **Importante**
- A consulta ao extrato bancário deve visualizar dados segundo padrão X

- **Desejável**
- A consulta ao extrato bancário deve usar cores vermelhas para saldos negativos
