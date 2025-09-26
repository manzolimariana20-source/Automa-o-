Automação de Abertura do YouTube com PyAutoGUI

Este script em Python utiliza a biblioteca PyAutoGUI para automatizar a abertura do navegador Microsoft Edge e, em seguida, acessar o site YouTube.

🛠️ O que o Script Faz

Pressiona a tecla Windows para abrir o menu iniciar.

Digita “Microsoft Edge” e confirma para abrir o navegador.

Aguarda alguns segundos para garantir que o navegador carregue.

Digita “youtube.com” na barra de endereços e confirma para acessar o site.

📦 Requisitos

Python 3 instalado.

Biblioteca PyAutoGUI
.
Instale com:

pip install pyautogui

▶️ Como Executar

Salve o arquivo como abrir_youtube.py.

Feche ou minimize janelas importantes, pois o script controla seu teclado.

No terminal, navegue até a pasta do arquivo e execute:

python abrir_youtube.py

⚠️ Cuidados Importantes

Não use enquanto digita ou mexe em outras janelas, porque o PyAutoGUI envia teclas para o sistema como se fosse você.

Garanta que o Microsoft Edge esteja instalado e que o atalho “Microsoft Edge” esteja disponível no menu iniciar com esse nome.

Se algo travar, pressione rapidamente Ctrl + C no terminal para interromper o script.

📝 Personalização

Para usar outro navegador, altere o texto passado para pa.write() na linha que hoje escreve "Microsoft Edge".

O tempo de espera pode ser ajustado mudando time.sleep(4) para mais ou menos segundos conforme a velocidade do seu computador.
