# FlexLabs - Teste técnico - Calculadora de Parcelas

Este é um técnico criado pela equipe de tecnologia do GrupoFlex (FlexLabs) montado para avaliar as capacidade de um programador de aplicar seus conhecimentos de programação web.

O teste se baseia na "Calculadora de Parcelas", que pode ser encontrada no nosso site (grupoflex.com.br). Essa calculadora tem como objetivo identificar contratos de dívida com bancos em que estejam sendo aplicados juros abusivos. Ela realiza um cálculo tomando como base o valor da parcela informada pelo cliente e apresenta um novo valor de parcela, que corresponde ao seu valor sem os juros abusivos.

Abaixo é possível conferir as tarefas que devem ser realizadas para a conclusão do teste, instruções para realizar a entrega do código implementado, assim como o material de referência que pode ser usado como auxilio na realização do teste

## Tarefas

Segue a lista de tarefas que devem ser realizadas para concluir o teste. 

### 1. Implementando um formulário

A primeira tarefa consiste na criação de um formulário para captação de dados de um usuário, usando React ou NextJS (preferência para o NextJS). O formulário deve conter 4 campos: **"Nome completo"**, **"E-mail"**, **"Telefone"** e **"Data de Nascimento"**, assim como um botão responsável por realizar a submissão do formulário (type="submit").

### 2. Implementando uma Calculadora de Parcelas

Após realizar a implementação do formulário acima, alguns campos devem ser incluídos, para que seja viável a implementação da "Calculadora de Parcelas". Os campos são: **"Valor total da dívida"**, **"Valor da parcela da dívida"**, **"Número total de parcelas"** e **"Número de parcelas pagas"**.

Após a submissão do formulário, deve ser aplicada uma função ao valor da parcela informado pelo cliente. Essa função deve obedecer à seguinte fórmula:

**(Valor da parcela/2) + 7,50**

### 3. Armazenando os dados

Após realizar a implementação do cálculo da "nova parcela" do usuário, você deve implementar alguma forma de persistência de dados, que registre a submissão de formulário e grave o valor de  **todos os campos do formulário**, assim como o valor da **"nova parcela"**

Essa lógica de persistência de dados pode ser implementada da forma com preferir, contanto que ela armazene os dados de forma **permanente**.

OBS: (Aqui você pode optar pela utilização de um banco de dados, ou alguma outra forma de armazenamento como Local Storage ou Cookies)

### 4. Exibindo os dados 

Agora, você deve criar uma forma de exibir os dados gravados na etapa anterior.

A forma de exibição fica à sua escolha, podendo ser em uma página separada do formulário, modal (dialog), etc. 

O importante é que a interface de exibição apresente uma lógica de leitura dos dados armazenados de forma permanente da etapa anterior. 

## Entrega

Para realizar a entrega dessa tarefa, você deve criar um repositório público no Github para armazenar todo o código da solução.

**Importante: o arquivo README.md do repositório deve conter uma documentação curta de como a solução foi desenvolvida, abordando as tecnologias e estratégias utilizadas.**

Após isso, você deve elaborar alguma forma de demonstrar o funcionamento da sua aplicação. Isso pode ser feito  hospedando a página em um servidor, ou gravando um vídeo curto de demonstração, em que a aplicação esteja rodando localmente.

Por fim, basta enviar um email para tecnologia@grupoflex.com.br contendo o link para o repositório do Github em que está concentrado o código da solução, assim como o link para a aplicação hospedada ou para o vídeo de demonstração gravado.

## Materiais de Referência

Estes são alguns links para a documentação das ferramentas que devem ser usadas para a realização do teste, assim com links úteis de pesquisa para a realização do teste.

**Documentação do NextJS** - https://nextjs.org/
**Documentação do ReactJS** - https://react.dev/
**ChatGPT** - https://chatgpt.com/
**Google** - https://www.google.com.

## Dúvidas

Qualquer dúvida que surgir durante a realização das tarefas, sinta-se livre para entrar em contato através do email tecnologia@grupoflex.com.br

### Boa realização do teste!
