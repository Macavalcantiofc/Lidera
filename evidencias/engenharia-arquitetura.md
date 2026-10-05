# Evidências | Engenharia e arquitetura

## Evolução da visão arquitetural

### Visão inicial
Havia uma associação mais simples entre microserviço e desacoplamento.

### Visão atual
A experiência com sistemas de maior escala ampliou a compreensão de que desacoplamento e escalabilidade vão além da separação física em microserviços.

Hoje a análise considera:
- dependências;
- contratos;
- eventos;
- integrações assíncronas;
- concorrência;
- resiliência;
- capacidade de evolução;
- volumetria;
- sistemas externos;
- ambientes desconhecidos;
- efeitos em cadeia.

## Experiência de modernização
A migração de Access/VB para .NET ampliou o repertório em MVC, SQL Server, APIs REST, JavaScript/jQuery, C#, paralelismo, memória, queries e modelagem de dados.

Posteriormente, a modernização de soluções BNDES trouxe contato com cloud, Java, Python, bancos não relacionais, eventos, processamento assíncrono, resiliência e soluções desacopladas.

## Sistemas de alta volumetria
O contato com sistemas que recebem centenas de chamadas por segundo e com integrações concorrentes em ambientes desconhecidos contribuiu para diferenciar a visão atual de engenharia em relação a uma visão puramente de implementação.

## Visão sistêmica
A arquitetura passou a ser analisada considerando o sistema como uma cadeia de capacidades e dependências, e não como componentes isolados.

Isso aparece também no caso da modelagem Salesforce/BNDES, em que o risco não estava apenas no componente construído, mas no impacto que o contrato de dados causaria no próximo sistema.

## Atuação atual como Tech Lead
A visão arquitetural é aplicada em conjunto com definição de soluções, influência sobre decisões, liderança de projetos, condução de equipes e interação com produto.

## Evidências a aprofundar
Registrar:
- arquiteturas específicas;
- diagramas antes/depois;
- indicadores de performance;
- volumetria;
- redução de acoplamento;
- disponibilidade/resiliência;
- incidentes evitados;
- trade-offs;
- decisões com impacto mensurável.
