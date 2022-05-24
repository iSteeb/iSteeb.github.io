<script>
  import { Player, Youtube, DefaultUi } from '@vime/svelte';

  export let gameNumber;
  export let gameName;
  export let statsURL;
  export let videoId;
</script>

<svelte:head>
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/default.css" />
</svelte:head>

<h1>Game {gameNumber} - {gameName}</h1>
<Player theme="dark" style="--vm-player-theme: #e86c8b;">
  <Youtube {videoId} />
  <DefaultUi />
</Player>
<img src={statsURL} alt="Statistics for Game {gameNumber} - {gameName}" />
<slot />
