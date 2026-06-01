# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 01/06/2026
**Empresa:** Melo Indústria
**Responsável:** Vitor Das Neves

---

## Introdução

Este relatório apresenta uma proposta de implementação de serviços simples da AWS na empresa **Melo Indústria**, com foco na redução de custos operacionais, melhor controle financeiro da infraestrutura em nuvem e aumento da eficiência dos recursos tecnológicos.

O objetivo principal do projeto é elencar três serviços AWS que podem contribuir para a diminuição de custos imediatos, evitando desperdícios, otimizando o uso de armazenamento e reduzindo a necessidade de manter servidores ou recursos ativos sem utilização constante.

Os serviços selecionados foram:

1. **AWS Cost Explorer**
2. **Amazon S3 com classes de armazenamento**
3. **AWS Lambda**

---

## Descrição do Projeto

O projeto foi dividido em três etapas, cada uma relacionada a um serviço AWS específico. Cada etapa tem como foco uma oportunidade de redução de custos e melhoria de gestão.

---

## Etapa 1: AWS Cost Explorer

### Nome da ferramenta

**AWS Cost Explorer**

### Foco da ferramenta

Controle, análise e acompanhamento dos custos da AWS.

### Descrição do caso de uso

O AWS Cost Explorer permite visualizar os custos e o uso dos serviços AWS ao longo do tempo. Com essa ferramenta, a empresa consegue identificar quais serviços estão gerando maior gasto, quais recursos estão sendo pouco utilizados e onde existem oportunidades de economia.

Para a Melo Indústria, esse serviço pode ser utilizado para acompanhar mensalmente os gastos com infraestrutura em nuvem, separar custos por serviço, identificar aumentos fora do padrão e apoiar decisões financeiras com base em dados reais.

### Como reduziria os custos da empresa

A redução de custos ocorreria por meio da identificação de recursos ociosos, serviços subutilizados e gastos que não agregam valor ao negócio. Com o Cost Explorer, a empresa conseguiria analisar melhor onde o dinheiro está sendo aplicado e tomar decisões mais assertivas, como desligar recursos não utilizados, ajustar capacidades contratadas e evitar crescimento descontrolado dos custos.

### Ganhos esperados

* Maior visibilidade dos gastos em nuvem.
* Melhor controle financeiro da infraestrutura.
* Identificação de desperdícios.
* Apoio à tomada de decisão do gestor financeiro.
* Previsibilidade dos custos mensais.
* Redução de gastos desnecessários com recursos pouco utilizados.

---

## Etapa 2: Amazon S3 com classes de armazenamento

### Nome da ferramenta

**Amazon S3**

### Foco da ferramenta

Armazenamento de arquivos, documentos, backups e dados históricos com custo otimizado.

### Descrição do caso de uso

O Amazon S3 é um serviço de armazenamento em nuvem que permite guardar arquivos de forma segura, escalável e organizada. A empresa pode utilizá-lo para armazenar documentos administrativos, backups, relatórios, arquivos fiscais, imagens, logs e outros dados corporativos.

Um ponto importante é que o Amazon S3 possui diferentes classes de armazenamento, permitindo que arquivos acessados com frequência fiquem em uma classe mais rápida, enquanto arquivos antigos ou pouco acessados possam ser movidos para classes de menor custo.

### Como reduziria os custos da empresa

A redução de custos seria obtida ao transferir arquivos antigos, backups e documentos pouco acessados para classes de armazenamento mais econômicas. Dessa forma, a empresa evita manter todos os dados em estruturas de custo mais alto, pagando de acordo com a necessidade real de acesso.

Por exemplo, arquivos recentes e utilizados com frequência podem permanecer em uma classe padrão, enquanto arquivos antigos, históricos ou de consulta eventual podem ser migrados para classes mais baratas.

### Ganhos esperados

* Redução de custos com armazenamento de arquivos antigos.
* Melhor organização dos dados corporativos.
* Menor dependência de servidores locais para guardar arquivos.
* Escalabilidade conforme o crescimento da empresa.
* Segurança e alta durabilidade dos dados.
* Possibilidade de criar regras automáticas para movimentar arquivos entre classes de armazenamento.

---

## Etapa 3: AWS Lambda

### Nome da ferramenta

**AWS Lambda**

### Foco da ferramenta

Execução de rotinas, automações e processos sob demanda, sem necessidade de manter servidores ligados continuamente.

### Descrição do caso de uso

O AWS Lambda permite executar códigos e automações sem a necessidade de provisionar ou manter servidores. A empresa paga apenas pelo tempo em que a função é executada, tornando o serviço interessante para processos pontuais ou rotinas automatizadas.

Na Melo Indústria, o AWS Lambda poderia ser utilizado para executar tarefas simples, como processamento de arquivos, envio de notificações, validações automáticas, integrações entre sistemas e execução de rotinas agendadas.

### Como reduziria os custos da empresa

A redução de custos aconteceria ao substituir pequenos servidores ou máquinas virtuais utilizadas apenas para executar tarefas específicas. Em vez de manter um servidor ativo durante todo o dia, mesmo quando não está sendo usado, a empresa poderia executar essas rotinas apenas quando necessário.

Isso evita custos com capacidade ociosa, manutenção de servidor, consumo contínuo de recursos e administração de infraestrutura.

### Ganhos esperados

* Pagamento baseado no uso real.
* Redução da necessidade de servidores dedicados para pequenas rotinas.
* Menor custo operacional com manutenção.
* Maior agilidade para criar automações.
* Escalabilidade automática conforme a demanda.
* Melhor aproveitamento dos recursos de tecnologia.

---

## Visão Financeira da Proposta

A implementação dos três serviços propostos contribui diretamente para uma gestão financeira mais eficiente da infraestrutura em nuvem.

| Serviço           | Oportunidade de economia                                      | Principal ganho financeiro            |
| ----------------- | ------------------------------------------------------------- | ------------------------------------- |
| AWS Cost Explorer | Identificação de desperdícios e recursos ociosos              | Controle e previsibilidade dos gastos |
| Amazon S3         | Armazenamento de arquivos antigos em classes mais econômicas  | Redução de custos com armazenamento   |
| AWS Lambda        | Execução de rotinas sem servidor dedicado ligado o tempo todo | Pagamento somente pelo uso real       |

Essas ações permitem que a empresa reduza custos sem comprometer a operação, mantendo segurança, escalabilidade e controle sobre os recursos utilizados.

---

## Conclusão

A implementação dos serviços **AWS Cost Explorer**, **Amazon S3** e **AWS Lambda** na empresa **Melo Indústria** tem como objetivo reduzir custos operacionais, melhorar a gestão financeira da infraestrutura em nuvem e aumentar a eficiência dos recursos tecnológicos.

Com o AWS Cost Explorer, a empresa passa a ter maior visibilidade dos gastos. Com o Amazon S3, é possível armazenar dados de forma mais econômica e organizada. Com o AWS Lambda, a empresa pode executar rotinas e automações sem manter servidores ativos desnecessariamente.

Como resultado esperado, a Melo Indústria poderá obter maior controle financeiro, redução de desperdícios, melhor aproveitamento dos recursos tecnológicos e mais eficiência operacional.

Recomenda-se que a empresa inicie a implementação por meio do levantamento dos custos atuais, classificação dos arquivos armazenados e identificação das rotinas que podem ser automatizadas, garantindo que a redução de custos seja feita de forma segura e mensurável.
