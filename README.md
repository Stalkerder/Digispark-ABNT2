**Configuração do Digispark como Teclado ABNT2

Pré-requisitos:
Driver do Digispark instalado no seu computador
IDE do Arduino baixada e instalada

Instruções:
Conecte o Digispark ao seu computador via USB
Abra a IDE do Arduino e selecione "Arquivos" e depois "Preferencias" e Abra o caminho onde o Arduino foi instalado.
Entre no diretorio "packages\digistump\hardware\avr\1.6.7\libraries\DigisparkKeyboard" e copie e cole o arquivo "scancode-ascii-table.h" dentro da pasta para o Digispark funcionar como um teclado ABNT2, 
Agora, o Digispark deve funcionar como um teclado ABNT2 no dispositivo conectado.

Observações:

Alguns dispositivos podem requerer configurações adicionais para funcionar corretamente com o Digispark.
Certifique-se de verificar a compatibilidade do dispositivo com o Digispark antes de tentar usá-lo.