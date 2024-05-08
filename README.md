## Sobre o Projeto
Este projeto consiste na construção de um sistema de hospedagem para realizar reservas em um hotel. O sistema será desenvolvido em C# e utilizará as classes Pessoa, Suíte e Reserva para representar os hóspedes, as suítes disponíveis e as reservas feitas, respectivamente. O principal objetivo do sistema é calcular corretamente os valores das reservas, considerando a quantidade de hóspedes e o valor da diária, com a aplicação de um desconto de 10% para reservas com duração superior a 10 dias.

## Classes Utilizadas

### Classe Pessoa
Esta classe representa os hóspedes do hotel. Ela contém atributos como nome, idade, e outros dados relevantes sobre o hóspede.

### Classe Suíte
A classe Suíte é responsável por representar as diferentes opções de suítes disponíveis no hotel. Cada suíte possui características como capacidade máxima de hóspedes, categoria, e preço da diária.

### Classe Reserva
A classe Reserva faz o relacionamento entre as classes Pessoa e Suíte, representando uma reserva específica feita por um hóspede em uma suíte. Ela calcula corretamente os valores da reserva com base na quantidade de hóspedes e no valor da diária da suíte escolhida. Além disso, aplica um desconto de 10% para reservas com duração maior que 10 dias.

## Funcionalidades

O sistema de hospedagem será capaz de

- Registrar informações de novos hóspedes.
- Mostrar as opções de suítes disponíveis.
- Realizar reservas para os hóspedes nas suítes escolhidas.
- Calcular corretamente o valor total da reserva, aplicando descontos conforme necessário.

## Execução do Programa

Para executar o programa, basta rodar o script principal que irá interagir com o usuário, permitindo-o realizar as operações desejadas, como registrar um novo hóspede, fazer uma reserva, ou consultar as suítes disponíveis.

## Considerações Finais

Este projeto visa fornecer uma solução eficiente para o gerenciamento de reservas em um hotel, garantindo que os valores sejam calculados corretamente e que os hóspedes tenham uma experiência satisfatória durante sua estadia.
