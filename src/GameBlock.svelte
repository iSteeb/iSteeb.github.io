<script>
  export let gameNumber;
  export let gameName;
  export let statsURL = '';
  export let videoURL = '';
</script>

<h1>Game {gameNumber} - {gameName}</h1>
{videoURL}
<img src={statsURL} alt="Statistics for Game {gameNumber} - {gameName}" />
<slot />
