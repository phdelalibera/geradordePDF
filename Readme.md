O que esse código faz?
- Esse código consiste em um gerador de PDF simples de um Orçamento.

Como funciona?
- Primeiro, o usuário deve inserir os dados do seu Orçamento, tais como: descrição do projeto, a quantidade de horas previstas, o valor da hora trabalhada e por fim o prazo do projeto.
- Posteriormente iremos efetuar o cálculo do valor do Orçamento(total de horas estimadas * valor da hora de trabalho).
- Por fim, iremos executar os seguintes passos abaixo utilizando a biblioteca fpdf:
   • Criaremos a arquivo PDF;
   • Adiconaremos uma página ao pdf e alteramos a fonte para Arial;
   • Iremos inserir o arquivo de template ao PDF;
   • Iremos inserir os dados do projeto definido anteriormente nas variáveis;
   • Iremos salvar o arquivo PDF e depois mostraremos a mensagem "Orçamento gerado com sucesso!".
