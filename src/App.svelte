<script lang="ts">
  import Comic from './lib/Comic.svelte'
  import Bio from './lib/Bio.svelte'
  import Avatar from './lib/Avatar.svelte'
</script>

<main>
  <div class="bio">
    <Avatar />
  </div>
  <div class="bio">
    <Bio />
  </div>
  <div class="card">
    <Comic />
  </div>
</main>