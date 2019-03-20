# Contexto:

A provi é uma fintech que oferece crédito para pessoa física sem garantia, com o intúito de fomentar a educação especializada no Brasil. Financiamos cursos e especializações (presencias ou online) para designers, programadores, data scientits, digital marketers, etc.

### Challenge provi

Imagine que você recebeu a missão de construir um dashboard onde os usuários que tomaram empréstimos podem ver suas parcelas em aberto, valor total da dívida, total de juros, etc...

Olhando esse desafio pela ótica do cliente, quais funcionalidades você imagina que sejam ideais para um dashboard de gestão e acompanhamento do empréstimo?

Com isso em mente, imagine que vc é um "single dev army" e tem a responsabilidade de desenvolver um MVP desse dashboard e apresentar para o resto do time.

### Caso vc aceite o desafio:

1. Clone esse repositório.
2. Desenvolva o dashboard usando React
3. Todas as informações de um empréstimo podem ser encontradas nesse endpoint (http://www.mocky.io/v2/5c923b0932000029056bce39)
4. Sinta-se a vontade para fazer chamadas http como preferir
5. Sinta-se a vontade para usar algum framework de UI/UX ou fazer o próprio design
6. Ao terminar, faça um commit do seu challenge e suba esse repositório para o GitHub
7. Caso você sinta necessidade de "chumbar" algum texto na tela que não esteja na API (nome do usuário, foto, email, mensagens, etc), não tem problema
8. Envie o link do seu repositório para luciano@provi.com.br

### O que gostaríamos de ver:

1. Bons princípios de UI/UX
2. Boa noção de componentização e código organizado
3. Um dashboard com funcionalidades condizentes à gestão de um empréstimo pessoal

### Diferencias

1. Usar Redux para gerenciamento de estado

### Observações

1. Caso tenha alguma dúvida durante o challenge, fique a vontade pra entrar em contato conosco.
2. Esse challenge não deve tomar mais do que 3 horas do seu tempo. É apenas um protótipo.
3. Explicação dos dados no ENDPOINT do empréstimo:
   ~> totalAmountInTaxes: Valor total de juros no empréstimo
   ~> monthlyInterest: Taxa de juros mensal
   ~> amountPayd: Valor total pago
   ~> amountTaken: Valor total emprestado
   ~> installments: todas as parcelas do empréstimo
