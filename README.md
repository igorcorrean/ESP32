# estudos
Aqui contém os programas desenvolvidos para aprimoramento de habilidades de programação

O objetivo é sintetizar o conhecimento em desenvolvimento de projetos utilizando ESP32(o modelo utilizado é o ESP32-WROOM KIT V1) mantendo um registro que pode ser útil
posteriormente.

Para que a placa execute algum comando, como por exemplo energizar uma saída, é necessário gravar este comando na memória flash do SoC. Um programa é um conjunto de 
comandos organizados de forma a executar uma ou mais tarefas. A gravação destes dados pode ser feita de diversas maneiras:via comunicação UART, SPI, Wi-Fi, 
Bluetooth, etc. A escolha vai depender da finalidade da aplicação. Inicialmente utilizei a entrada usb mini pela facilidade.

Para que o USB do Windows 11 (Sistema Operacional que estou utilizando no momento)reconheça e se comunique corretamente com o ESP32 é necessário 
instalar os drivers de comunicação USB para UART CP210x (https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers).

É possível fazer a atualização dos dados gravados na memória de maneira remota através de um web server, utilizando uma rede Wi-Fi ou via bluetooth. É comumente utilizada
a expressão Over-the-air.O blog lastminuteengineer possui um tutorial onde ele ensina em 3 etapas como utilizar o OTA Web Updater com ESP32 (https://lastminuteengineers.com/esp32-ota-web-updater-arduino-ide/)
 utilizando o Arduino IDE e a rede Wi-Fi.
