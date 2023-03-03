# Sistemas Distribuídos - Aula 01 (pós carnaval)

## Roteiro

Fundamentos de Eletrônica

Introdução de Arduino

Tinkercad

<br/>

## Fundamentos de Eletrônica

Eletrônica

- A arte e ciência de controlar a eletricidade usando eletricidade;
- É provavelmente a descoberta que teve a maior influência na cultura do século 20;
- Tensão, corrente e resistência;

Componentes eletrônicos

- Protoboard -> Placa cheia de furos que, em baixo dela, há uma placa metálica que permite a conexão entre os componentes

- Potenciômetro -> Regulador de tensão

- Motor Corrente Contínua -> Comumente chamado de "Motor DC "(derivado do inglês)

- Servo Motor-> Tem como objetivo trabalhar com ângulos de abertura de giro (necessário em braços mecânicos, por exemplo)

- Led -> Sigla significa, em português, Diodo emissor de Luz (Light Emitter Diode)

- Led RGB -> Transparente, você programa a cor que você quiser misturando vermelho, verde e azul (rgb). Apresenta dois terminais: ânodo e cátodo, anodo sendo negativo e o cátodo sendo positiva. Led RGB pode ter 4 terminais: 1 pro vermelho, 1 pro verde, 1 pro azul e 1 para "alimentação"

- Capacitor ->

- Resistor ->

<br/>

## Introdução ao Arduino

O Arduino é uma plataforma utilizada para prototipação de circuito eletrônicos.;

O Projeto do Arduino teve início em 2005 na cidade Ivrea, Itália;

O Arduino é composto por uma placa com um microcontrolador e um ambiente de programação;

Projeto de **hardware livre**;

Quando falamos em Arduino, nos referimos tanto à placa quanto à IDE de programação;

Existem muitos modelos de Arduino, sendo o mais comum o **Arduino Uno**;

Curiosidade: Arduino Lily Pad -> Tem tamanho de uma moeda de um real;

Apresenta pinos de conexão, para que se conecte-se os componentes nele;

Os Arduinos costumam ter os componentes acoplados e desacoplados. Alguns dos modelos precisam que os componentes sejam soldados.

**O Tinkercad (plataforma que vamos utilizar para mexer com o arduíno) simula o Arduíno Uno**

Quando damos **reset** no Arduino, apenas reiniciamos o programa vigente no arduíno.

Arduino - The Documentary

<br/>

## Tinkercad

Sistema Web que possibilita:

- Modelagem 3D
- Simulação de circuitos eletrônicos
- Programação

## Documentário Arduino

Arduino foi criado para possibilitar que pessoas que não tinham muito dinheiro pudessem trabalhar/mexer com esse tipo de tecnologia, uma vez que ele é barato e open source, logo, tudo que você constrói com o arduino você pode usar e vender sem ter que pagar nada pra ninguém.

## BuiltIn Functions e seus usos

pinmode -> Função que serve para setar o modo de configuração de um pino. Exemplo:

- pinMode(LED_BUILTIN, OUTPUT); LED_BUILTIN (módulo default, 13).

digitalWrite -> Função para passar instrução para um pino. Exemplo:

- digitalWrite(LED_BUILTIN, HIGH);
- digitalWrite(LED_BUILTIN, LOW);
