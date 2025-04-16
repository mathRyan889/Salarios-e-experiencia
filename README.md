#Análise de Salário vs. Experiência em Ciência de Dados


Este projeto realiza uma análise simples e didática para explorar a relação entre salários e experiênciae experiência (manutenção) em anos para cientistas de dados , utilizando apenas Pythonem anos para cientistas de dados, utilizando apenas Python puro. Ideal para iniciantes que querem entender como transformar dados simples em informações úteis.

🧠 Objetivo
Investigar como o tempo de experiência impacta o salário de profissionais da área de ciência de dados, utilizando agrupamentos por anos de experiência e meios salariais.

🛠️ Ferramentas Utilizadas
Python 3

Google Colab

defaultdictda bibliotecacollections

🔍 O que foi feito
Estruturação dos Dados Os dados
Os dados consistem em pares (salário, anos de experiência).

Agrupamento Inicial por Tempo Exatosalário para
Calculamos o salário médio para cada valor exato de experiência.

Criação de Buckets de Experiência Agrupamos
Agrupamos os anos de experiência em categorias:

Menos de 2 anos

Entre 2 e 5 anos

Mais de 5 anos

Cálculo das Médias por Bucket Calculamos a média salarial para cada grupo
Calculamos um salário médio para cada grupo de experiência, tornando os dados mais significativos.

🧪 Exemplo de Resultado
pitão

Cópia

Editar
{
  'more than five': 79166.67,
  'less than two': 48000.00,
  'between two and five': 61500.00
}
📁 Como Usar
Clonar este repositório:

festança

Cópia

Editar
git clone https://github.com/mathRyan889/Salarios-e-experiencia.git
Acesse o notebook via Google Colab clicando no badge acima ☝️

Execute célula por célula para entender a lógica por trás da análise!

🤔 Possibilidades de Expansão
Visualização gráfica (matplotlib ou seaborn)

Modelagem preditiva com regressão linear

Inclusão de novos dados ou fontes externas
