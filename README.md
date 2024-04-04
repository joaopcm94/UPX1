Será de grande importância conhecimentos básicos de eletrônica e programação
para configurar o microcontrolador e escrever o código para controlar o semáforo
com base nos sinais do sensor de presença.

Utilizando um Arduino como microcontrolador programável para criar o protótipo.
Serão conectados os sensores de presença ou infravermelhos ao microcontrolador
para detectar a presença de pedestres. Com base na detecção dos sensores, o
microcontrolador será programado para controlar os sinais dos semáforos. Por
exemplo, quando um pedestre for detectado, o semáforo irá

É importante lembrar que a construção de um protótipo do semáforo com sensor
requer cuidado e atenção, especialmente quando envolve componentes eletrônicos.

Passo a passo:

Conecte o sensor de movimento ao microcontrolador. Geralmente, o sensor de
movimento possui três pinos: VCC (5V), GND (terra) e OUT (saída). Conecte o VCC
ao 5V do microcontrolador, o GND ao GND e o OUT a um pino digital do
microcontrolador.

Conecte o buzzer ao microcontrolador. Conecte um dos terminais do buzzer a um
pino digital do microcontrolador e o outro terminal a um resistor de 220 ohms. Em
seguida, conecte o resistor ao GND.

Opcionalmente, conecte um LED. Conecte o anodo (terminal mais longo) do LED a
um resistor de 220 ohms e, em seguida, conecte o resistor a um pino digital do
microcontrolador. Conecte o catodo (terminal mais curto) do LED ao GND.

Conecte o microcontrolador a uma fonte de energia. Se estiver usando uma bateria,
conecte-a aos pinos apropriados do microcontrolador. Se estiver usando uma fonte
de alimentação, conecte-a à porta de alimentação do microcontrolador.

Escreva o código para o microcontrolador. Você precisará programar o
microcontrolador para ler os dados do sensor de movimento e tomar uma ação
quando um pedestre for detectado. Por exemplo, quando um pedestre for detectado,
o buzzer pode emitir um som e o LED pode acender.

Faça o upload do código para o microcontrolador e teste o seu projeto. Certifique-se
de que o sensor está detectando corretamente os movimentos dos pedestres e que
o buzzer e o LED estão funcionando conforme o esperado.
