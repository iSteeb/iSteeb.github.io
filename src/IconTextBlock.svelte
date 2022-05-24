<script>
  import Icon from '@iconify/svelte';
  export let icon;
  export let heading;
</script>

<div class="container border-2 border-black">
  <h2>{heading}</h2>
  <Icon {icon} />
  <slot />
</div>

<style>
</style>
