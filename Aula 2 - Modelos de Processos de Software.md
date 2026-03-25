# Modelos de Processos de Software

## Processo de Software

- Conjunto de atividades e resultados associados que levam à produção de um produto de software.
- Não há um processo ideal para todas as situações.

## Modelos de Processos de Software

- São descrições abstratas do processo de desenvolvimento.
- Definem as principais atividades, bem como a ordem em que devem ser executadas.

## Modelo Cascata

- Conhecido também como Ciclo de Vida Clássico.
- Abordagem sequencial e sistemática para o desenvolvimento de software.
- A fase seguinte não pode ser iniciada até que a fase anterior encerre.

### Modelo Cascata Presmann

<p align="center">
  <img width="1017" height="228" alt="Modelo Cascata Presmann" src="https://github.com/user-attachments/assets/53289e82-3526-4d26-8368-ace2131be3f9" />
</p>

### Modelo Cascata Sommerville

<p align="center">
  <img width="600" height="300" alt="Modelo Cascata Sommerville" src="https://github.com/user-attachments/assets/66fa785a-7961-4cc8-8665-032116621a39" />
</p>

### Fases Do Modelo Cascata

#### 1. Definição e Análise de Requisitos

- Os serviços, restrições e metas do sistema são estabelecidos por meio de consulta aos usuários.
- Em seguida, são definidos em detalhes e funcionam como uma especificação do sistema.

#### 2. Projeto de sistemas e de software

- Agrupa os requisitos em sistemas de hardware ou de software.
- Estabelece uma arquitetura do sistema geral.

#### 3. Implementação e teste de unidades

- O projeto do software é desenvolvido como um conjunto de programas ou unidades de programa.
- O teste unitário envolve a verificação de que cada unidade atenda a sua especificação.

#### 4. Integração e teste de sistemas

- As unidades individuais do programa ou programas são integradas e testadas como um sistema completo.
- Após o teste, o sistema de software é entregue ao cliente.

#### 5. Operação e manutenção

- Normalmente, a fase mais longa do ciclo de vida.
- O sistema é instalado e colocado em operação.
- Manutenção envolve a correção de erros que não foram descobertos em estágios iniciais do ciclo de vida.

### Resultados do Modelo Cascata

- Cada fase resulta em um ou mais documentos que são aprovados.
- Gera muita documentação que nem sempre é utilizada.

## Modelo Incremental

- Combina elementos dos fluxos de processos lineares de forma paralelizada.
- Cada sequência linear gera incrementos.
- Cada ciclo ou iteração, uma versão operacional do sistema será produzida e entregue para uso ou avaliação detalhada do cliente.
- Clientes não precisam esperar todo sistema ficar pronto para utilizá-lo.
- Podem utilizar os incrementos iniciais para identificar novas necessidades no sistema.
- Baixo risco de falha geral do projeto.
- Os serviços de mais alta prioridade tendem a passar por mais testes.

### Quando usar o Modelo Incremental?

- **Quando os requisitos estão bem definidos e claros**: os incrementos podem ser planejados e desenvolvidos passo a passo com alterações mínimas nos requisitos.
- **Se o projeto tiver um longo cronograma de desenvolvimento**: a entrega incremental ajuda a gerenciar a complexidade ao longo do tempo, dividindo o projeto em partes menores e mais gerenciáveis.
- **Se o cliente precisar de um lançamento rápido do produto**: você pode entregar os recursos mais críticos logo no início do primeiro incremento, permitindo que ele comece a usar o software mais cedo.
- **Quando você deseja desenvolver primeiro os recursos mais importantes**: isso permite obter feedback antecipado sobre as funcionalidades principais e priorizar melhor os incrementos subsequentes.

### Vantagens do Modelo Incremental

- A entrega antecipada de software melhora a satisfação do cliente.
- Facilidade para gerenciar alterações entre incrementos.
- Melhor gestão de riscos por meio de testes precoces.
- Controle de custos distribuindo o orçamento pelas etapas.
- Depuração simplificada graças ao desenvolvimento modular.
- Alta qualidade de software através de testes contínuos.

