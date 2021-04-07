---
id: commands
title: Commands
---

:::info Note
### Always remember the following!
- The default prefix of Rythm is `!`. If you have changed your prefix to something else, please use your prefix instead of `!`. If you forget your prefix, mention Rythm (`@Rythm#3722`).
- **Never include `<>` in your messages when using a command!**
- Time can be in different formats
   + Example: `100`, `1:50`, `2m30s`
:::

## Song
---
<!-- Song-related commands -->
- **`!join`** - Summons the bot to the voice channel you are in.
    - **Aliases:** `summon`
---
- **`!play`** - Plays a song with the given name or url. [More Info](/play_song)
    - **Usage:** `!play <link/query>`
    - **Alias:** `p`
---
- **`!playtop`** - Adds a song with the given name/url __on the top of the queue__.
    - **Usage:** `!playtop <link/query>`
    - **Aliases:** `pt`, `ptop`
---
- **`!playskip`** - Skips the current song and plays the song you requested.
    - **Usage:** `!playskip <link/query>`
    - **Aliases:** `ps`, `pskip`, `playnow`, `pn`
---
- **` uma música através de sua consulta e retorna o top 10 resultados.
    - **Usage:** `!search <nome da música>`
    - **Alias:** `find`
---
- **`!soundcloud`** - Toca uma música de [SoundCloud](https://www.soundcloud.com)  com o nome/url 
    - **Usage:** `!soundcloud <link/música>`
    - **Alias:** `sc`
---
- **`!nowplaying`** - Mostra que música Rythm está tocando atualmente.
    - **Alias:** `np`
---
- **`!grab`** - Salva a música atual de reprodução para suas Mensagens Diretas.
    - **Aliases:** `save`, `yoink`
---
- **`!seek`** - Busca até um certo ponto na faixa atual.
    - **Usage:** `!seek <tempo>`
---
- **`!rewind`** - Rebobina por um certo período de tempo na faixa atual.
    - **Usage:** `!rewind <tempo>`
    - **Alias:** `rwd`
---
- **`!forward`** - Atacantes por um certo período de tempo na pista atual.
    - **Usage:** `!forward <Hora>`
    - **Alias:** `fwd`
---
- **`!replay`** - Redefine o progresso da música atual.
---
- **`!loop`** - Alterna looping para a música de reprodução atual.
    - **Alias:** `repeat`
---
- **`!voteskip`** - Vota para pular a música atual. **[Mais informações](/voteskip#quantos votos-são-necessário-para-uma-canção-a-ser-voto-pulou)**
    - **Alias:** `skip`, `next`, `s`
---
- **`!forceskip`** - Ignora a música atual tocando imediatamente.
    - **Outros usos:** `!forceskip <número>` - Pule uma certa quantidade de músicas.
    - **Aliases:** `fs`, `fskip`
    - **nota:** `DJ` role/`Gerenciar canais` permissão necessária.
---
- **`!pause`** - Pausa a faixa de reprodução atual.
    - **Alias:** `stop`
---
- **`!resume`** - Retoma música pausada.
    - **Aliases:** `re`, `res`, `continue`
---
- **`!lyrics`** - Recebe a letra da música atual.
    - **Outros Usos:** `!lyrics <nome da canção>` - Recebe a letra da canção mencionada.
    - **Aliases:** `l`, `ly`
---
- **`!disconnect`** - Desconecta o bot do canal de voz em que está.
    - **Aliases:** `dc`, `leave`, `dis`
---

## Queue
---
- **`!queue`** - Mostra a primeira página da fila.
    - **Outros usos:** `!queue <página>`: Mostra o número da página especificado.
    - **Alias:** `q`
---
- **`!loopqueue`** - Alternação looping para toda a fila.
    - **Aliases:** `qloop`, `lq`, `queueloop`
---
- **`!move`** - Move uma determinada música para uma posição escolhida na fila.
    - **uso:** `!move <posição antiga > <nova posição>`
    - **Aliases:** `m`, `mv`
    - **nota:** Se a `<nova posição>` não está especificado, a música será movida para a primeira posição da fila
---
- **`!skipto`** - Pula para uma certa posição na fila.
    - **uso:** `!skipto <posição>`
    - **Alias:** `st`
---
- **`!shuffle`** -  Embaralha toda a fila.
    - **Alias:** `random`
---
- **`!remove`** - Remove uma determinada entrada da fila.
    - **uso:** `!remove <Números>`
    - **Alias:** `rm`
---
- **`!clear`** - Limpa toda a fila.
    - **Outros Usos:** `!clear <@Usuario>` - Limpa todas as músicas solicitadas pelo usuário mencionado.
    - **Alias:** `cl`
---
- **`!leavecleanup`** - Remove as músicas do usuário ausente da fila.
    - **Alias:** `lc`
---
- **`!removedupes`** - Remove músicas duplicadas da fila.
    - **Aliases:** `rmd`, `rd`, `drm`
---

## koodos
---
- **`!sotd`** - Mostra a música do dia. [More Info](/koodos#song-of-the-day)
---
- **`!playsotd`** - Fila a música do dia.
    - **Alias:** `psotd`
---
- **`!sotw`** - Shows the songs of the week. [More Info](/koodos#song-of-the-week)
---
- **`!playsotw`** - Queue the songs of the week.
    - **Alias:** `psotw`
---
- **`!sotm`** - Mostra as músicas do mês. [More Info](/koodos#song-of-the-month)
---
- **`!playsotm`** - Enfileirar as músicas do mês.
    - **Alias:** `psotm`
---

## Configurações
---
- **`!settings`** - Use o formato de comando `!settings <option>` para ver mais informações sobre uma opção. [More Info](/settings)
    - **Alias:** `setting`
    - **Lista de opções:**
      - [**`prefix`**](/settings#prefix) - Altera o prefixo de Rythm.
      - [**`announcesongs`**](/settings#announce-songs) - Permite que o bot anuncie cada música nova tocando.
      - [**`preventduplicates`**](/settings#duplicate-song-prevention) - Impede que os usuários adicionem músicas na fila que já estão na fila.
      - [**`blacklist`**](/settings#blacklist)- Permite que você coloque na lista negra de canais que você **não** quer que Rythm responda.
      - [**`maxqueuelength`**](/settings#max-queue-length) - Limita quantas músicas a fila pode armazenar.
      - [**`maxusersongs`**](/settings#max-user-songs) - Limita quantas músicas o usuário pode fazer fila ao mesmo tempo.
      - [**`djonly`**](/settings#dj-only-mode) - Define o servidor para executar apenas em DJ.
      - [**`djrole`**](/settings#dj-role) - Mudanças qual papel é considerado DJ. Papéis chamados 'DJ' ainda funcionarão.
      - [**`djplaylists`**](/settings#dj-only-playlists) - Permite apenas DJs para listas de reprodução em fila.
      - [**`reset`**](/settings#reset) - Redefine todas as configurações do Rythm.
    - **[Somente Premium](https://rythm.fm/premium):**
      - [**`defaultvolume`**](/settings#default-volume) - Define o volume padrão em que o bot sempre começará.
      - [**`autoplay`**](/settings#autoplay) - Alterna músicas de reprodução automática da lista de reprodução quando não há mais reprodução. 
      - [**`alwaysplaying `**](/settings#always-playing) - Define Rythm para ficar em seu canal de voz 24/7. 
      


---

## [Premium](https://rythm.fm/premium)
---
- **`!effects`** - Mostra os efeitos de áudio atuais.  [**Somente doador**](https://rythm.fm/premium?do)
    - **Outros Usos**:
        - `!effects help` - Mostra todos os efeitos de áudio disponíveis.
        - `!effects clear` - Limpa todos os efeitos de áudio.
    - **Alias:** `effect`
---
- **`!speed`** - Mostra informações sobre o efeito de velocidade atual.  [**Somente doador**](https://rythm.fm/premium?do)
    - **Outros Usos**: `!speed <0.1 - 3>` - Modifica a velocidade de reprodução.
---
- **`!bass`** - Mostra informações sobre o efeito atual de aumento de graves.  [**Somente doador**](https://rythm.fm/premium?do)
    - **Outros Usos**: `!bass <1 - 5>` - adicionar grave a música atual.
---
- **`!nightcore`** - Alterna o efeito nightcore.  [**Somente doador**](https://rythm.fm/premium?do)
---
- **`!slowed`** - Alterna o efeito lento.  [**Somente doador**](https://rythm.fm/premium?do)
---
- **`!volume`** - Saídas do volume atual.   [**Somente doador**](https://rythm.fm/premium?do)
    - **Outros Usos:** `!volume <1-200>` - Altera o volume atual.
    - **Alias:** `vol`
---

## Outros
---
- **`!prune`** - Exclui as mensagens e comandos do bot.
    - **Aliases:** `purge`, `clean`
---
- **`!invite`** - apresenta Rythm's links oficiais!
    - **Alias:** `links`
---
- **`!info`** - Mostra informações sobre Rythm!
---
- **`!shard`** - Verifica o fragmento do servidor em que seu servidor está.
    - **Alias:** `debug`
---
- **`!ping`** - Verifica o tempo de resposta do bot para o Discord.
---
- **`!aliases`** - Lista todos os codinomes de comando.
---
