# Evidências | Negócio, produto e impacto

## Evolução da visão de produto

### Primeira experiência
Como estagiário, recebeu uma demanda para criar uma funcionalidade baseada em um registro do sistema para eliminar um fluxo manual de mudança de etapa.

A implementação foi feita com investigação insuficiente, baseada no pedido recebido e no valor esperado.

Na entrega, percebeu-se que o pedido não considerava todas as regras de negócio.

### Consequências
- rollback da implementação;
- invalidação da entrega;
- a demanda acabou sendo despriorizada e posteriormente inviabilizada.

### Aprendizado
Executar corretamente um pedido não significa necessariamente resolver o problema correto.

O padrão evoluiu de:

**pedido → desenvolvimento → entrega**

para:

**problema → investigação → regras de negócio → validação → solução → resultado**.

## Mentor de produto
Desde o início houve um par com experiência de mercado que funcionou como referência e mentor, ajudando a desenvolver a visão de que excelência técnica precisa coexistir com conhecimento profundo do produto e suas particularidades.

## Caso BNDES | Emergência do Rio Grande do Sul

### Contexto
Durante a emergência causada pelas enchentes no Rio Grande do Sul, o BNDES disponibilizou uma linha emergencial para atender empreendedores impactados.

O desafio era disponibilizar rapidamente uma esteira capaz de atender a demanda.

### Restrições
- mais de 500 clientes impactados na lista comercial;
- volume esperado muito superior ao normal;
- necessidade de processamento rápido;
- necessidade de protocolo no BNDES;
- clientes comerciais não sabiam previamente quais operações seriam elegíveis;
- preenchimento manual geraria desperdício operacional;
- havia pressão por uma solução rápida;
- alternativas mais sofisticadas poderiam demandar esforço excessivo.

### Decisão
A discussão caminhava para soluções consideradas mais robustas ou sofisticadas.

Foi feita uma análise de benefício versus esforço e tempo.

A alternativa escolhida foi uma PoC utilizando um robô antigo ainda disponível, mesmo sem ser a solução arquitetural mais indicada para longo prazo.

A PoC:
- lia a planilha utilizada pelo comercial;
- cruzava dados com bases históricas;
- reaproveitava informações existentes;
- criava operações automaticamente;
- deixava para o comercial a responsabilidade principal de validação;
- reaproveitava uma solução do próprio BNDES em homologação para validar elegibilidade.

### Influência e decisão
A ideia foi apresentada inicialmente como hipótese.

Em vez de tentar convencer apenas por argumento, foi construída uma PoC para demonstrar o benefício.

A evidência reduziu a incerteza e permitiu que as pessoas assumissem conscientemente o risco da solução.

### Resultado relatado
Mais de **R$ 580 milhões em recursos do BNDES foram disponibilizados em um único dia** para clientes impactados pelas enchentes.

### Aprendizado
A decisão mais adequada não é necessariamente a tecnologia mais inovadora ou a arquitetura mais elegante.

É a decisão que melhor equilibra:
- tempo;
- momento;
- benefício;
- esforço;
- risco;
- sustentabilidade;
- contexto do negócio.

### Competências
- tomada de decisão;
- pragmatismo;
- visão de negócio;
- gestão de risco;
- priorização;
- influência sem autoridade;
- experimentação;
- orientação a resultado.

## Caso de modelagem Salesforce/BNDES

### Situação
Em uma iniciativa de migração, foi identificada uma modelagem de dados em Salesforce que poderia romper padrões já consolidados no domínio.

O risco estava em não compreender corretamente:
- entidades;
- categorização de linhas;
- chaves;
- relacionamentos;
- linha, produto e subproduto;
- documentação do BNDES;
- necessidades do sistema seguinte.

### Problema
A proposta poderia funcionar localmente, mas gerar desalinhamento para o fluxo de protocolo e aumentar validações e tratamento de dados no próximo sistema.

### Atuação
A experiência acumulada foi usada para identificar o contraditório.

Mesmo com esforço já investido no projeto, houve influência para corrigir a modelagem a tempo, evitando um problema maior na entrega.

### Competências
- visão sistêmica;
- influência;
- qualidade de dados;
- pensamento de cadeia;
- arquitetura orientada ao fluxo de negócio;
- capacidade de discordar de forma construtiva.

## Tese de negócio
Uma solução de tecnologia deve ser avaliada pelo valor que entrega no contexto, e não apenas por sua sofisticação técnica.
