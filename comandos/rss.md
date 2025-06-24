# Comando RSS

O comando **/rss** é fácil de usar, e apenas serve para canais de notícias onde o foco é publicar automaticamente os anúncios. Basta definir um canal de notícias e o The Reaper trata do resto.

## Criar

Use essa opção para adicionar um novo canal de notícias ao bot e assim ele começará a publicar novas mensagens.

- `URL`: Identifique uma URL de um Feed RSS válido.
- `Canal`: Identifique um canal para os itens do feed RSS serem enviados.

<img
  src="https://i.imgur.com/ekie3Wg.png"
  className="mx-auto"
/>

## Editar

Use essa opção para remover um novo canal de notícias ao bot e assim ele para de publicar novas mensagens.

- `Feed`: Identifique um dos feeds listados para ser editado.

<img
  src="https://i.imgur.com/WiPJDUM.png"
  className="mx-auto"
/>

## Apagar

Esta irá listar todos os canais definidos até ao momento ativos no servidor.

- `Feed`: Identifique um dos feeds listados para ser removido.

<img
  src="https://i.imgur.com/877U3jR.png"
  className="mx-auto"
/>

## Filtrar

Este comando foca que o RSS Feed será filtrado com base em algumas palavras-chave.

- `Feed`: Identifique um dos feeds listados.
- `Mensagem`: O que deve ser filtrado?

### Exemplo

"% OFF"

✅ Notebook Acer, teclado Logitech, SSD Kingston e mais com até 65% OFF na Liquida Tech do KaBuM\!

❎ Aquecimento global: mudanças climáticas podem ultrapassar limite de 1,5 °C em três anos

<img
  src="/images/rssFilter.png"
  alt="Rss Filter Pn"
  title="Rss Filter Pn"
  className="mx-auto"
/>

## Remover Filtro

Este comando retirará um dos filtros.

- `Feed`: Identifique um dos feeds listados para ser removido.
- `Mensagem`: Selecione uma das mensagem para ser removido.

![Remove Filter Pn](/images/removeFilter.png)