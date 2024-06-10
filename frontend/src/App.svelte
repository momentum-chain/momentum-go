<script>
  import logo from './assets/images/logo-universal.png'
  import {GetVersion} from '../wailsjs/go/main/App.js'

  let resultText = "Please enter your name below 👇"
  let name


</script>

<main>
  <h1>Momentum</h1>
  {#await GetVersion() then version}
    {version}
  {/await}
</main>

<style>

</style>
