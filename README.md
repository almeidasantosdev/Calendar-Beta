# Calendar Beta

Versão em Node.js do bot de agendamento do Calendar Plus. O cliente manda mensagem no WhatsApp, o bot confere se o horário está livre no Google Calendar, respeita o expediente e grava ou cancela o compromisso. As conversas e os dados da empresa ficam no Firebase.

O pacote se chama `calendario-bot-firebase`. O QR Code do WhatsApp aparece no terminal. O passo a passo de Firebase, OAuth do Google e variáveis de ambiente está em `Instalação.txt`.

## Como rodar

```bash
npm install
npm run auth
npm start
```

`npm run auth` sobe o servidor OAuth. `npm start` liga o bot (`src/bot.js`).
