<script>
  import {base} from '$app/paths';
</script>

<section id="header">
  <a href="{base}/">HOME</a>
  <a href="{base}/sound">sound()</a>
  <!-- <a href="{base}/note">note()</a> -->
  <!-- <a href="{base}/stack">stack()</a> -->
  <!-- <a href="{base}/samples">samples()</a> -->
  <!-- <a href="{base}/ping_pong">ping pong</a> -->
</section>

<style>
#header {
  display: flex;
  gap: 1em;
  font-size: 1.5em;
  margin: 1.8em 0 2em;
  border-bottom: solid;
}

#header a {
  height: 1.8em;
}
</style>
