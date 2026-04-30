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

### Verificação de Requisitos

- Os requisitos são verificados quanto sua completude e consistência.
- Verifica se estão em conformidade com os stakeholders.

# Técnicas de Elicitação de Requisitos

## Análise de Documentos

- Surgiu da dificuldade de acesso às partes interessadas é comum.
- Muitos profissionais consideram a análise de documentos tediosa e pouco útil.
- Porém, isso ocorre por má utilização da técnica, não pela técnica em si.
- Documentos ajudam a formular perguntas melhores, não apenas obter respostas.

### O que é?

- Técnica de elicitação de requisitos baseada no estudo de documentos existentes.
- Ajuda a identificar necessidades do negócio e partes interessadas.

### Tipos de Documentos

- Planos de negócio
- Documentos de marketing
- Contratos e RFPs
- Fluxos de processos
- Modelos de dados
- Regras de negócio
- Manuais e relatórios
- Casos de uso e requisitos
- Políticas, normas e leis

### Como Realizar?

**1. Preparação**

- Definir as informações que deseja coletar:
  - Entender o domínio
  - Definir escopo
  - Detalhar funcionalidades
  - Elaborar perguntas-chave
  - Identificar e selecionar documentos relevantes

**2. Execução**

- Analisar documentos para responder às perguntas.
- Registrar respostas encontradas e dúvidas surgidas.

**3. Finalização**

- Validar com especialistas
- Referênciar documentos usados
- Organizar documentos em repositório

### Vantagens

- Não começa do zero (reaproveita informações)
- Ajuda a entender o domínio e planejar outras técnicas (ex: entrevistas)
- Útil quando não há especialistas disponíveis
- Informação tende a ser mais objetiva

### Desvantagens

- Pode não existir documentação (processos novos).
- Documentos podem estar desatualizados ou incompletos.
- Processo costuma ser demorado.
- Pouco eficiente para demandas específicas.

## Observação

- Nem todos os stakeholders conseguem explicar bem seu trabalho.
- A observação surge como alternativa: ver o trabalho acontecendo em vez de apenas perguntar.

### O que é?

- Técnica originada da antropologia.
- Consiste em acompanhar o ambiente real de trabalho.
- Entender interações entre pessoas, sistemas e processos.
- O analista observa atividades reais, registra tarefas, comportamentos e contexto.
- Analista atua como iniciante e aprende fazendo.

### Como Realizar?

**1. Preparação**

- Definir objetivos:
  - Escopo: quais tarefas existem.
  - Profundidade: como as tarefas são executadas.
  
- Identificar:
  - Pessoas a observar (especialistas e novatos)
  - Atividades relevantes
  - Momentos adequados (eventos comuns e raros)
    
- Definir postura:
  - Passiva (invisível) → não interfere
  - Ativa (visível) → faz perguntas durante a observação
  - Sempre que possível, observar mais de uma vez

**2. Execução**

- Apresentar-se e explicar o objetivo.
- Garantir que não há julgamento do trabalho
- Observar e registrar Passos realizados, Dificuldades, Comportamentos.
- Pode pedir para o usuário “pensar alto”.
- Fazer perguntas (se abordagem ativa).

**3. Finalização**

- Organizar respostas e descobertas.
- Criar memória de levantamento.
- Validar com os participantes.
- Comparar observações de diferentes pessoas.
- Identificar padrões e divergências.

### Vantagens

- Visão realista do trabalho
- Identifica processos informais, requisitos implícitos
- Útil quando usuários não sabem explicar bem, não há tempo para entrevistas.
- Excelente para requisitos de usabilidade.
- Demonstra envolvimento com o cliente.

### Desvantagens

- Só funciona bem com processos existentes.
- Mais demorada e custosa que outras técnicas.
- Pode não capturar eventos raros ou exceções.
- Pode gerar desconforto nos observados e alteração no comportamento natural.

## Entrevista

- Técnica amplamente utilizada para levantamento de requisitos.
- Baseada em diálogo entre entrevistador e entrevistado.
- Exige preparação e habilidades de comunicação.
- Problemas comuns: Falta de experiência, Falta de preparo e Foco excessivo em anotações.

### O que é?

- 
