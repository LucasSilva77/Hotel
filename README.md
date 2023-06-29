# README - Sistema de Reservas do Hotel
Este é um programa de reservas para um hotel, onde você pode realizar diferentes tarefas, dependendo da opção selecionada.

## 1) Quantos quartos são? 
Nesta opção, o programa permite que você informe o valor de uma diária no hotel e a quantidade de dias de hospedagem desejada. Em seguida, ele valida as informações para garantir que sejam válidas. O valor da diária não pode ser negativo e a quantidade de dias não pode ser negativa ou maior que 30. Caso alguma informação inválida seja inserida, o programa exibirá "Valor inválido" e retornará ao menu inicial. Caso as informações sejam válidas, o programa solicitará o nome do hóspede e, em seguida, perguntará se o usuário confirma a reserva.

## 2) Como soletra?
Nesta opção, o programa permite o cadastro de hóspedes. É solicitado o valor padrão da diária e, em seguida, é possível cadastrar vários hóspedes, informando seus nomes e idades. Caso o hóspede tenha menos de 6 anos, a diária é gratuita, e essa informação é exibida na tela. Caso o hóspede tenha mais de 60 anos, ele paga metade da diária, e essa informação também é exibida. O programa continuará a receber os nomes e idades dos hóspedes até que a palavra "PARE" seja digitada, interrompendo a entrada de dados. Ao final, o programa exibirá a quantidade de gratuidades, a quantidade de meias hospedagens e o valor total considerando todos os hóspedes informados.

## 3) Com "S" ou com "Z"?
Nesta opção, o programa permite o cadastro e pesquisa de hóspedes. O usuário pode selecionar entre diferentes opções: cadastrar, pesquisar, listar e sair.

A opção "cadastrar" permite que o usuário informe o nome de um hóspede e o programa o cadastra em memória. É possível realizar até 15 cadastros, e caso o limite seja atingido, será exibida a mensagem "Máximo de cadastros atingido".

A opção "pesquisar" permite que o usuário informe o nome de um hóspede e o programa verifica se o nome exato foi encontrado. Em caso afirmativo, é exibida a mensagem "Hóspede (nome) foi encontrado". Se o nome não for encontrado, será exibida a mensagem "Hóspede não encontrado".

A opção "listar" exibe todos os hóspedes cadastrados um a um.

O programa permite que o usuário realize essas operações repetidamente até escolher a opção "sair".

## 4) Festa ou trabalho?
Nesta opção, o programa permite o cálculo do custo total para contratar garçons em um evento. O usuário precisa informar o número de garçons necessários e o total de horas do evento. O programa então calcula o custo total com base no valor de R$10,50 por hora por garçom e exibe o resultado na tela. Por fim, o programa pergunta se o usuário aceita os valores. Se a resposta for "S" (sim), é exibida a mensagem "Reserva efetuada com sucesso". Caso contrário, o programa retorna ao menu principal.

## 5) Hora de comer
Este projeto consiste em um programa que calcula a quantidade de água, café e salgados necessários para um evento realizado em um salão de um hotel. Além disso, o programa também calcula o custo total com comida do evento, com base nos preços estabelecidos. Por fim, o usuário será solicitado a confirmar os valores, e a reserva será efetuada caso a resposta seja "SIM".

## 6)Auditório do Hotel
Este é um programa desenvolvido para ajudar a determinar qual dos dois auditórios de um hotel é o mais adequado para um evento, com base no número de convidados. O hotel possui dois auditórios: Laranja e Colorado.
O auditório Laranja possui 150 lugares e espaço para até 70 cadeiras adicionais. Já o auditório Colorado tem capacidade para 350 lugares, sem a possibilidade de adicionar mais cadeiras.

O programa desenvolvido recebe como entrada o número de convidados para o evento e realiza a seguinte verificação:

-Se o número de convidados for maior que 350 ou menor que zero, exibe a mensagem "Número de convidados inválido". <br>
Caso o número de convidados seja válido, o programa determina qual dos auditórios é o mais adequado, dando prioridade ao Auditório Laranja. <br>
-Se o auditório Laranja for escolhido, o programa calcula a quantidade de cadeiras adicionais necessárias, levando em consideração o limite de 70 cadeiras adicionais. <br>

## 7)Reserva no Restaurante do Hotel
Este é um programa desenvolvido para verificar a disponibilidade do restaurante do hotel para reservas, levando em consideração os dias da semana e os horários de funcionamento.

Funcionalidade
O restaurante do hotel está disponível para reservas de acordo com os seguintes horários:

Segunda a sexta-feira: das 7h às 23h.
Sábados e domingos: das 7h às 15h.
O programa realiza as seguintes tarefas:

-Recebe o dia da semana em formato de texto (letras minúsculas, sem acentos). <br>
-Recebe a hora do dia (apenas o número inteiro, desconsiderando minutos e segundos). <br>
-Verifica se o restaurante está disponível de acordo com as regras especificadas acima. <br>
-Quando o restaurante estiver disponível, o programa solicita o nome da empresa que deseja fazer a reserva. <br>
-Exibe na tela a mensagem "Restaurante reservado para (nome da empresa): (dia da semana) às (horas)h" quando a reserva for realizada com sucesso. <br>

## 8) Comparador de Combustível - Álcool ou Gasolina
Este é um programa desenvolvido para ajudar a determinar qual é o combustível mais atraente e qual posto de gasolina oferece o preço mais baixo para abastecer o carro do hotel.

Funcionalidade
O programa realiza as seguintes tarefas:

-Recebe os valores do álcool e da gasolina nos postos Wayne Oil e Stark Petrol. <br>
-Calcula qual é o combustível mais atraente com base na relação de preços. <br>
-Verifica qual posto de gasolina oferece o preço mais baixo para o combustível selecionado. <br>
-Informa ao usuário qual é o combustível mais atraente e qual posto de gasolina oferece o preço mais baixo. <br>

## 9)Orçamento de Manutenção de Ar Condicionado
Este é um programa desenvolvido para calcular o valor total do serviço de manutenção de ar condicionado em diferentes empresas terceirizadas, levando em consideração o valor por aparelho, a quantidade de aparelhos em manutenção, o percentual de desconto e a quantidade mínima de aparelhos para que o desconto seja aplicado.

Funcionalidade:
O programa realiza as seguintes tarefas:

-Recebe o valor do serviço por aparelho, a quantidade de aparelhos em manutenção, o percentual de desconto e a quantidade mínima de aparelhos para que o desconto seja aplicado. <br>
-Calcula o valor total do serviço com base no valor por aparelho e na quantidade de aparelhos. <br>
-Verifica se a quantidade de aparelhos é maior que a quantidade mínima para que o desconto seja aplicado. <br>
-Se a quantidade de aparelhos for maior ou igual à quantidade mínima, aplica o desconto sobre o valor total do serviço. <br>
-Exibe na tela o valor total do serviço para cada empresa informada. <br>
-Ao final, identifica e exibe o orçamento de menor valor entre as empresas informadas. <br>
