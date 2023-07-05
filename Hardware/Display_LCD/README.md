

Guia Completo do Display LCD – Arduino
- https://blog.eletrogate.com/guia-completo-do-display-lcd-arduino/

LCD 16×2 com Interface I2C:
- GND – conecte no terra (pino 6) do Raspberry Pi 
- VCC – conecte no pino +5V (pino 2) do Raspberry Pi  
- SDA – serial Data – interface I2C => GPIO_02 (pino 3) do Raspberry Pi 
- SCL – serial Clock – interface I2C => GPIO_03 (pino 5) do Raspberry Pi 

O chip PCF8574 possui alguns endereços I2C já definidos, dependendo do modelo (identifique o chip do seu módulo):

- PCF8574 = 0x20H
- PCF8574A = 0x38H

O potenciômetro Azul nessa interface é usado para ajuste do contraste. 
Após o Display energizado e programado, ajuste-o para tornar a imagem visível. 
O jumper LED é usado para ativar o LED Backlight.
