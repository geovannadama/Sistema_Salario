# Calculadora de Salário
Esta é uma simples calculadora de salário baseada em metas de vendas. Permite calcular o salário final de um funcionário com base em suas metas semanais e mensais de vendas.

## Funcionalidades
O usuário insere o nome do funcionário, a meta semanal de vendas em reais (R$) e a meta mensal de vendas em reais (R$).
Após submeter o formulário, a calculadora processa os dados e exibe o salário final do funcionário com base nas seguintes regras:
O salário mínimo é de R$ 1856,94.
O funcionário recebe um bônus de 1% sobre a meta semanal de vendas.
Se a meta semanal de vendas for superior a R$ 20.000,00, o funcionário recebe um adicional de 5% sobre o excedente da meta semanal.
Se todas as metas semanais de vendas forem atingidas (ou seja, a meta mensal de vendas é igual ou superior a R$ 80.000,00), o funcionário recebe um adicional de 10% sobre o excedente da meta mensal.
O resultado é exibido na página após o cálculo.

## Explicando o código

1. $_SERVER["REQUEST_METHOD"] == "POST": Esta condição verifica se o método de requisição HTTP utilizado é POST. O método de requisição POST é comumente usado para enviar dados de formulários HTML.

2. if (isset()): é uma estrutura de controle em PHP que verifica se uma variável está definida e é diferente de null. É comumente usada para garantir que variáveis estejam inicializadas antes de serem usadas, evitando erros de "variável indefinida".

3. foreach: percorre cada elemento do array e executa o bloco de código especificado para cada elemento. Ele é especialmente útil quando você precisa percorrer todos os elementos de um array sem se preocupar com os índices

4. array_sum(): em PHP é usada para calcular a soma de todos os valores em um array numérico. Ela retorna a soma total dos valores contidos no array.

## Tecnologias Utilizadas
HTML: Utilizado para a estruturação do formulário de entrada de dados.
CSS: Utilizado para estilizar a aparência da calculadora e proporcionar uma melhor experiência visual.
PHP: Utilizado para processar os dados do formulário e calcular o salário final do funcionário.
GitHub: Utilizado como repositório 

## Fontes Utilizadas 
ChatGPT
(https://www.treinaweb.com.br/blog/css-flexbox-um-guia-interativo-parte-1-containers#google_vignette)
(https://cursos.alura.com.br/forum/topico-para-que-serve-especificadamente-a-funcao-foreach-222477)
(https://www.php.net/manual/pt_BR/function.array-sum.php)

