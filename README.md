# GS-2024-Edge
Global Solution de Edge 2024 

OceanGuard

Este é um projeto para criar um sensor subaquático que monitora a temperatura da água usando um sensor DS18B20, além de medir a salinidade e o nível de oxigênio dissolvido na água. O projeto utiliza um Arduino, um módulo RTC DS1307 e sensores analógicos para medir a salinidade e o nível de oxigênio.

Requisitos e Dependências:

Hardware:
Arduino Uno ou equivalente
Sensor DS18B20
Módulo RTC DS1307
Sensores analógicos para salinidade e oxigênio dissolvido
Protoboard
Cabos jumper
Resistores de pull-up de 4.7kΩ (para linhas SDA e SCL)

Software:
Arduino IDE

Bibliotecas:
OneWire
DallasTemperature
Wire
RTClib

Instruções de Uso:

Montagem do Hardware:

Conecte o DS18B20, o módulo RTC DS1307 e os sensores analógicos à protoboard conforme indicado no esquema de conexão.

Configuração do Código:

Abra o código fonte fornecido no Arduino IDE.
Certifique-se de ter instalado todas as bibliotecas necessárias.
Verifique se os pinos definidos no código correspondem aos pinos físicos usados na montagem.

Upload do Código:

Conecte o Arduino ao computador via USB.
Selecione a placa correta e a porta serial no Arduino IDE.
Faça o upload do código para o Arduino.

Monitoramento:

Abra o Serial Monitor na Arduino IDE.
Você verá as leituras de temperatura, salinidade e oxigênio dissolvido da água sendo exibidas em intervalos regulares.
As leituras serão exibidas no formato "DD/MM/YYYY - Temperatura: X °C - Salinidade: Y ppt - Dissolved Oxygen: Z mg/L".

Observações:
Certifique-se de calibrar os sensores de salinidade e oxigênio dissolvido conforme necessário para garantir leituras precisas.
O módulo RTC DS1307 é usado para fornecer informações de data e hora precisas ao projeto. 
