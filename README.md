# Como enviar o seu código do VS Code <img src="https://github.com/user-attachments/assets/e157c6fd-9b25-4d48-9d4b-d05c3eb50bf7" width="25"> diretamente para o seu repositório no GitHub <img src="https://github.com/user-attachments/assets/0d41e10e-198f-4a4a-a00e-edc415bd669a" width="30">

## 1 - No seu GitHub, crie um repositório sem README.md

## 2 - Copie a URL do seu repositório, exemplo:
```
https://github.com/seu-usuario/seu-repositorio.git
```
## 3 - Vá até o VS Code e crie um novo terminal

## 4 - No terminal, digite:
```
git remote add origin https://github.com/seu-usuario/seu-repositorio.git
```
#### Lembre-se de colar a URL do seu repositório

## 5 - Em seguida digite:
```
git add .
```

## 6 - Crie um commit digitando:
```
git commit -m "Mensagem do commit"
```
#### Personalize a mensagem do commit como quiser!

## 7 - Envie o código para o GitHub digitando:
```
git push -u origin main
```
## Prontinho! Agora é só recarregar a página do seu repositório que já estará com o código do VS Code lá.
## Se você quiser, pode criar um README.md para dar um título ao seu projeto e fazê-lo aparecer quando as pessoas clicam no seu repositório.
