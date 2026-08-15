Este projeto foi desenvolvido durante a Jornada Python e tem como objetivo analisar o cancelamento de clientes de uma empresa fictícia utilizando Python.

O projeto faz uma análise completa da base de dados, realizando:

Tratamento de dados (remoção de valores nulos, padronização)

Análise exploratória com Pandas

Visualização gráfica com Plotly para identificar padrões de cancelamento

Agrupamentos e médias para entender comportamento de diferentes planos e perfis de clientes

Na base, a taxa de cancelamento é de **56,8%**, e três recortes concentram quase todo o problema:

| Recorte | Clientes | Cancelamento |
|---|---:|---:|
| Contrato mensal | 9.884 | **100,0%** |
| Mais de 4 ligações ao call center | 16.283 | **99,0%** |
| Atraso acima de 20 dias | 9.646 | **100,0%** |

Excluindo os três grupos, o cancelamento do restante cai para **18,4%**. Vale a ressalva: esses grupos somam **47,5% da base** — o número menor vem de retirar quase metade dos clientes, não de uma retenção aplicada. É o resultado do exercício sobre dados fictícios, e a leitura útil é onde o problema se concentra, não a taxa final.

⚙️ Tecnologias Utilizadas

Python

Pandas

Plotly

Jupyter Notebook (VSCode)

🎯 Objetivo do Projeto

Demonstrar como a análise de dados pode identificar problemas e propor soluções, usando Python para:

Entender padrões de cancelamento

Avaliar diferentes contratos e perfis de clientes

Criar gráficos interativos para suportar decisões estratégicas

💡 Aplicações Práticas

Empresas podem identificar clientes com risco de cancelamento

Auxiliar em decisões estratégicas para retenção de clientes

Visualização e interpretação de grandes bases de dados
