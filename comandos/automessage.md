# Comando Automessage

O comando automessage permite ao utilizador visualizar mais opções sobre as funções atuais de envio de mensagens automáticas.

Para usá-lo você deverá escrever **/automessage** e selecionar um dos seguintes grupos:

O mesmo irá ter 4 grupos:

## Adicionar

Use essa opção para adicionar uma nova mensagem para ser enviada entre um certo intervalo de tempo em um canal específico.

- `Canal`: Identifique um canal para sua mensagem automática ser enviada.
- `Tempo`: Defina um intervalo de tempo como por exemplo 10m para 10 minutos.
- `Mensagem`: Defina a mensagem que deverá ser enviada.

<img
  src="https://i.imgur.com/cr02vwz.png"
  className="mx-auto"
/>

## Remover

Use essa opção para remover um novo canal de notícias ao bot e assim ele para de publicar novas mensagens.

- `Mensagem`: Defina a mensagem que deverá ser removida.

<img
  src="https://i.imgur.com/TIrQOaZ.png"
  className="mx-auto"
/>

## Lista

Esta irá listar todos os canais definidos até ao momento ativos no servidor.

<img
  src="https://i.imgur.com/aJD4oEp.png"
  className="mx-auto"
/>

## [Avançado] - Cronjob

Este comando permite inserir cronjobs, estes poderão fazer agendamentos totalmente personalizados com base em tempo e expressões. É importante analisar o seu Cronjob no [CronTab Guru](https://crontab.guru).

- `Canal`: Identifique um canal para sua mensagem automática ser enviada.
- `Cronjob`: Defina um intervalo de tempo com um cronjob. (É usado o horário America/Sao_Paulo)
- `Mensagem`: Defina a mensagem que deverá ser enviada.

<img
  src="/download.png"
  alt="image.png"
  title="image.png"
  className="mx-auto"
/>