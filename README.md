# Fonte de Tensão Ajustável :electric_plug::fire: 
## Descrição:
Projeto de uma Fonte de Tensão ajustável entre 3V a 12V com capacidade de 100mA para Disciplina de "Eletrônica para Computação"
## Participantes:
* Ana Rita Marega Gonçalves - 15746365
* Luiz Henrique Martins Silva - 15695612 [GitHub](https://github.com/LuizUSP)
* Matias Aldrighi Mendonça - 11485044 
* Pedro Henrique Marques de Carvalho Silva - 16819166  [GitHub](https://github.com/PEDROHMCS)
## Componentes Utilizados:
| Quantidade  | Componente | Especificação | Valor |
| ------------- | ------------- | ------------- | ------------- |
| 1  | Ponte retificadora  | 2W 10 2A 800V JINNAN |  R$ 3,90    |
| 1  | Led |  5MM VM DIFUSO  |   R$ 0,50    |
| 1  | Capacitor ELCO | 470uF 50V | R$ 4,40 |
| 1  | Resistor | CR25 3K CARVÃO | R$ 0,07 |
| 1  | Resistor | CR25 1K CARVÃO LGE | R$ 0,07 |
| 1  | Resistor | 5W 100R 5% METAL FILME LGE | R$ 1,90 |
| 1  | Resistor | 5W 120R 5% METAL FILME LGE | R$ 1,90 |
| 2  | Resistor | CR25 2K2 CARVÃO ROHS | R$ 0,14 |
| 1  | Potenciômetro | 1W B10K  B-16,5XE-20XR-7MM | R$ 7,00 |
| 1  | Diodo Zener | 13V 1W | R$ 1,00 |
| 1  | Transistor | 2N2222A NPN 60V 0,8A TO-92 | R$ 2,55 |
| 1  | ProtoBoard | BB-01 400P S/BASE TOWER++ | R$ 21,70 |
| 4  | Jumpers |  Macho x Macho| R$ 2,80 |
|TOTAL| | | R$ 47,93 |
## Explicação dos Componentes:
#### Ponte retificadora:
 > Converte corrente alternada (CA) em corrente contínua pulsante (CC). Funcionando como um sistema coordenado de válvulas eletrônicas, direciona ambos os semiciclos da onda CA para a mesma polaridade na saída, eliminando ciclos negativos e permitindo conversão eficiente de energia
#### Led:
 > Indica visualmente o funcionamento correto do circuíto, quando acesso sinaliza estado ideal de funcionamento do projeto.
#### Capacitor ELCO:
 > O capacitor funciona como reservatório energético, armazenando cargas elétricas temporariamente durante os picos de tensão e liberando-as nos momentos de baixa tensão. Em circuitos retificadores, ele atua como filtro capacitivo, suavizando as variações da corrente pulsante pós-retificação por diodos, reduzindo assim a ondulação residual (ripple) e aproximando a saída de uma tensão contínua estável necessária para alimentação de componentes eletrônicos sensíveis.
#### Resistores:
 > Incluídos para controlar corrente em diferentes partes do circuito: um para o LED, outro para o Zener (evitando superaquecimento), dois para o Potenciômetro para ser equivalênte a 4,4K e outro resistor de 100 ohms e 5W. O último de 120 ohms foi usádo para testes
#### Potenciômetro:
 > O potenciômetro é utilizado para alterar a resistência elétrica em um ponto específico do circuito, permitindo o controle da voltagem. No nosso circuito, ele será responsável por tornar a tensão de saída da fonte ajustável entre 3V e 12V.
#### Diodo Zener:
 > O diodo Zener é um componente semicondutor projetado para operar em polarização reversa, mantendo uma tensão constante entre seus terminais (tensão Zener) quando atingida sua tensão de ruptura específica. Diferentemente dos diodos convencionais, ele utiliza o efeito de avalanche controlada para regular voltagem em circuitos, sendo essencial em aplicações como estabilização de tensão em fontes de alimentação e proteção contra sobretensões em sistemas eletrônicos sensíveis.
#### Transistor:
 > Utilizado em conjunto com o Zener para regular a tensão de saída, limitando-a a 12V conforme necessário.
#### ProtoBoard:
 > A protoboard é uma placa de desenvolvimento com orifícios interconectados internamente que possibilita a montagem temporária de circuitos eletrônicos por meio da inserção direta de componentes como resistores, LEDs e jumpers, dispensando soldagem. Sua estrutura modular permite configurações experimentais rápidas e ajustes imediatos, sendo amplamente utilizada na fase preliminar de projetos eletrônicos por estudantes e entusiastas devido à sua praticidade na validação de conceitos antes da implementação definitiva.
#### Jumpers:
 > Existem para fazer as conexões entre os componentes da protoboard, em uma placa as ligações estariam feitas
## Circuito no Falstad:
![image alt](https://github.com/AnaMarega/FonteTensao/blob/f436cd44fb827ac39bfd92e1c80f2b5ed529b291/imagens/Simula%C3%A7%C3%A3o%20Falstad.jpg)
Link: https://tinyurl.com/2a6x5lbq
## Projeto no EAGLE:
![image alt](https://github.com/AnaMarega/FonteTensao/blob/2b7a66db5d745a8cc134184e56ce26674c515683/imagens/Esquem%C3%A1tico%20do%20Circuito.jpg)
![image alt](https://github.com/AnaMarega/FonteTensao/blob/adae815034c13f89240ee65d87237884d07f4e26/imagens/PCB.jpg)
## Fotos do Projeto
![image alt](https://github.com/AnaMarega/FonteTensao/blob/d1f34a75e154eb9c451faf048a0355d1fe597a7a/imagens/Foto%20Projeto.jpg)
![image alt](https://github.com/AnaMarega/FonteTensao/blob/111715b77910dfdcfde4a9064123c017a9db8c59/imagens/Foto%20Projeto2.jpg)
## Video do Projeto:







