# Challenge BI - 3ª e 4ª semanas

<H1>Dashboard de Logística</H1>

A empresa Alura Store precisa entender como anda a sua área financeira (pensando em hipóteses).

Desenvolveremos um dashboard tático da área financeira de uma empresa, no qual vamos criar duas páginas, sendo uma delas exibindo um overview de toda a área financeira e a outra página realizando uma análise de cenários.

Teremos duas etiquetas indicando o que precisaremos pensar, sendo elas:
1 - Overview financeiro.
2 - Análise de cenário.

<h2>Base de Dados</h2>

Foram disponibilizadas 4 bases de dados no formato .SQL com a seguinte estrutura:

<h3>Tabela Notas fiscais</h3>
<ul>
  <li>id_nota</li>
  <li>numero_nota</li>
  <li>id_pedido</li>
  <li>id_vendedor</li>
  <li>valor_venda</li>
  <li>frete</li>
  <li>imposto</li>
</ul>

<h3>Tabela Produtos</h3>
<ul>
  <li>id_produto</li>
  <li>categoria_produto</li>
  <li>preco</li>
  <li>custos</li>
</ul>
  
<h3>Tabela Vendedores</h3>
<ul>
  <li>id_vendedor</li>
  <li>nome_vendedor</li>
</ul>

<h3>Tabela Pedidos</h3>
<ul>
  <li>Data da compra</li>
  <li>id_pedido</li>
  <li>id_produto</li>
  <li>quantidade</li>
</ul>

<h2>Ferramentas utilizadas</h2>

Foi utilizado somente o Power BI para desenvolver o Dashboard

<h2>Métricas</h2>
<ul>
  <li>Receita;</li>
  <li>Lucro;</li>
  <li>Custos;</li>
  <li>Despesa;</li>
  <li>Métricas mensais;</li>
  <li>Escolher ano a ser analisado;</li>
  <li>Análise de cenário;</li>
</ul>

<h2>Relacionamentos</h2>
<ul>
  <li>Notas Fiscais -- Vendedores</li>
  <li>Notas Fiscais -- Pedidso</li>
  <li>Pedidos -- Produtos</li>
</ul>

<h2>Link do Dashboard</h2>

https://app.powerbi.com/view?r=eyJrIjoiMjk4OWU0MjUtMjc4ZS00ZTdiLTgyZmUtYTI1YjI0ZGJjMmNiIiwidCI6IjA3Njg1MDA5LTg5NzAtNGFkNC05MmU1LTkzOWFhYTc1MGZmZCJ9
