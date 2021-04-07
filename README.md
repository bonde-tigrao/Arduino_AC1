# Arduino_AC1
## Nossa primeira AC, observe bem o código, procure pelos erros.

Use o FORK para adicionar esse projeto a sua organização antes de começar.

![](https://img.shields.io/github/forks/Leoruiz197/Arduino_AC1)
![](https://img.shields.io/github/stars/Leoruiz197/Arduino_AC1)

![](https://github.com/bonde-tigrao/Arduino_AC1/blob/main/bnn.png)

## **O PROBLEMA:** 

Seu grupo foi contratado para realizar a automação do chão de fábrica de uma farmacêutica responsável por produzir doses de vacina, a automação levará em conta alguns sensores e avisos luminosos para os funcionários responsáveis pela produção.

Após realizar a montagem, vamos conferir a lista de funcionalidades e adicionar cada ponto necessário para completar o desafio.

### Funcionalidades esperadas:

- Um botão para ligar e outro para desligar a produção indicados pelo led vermelho.
- Leitura do sensor de temperatura e teste, ao atingir **15℃** o led azul deve acender, deve ser informado via serial e somente apagar o led quando a temperatura for mais baixa que isso.
- Leitura do sensor de luminosidade e teste, ao indicar um valor acima de **5** a luminosidade do ambiente esta muito alta, deve ser informado via serial e o led verde deve permanecer aceso até a luminosidade diminuir.

