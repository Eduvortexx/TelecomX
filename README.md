📊 Análise de Churn - TelecomX
🔎 Objetivo
Este projeto visa identificar os principais fatores que levam os clientes da TelecomX a cancelar seus serviços. O foco está em gerar insights práticos que ajudem a empresa a reduzir o churn, melhorar a retenção e otimizar investimentos.

⚙️ Tecnologias
Python 3.9+

Pandas | Matplotlib | Seaborn | Jupyter

📁 Estrutura
TelecomX_BR.ipynb: Análise completa em Jupyter

TelecomX_data_tratados.csv/json: Dados tratados

readme.md: Documentação

▶️ Como Executar
Instale as dependências:

bash
Copiar
Editar
pip install pandas matplotlib seaborn jupyter
Clone e execute o notebook:

bash
Copiar
Editar
git clone https://github.com/dfarneym/TelecomX_BR.git
cd TelecomX_BR
jupyter notebook TelecomX_BR.ipynb
📉 Principais Descobertas
1. Distribuição de Cancelamentos
26,6% dos clientes cancelaram.

Base desbalanceada: maioria dos clientes permanece.

2. Fatores com Maior Impacto
Contrato Mensal: Churn acima de 42%.

Tenure Curto: A maioria dos cancelamentos ocorre nos primeiros meses.

Cobrança Alta: Clientes que cancelam pagam, em média, mais.

Cheque Eletrônico: Associado à maior taxa de evasão.

Perfil Demográfico:

Idosos: 41,7% de churn.

Sem cônjuge: 33%.

Sem dependentes: 31,3%.

Sem serviços adicionais: Tendem a sair mais rápido.

✅ Perfil do Cliente em Risco
Contrato mensal

Cliente novo

Alta fatura mensal

Pagamento por cheque eletrônico

Idoso, sem cônjuge ou dependentes

Não utiliza serviços extras

📌 Recomendações
Migrar contratos mensais para planos longos com benefícios.

Onboarding nos primeiros meses para evitar churn precoce.

Ofertas personalizadas para clientes com cobrança alta.

Incentivar novos métodos de pagamento mais estáveis.

Melhorar o suporte para idosos, com comunicação clara e acessível.

