# _Exercicio_

- <div style="float: right; width: 120px; height: 160px; background-image: url('../img/monstro-terrivel.png')"></div>
  Conheça o <span style="font-family: 'Ravie', serif; text-shadow: 2px 2px rgb(102, 102, 102)">Incrível <span style="color: #00FF21">Monstro Verde</style> que Come Pedras e Mora Debaixo da Terra</span>
- Objetivo:
  1. Dar comida para o terrível monstro verde (etc. etc.)
  1. Entender o funcionamento de um formulário web
  1. Entender a diferença entre os métodos http GET e POST

O terrível monstro verde (etc. etc.) está com fome e você deve dar comida para
ele. Ele acaba de ir para a superfície e para que ele não comece a comer
pessoas, você deve dar a ele seu segundo alimento preferido: pedras.

Para isso, você deve ir até onde ele está e enviar algumas pedras para ele.
Atualmente, ele está neste endereço: http://terrivel.herokuapp.com/monster.
Para dar comida a ele, você deve encomendá-las a partir de um formulário html.

- Para fazer sua encomenda, você deve **criar uma página com um formulário web**
  especificando o seu pedido. Ele deve conter as seguintes informações:
  - `num_pedras`, [0, &infin;[, &isin; N (quantidade de pedras)
  - `tam_pedras`, [1, 7], sendo 3 o padrão (tamanho das pedras)
    - são permitidos valores decimais a cada 0,5 (e.g.: 1, 1,5, 2)
  - `nome`, para dar um apelido carinhoso ao seu monstro
    - deve conter apenas letras, maiúsculas ou minúsculas

- Você também deve fornecer informações adicionais, como:
  - `corCeu1`, a cor do céu
  - `corCeu2`, outra cor para o céu (fazendo um degradê)
  - `tipo_pedras`, {`'marroada'`, `'ametista'`, `'topazio'`, `'espinela'`}
  - `tipo_pedras_sortidas`, {`não`, `sim`}

- Você deve usar os **elementos de formulários que mais se aproximem** do
  tipo de dados que você precisa representar, _e.g._,
  - `<input type="cor">` para as cores do céu
- O formulário deve ter **validação de acordo com o domínio de cada campo**

## Referências

- [Github - fegemo/cefet-web][page-1]

[page-1]: https://github.com/fegemo/cefet-web/blob/master/classes/html5/README.md#exercício