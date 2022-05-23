<script>
  import IconTextBlock from './IconTextBlock.svelte';
  import TextBlock from './TextBlock.svelte';
  import GameBlock from './GameBlock.svelte';
</script>

xw<menu> insert menu here </menu>

<highlights> insert highlights component here </highlights>

<IconTextBlock icon="mdi:person" heading="Attributes">
  <p>DOB: 19 Oct '96</p>
  <p>Height: 191cm</p>
  <p>Weight: 85kg</p>
</IconTextBlock>

<IconTextBlock icon="mdi:handball" heading="Reach">
  <p>Spike Touch: 350cm</p>
  <p>Block Touch: 340cm</p>
  <p>Standing Reach: 254cm</p>
</IconTextBlock>

<IconTextBlock icon="mdi:human-male-height" heading="Player">
  <p>Position: Opposite</p>
  <p>Hand: Right</p>
  <p>Serve: Jump Server</p>
</IconTextBlock>

<IconTextBlock icon="mdi:dumbbell" heading="Lifts">
  <p>Squat: 145kg</p>
  <p>Deadlift: 175kg</p>
  <p>Clean: 120kg</p>
</IconTextBlock>

<TextBlock heading="Experience">
  <p>2021: NSW Senior Phoenix Squad Member</p>
  <p>
    2017 – 2019: Athlete at the Australian Institute of Sport Centre of
    Excellence (AIS CoE)
  </p>
  <p>2017: Asian Men’s Club Volleyball Championship (Canberra Heat)</p>
  <p>
    2015 – 2019: Australian Volleyball League (1x Gold, 1x Silver, 1x Bronze w/
    Heat and AIS CoE)
  </p>
</TextBlock>

<TextBlock heading="Achievements">
  <p>
    Team Accomplishments: Team leader in all stats (most points scored in
    attack, highest attack%, most service aces, and most blocks).
  </p>
  <p>League Accomplishments:</p>
  <ul>
    <li>Best attacker (24 points) of the round.</li>
    <li>Best blocker (9 blocks) of the round.</li>
    <li>Best server (5 aces) of the round.</li>
    <li>
      2nd best points-scorer twice, with 26 and 28 points. o 2nd best attacker
      (25 points) of another round.
    </li>
  </ul>
</TextBlock>

<GameBlock
  gameNumber={1}
  gameName="SAY v SRO"
  videoURL="s3ragTy8o_s"
  statsURL="/stats1.png">
  heres a game descripton
</GameBlock>
<GameBlock
  gameNumber={2}
  gameName="SAY v BAR"
  videoURL="s3ragTy8o_s"
  statsURL="/stats1.png">
  another description of a game
</GameBlock>

<gallery> insert gallery component here </gallery>

<IconTextBlock icon="mdi:email" heading="Email">
  <p>steven@duz.ie</p>
</IconTextBlock>

<IconTextBlock icon="mdi:phone" heading="Phone">
  <p>+61 411 417 997</p>
</IconTextBlock>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }
</style>
