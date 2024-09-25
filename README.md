# piano-no-arduino

Desenvolver um piano eletrônico utilizando o microcontrolador Arduino, onde cada tecla aciona uma nota musical, com controle de tom e volume através de potenciômetros.

Materiais Necessários:

1 Placa Arduino (Uno ou compatível)
12 Botões de pressão (push-buttons)
2 Potenciômetros de 10kΩ
1 Buzzer ou pequeno alto-falante
Fios de conexão (jumpers)
Papelão ou outro material opcional para suporte do piano
Descrição do Projeto: Neste projeto, cada botão está conectado a uma entrada digital do Arduino, representando uma tecla do piano. Cada botão será associado a uma frequência específica de som, que corresponde a uma nota musical. Um buzzer é utilizado para gerar os sons e dois potenciômetros são empregados para ajustar o tom e o volume das notas.

O piano será capaz de tocar 12 notas diferentes, que vão desde a nota Dó até a nota Si em uma oitava. O potenciômetro 1 ajusta o volume do som, e o potenciômetro 2 permite modificar a afinação das notas (tom).

Esquema de Montagem:

Botões: Conecte os 12 botões nos pinos digitais de 2 a 13 do Arduino. Cada botão tem um terminal ligado ao pino digital correspondente e o outro terminal ao GND.
Potenciômetros: O pino central de um dos potenciômetros será ligado à entrada analógica A0 (para controle de volume), enquanto o outro potenciômetro será ligado à entrada A1 (para controle de tom). As extremidades dos potenciômetros serão conectadas ao 5V e GND.
Buzzer: Conecte o buzzer no pino digital 9, com o outro terminal ligado ao GND.

![Mighty Wluff](https://github.com/user-attachments/assets/f41663dd-545e-45c7-819f-042ecd468da3)
