# Challenge AIME

AIME é desenvolvido para ser um assistente de compras virtuais relacionados a área de TI. O objetivo é auxiliar o usuário e mostrar o que ele precisa de forma rápida e segura usando Inteligência Artificial.​
AIME é uma aplicação e pode se conectar com diversos tipos de lojas diferentes (que estão relacionadas a área de TI).​

Decidimos desenvolver um chat de voz com o cliente para tornar nosso programa mais acessível. O objetivo é trazer essa aplicação para o mercado e para isso precisamos atender todos os tipos de clientes.

Abaixo, segue o processo de instalação e uso do código apresentado no vídeo.

# Instalações

No terminal da IDE use o seguinte comando:
```
pip install SpeechRecognizer
pip install pyttsx3
pip install pyaudio
pip install bardapi
```

# Valores

Após instalar, entre no site do Google Bard ( bard.google.com ), conecte com a sua conta e entre na tela do chat.

Na tela do chat entre o inspetor de recursos (F12) e procure a aba "Aplicação" ou "Application".

Nesta aba procure os seguintes valores:

  ## *__Secure-1PSID*
  
  ## *__Secure-1PSIDTS*

Após encontra-los substitua os mesmos no código (linhas 10 e 11).

Lembrando que o valor de *__Secure-1PSID* sempre termina com um ponto (.)