### Desvantagens do Modelo Incremental

- Requer equipe qualificada e planejamento adequado.
- O custo pode aumentar devido a testes e integrações repetidos.
- Problemas de projeto se os requisitos futuros não estiverem claros.
- Desafios de integração entre incrementos
- Correção repetida de erros em várias etapas.

## Modelos de Processos Evolucionários

- Software evolui ao longo do tempo, assim que mudam as necessidades de negócio e do produto.
- Prazos de mercado costumam ser curtos, impossibilitando entregar um sistema completo de uma só vez.
- Geralmente os requisitos principais do sistema são conhecidos, mas detalhes precisam ser definidos ao longo do desenvolvimento.
- Para esse cenário, utiliza-se modelos de processo evolucionários, que permitem que o software se desenvolva e melhore gradualmente.
- Esses modelos são iterativos, ou seja, o sistema é construído em várias versões sucessivas, cada uma mais completa que a anterior.

## Modelo Espiral

- Baseado no modelo incremental;
- É um Processo Evolucionário;
- Orientado a riscos
- Cada volta no espiral, percorre todas as fases do processo de software;
- Ideal para softwares que precisam passar por diversas evoluções a medida que são desenvolvidos;
- Diferente do Modelo Incremental, que entrega partes prontas para uso, o Modelo Espiral é mais iterativo, e tenta fazer sucessivos refinamentos.

<p align="center">
  <img width="620" height="380" alt="Modelo Espiral" src="https://github.com/user-attachments/assets/8a0441f9-fbc3-4f4b-b73f-7e807eac2f90" />
</p>

### Fases do Modelo Espiral

#### 1. Definição de objetivos: 

- Os objetivos e requisitos do projeto são identificados.
- Os requisitos funcionais e não funcionais são analisados.
- São exploradas possíveis soluções.

#### 2. Avaliação e redução de riscos: 

- São identificados os riscos relacionados a custos, cronograma, desempenho e tecnologia.
- A melhor solução foi selecionada.
- Os protótipos são construídos para reduzir os riscos.

#### 3. Implementação e validação: 

- Funcionalidades selecionadas são projetadas, desenvolvidas e testadas.
- A próxima versão funcional do software foi criada.

#### 4. Planejamento e Especificação: 

- Os clientes avaliam a versão atual.
- O feedback é coletado.
- O planejamento para a próxima versão começa.

### Vantagens do Modelo Espiral

- **Gestão eficaz de riscos:** Identifica e resolve riscos em todas as fases, sendo ideal para projetos com alto grau de incerteza.
- **Indicado para projetos de grande porte:** Ideal para sistemas de software grandes e complexos.
- **Requisitos flexíveis:** Permite alterações nos requisitos mesmo em estágios posteriores do desenvolvimento.
- **Feedback antecipado do cliente:** Os clientes podem avaliar versões preliminares do produto, aumentando a satisfação.
- **Desenvolvimento iterativo:** o software é desenvolvido em ciclos repetidos, permitindo melhorias graduais.
- **Melhor comunicação:** Revisões regulares melhoram a coordenação entre clientes e desenvolvedores.
- **Alta qualidade de software:** Testes e aprimoramentos contínuos resultam em software confiável e de alta qualidade.

### Desvantagens do Modelo Espiral

- Projetos de grande porte e alto risco.
- Requisitos pouco claros ou em constante mudança.
- Liberações frequentes necessárias.
- É necessário fazer protótipos.
- A avaliação de riscos e custos é fundamental.
- Projetos de longo prazo com incerteza.

## Referências

- PRESSMAN, Roger S.; LOWE, David Brian. Engenharia web. Rio de Janeiro: LTC, 2009;
- SOMMERVILLE, Ian. Engenharia de software. 10. ed. São Paulo: Pearson Education do Brasil, 2019. E-book (Biblioteca Virtual Pearson).

