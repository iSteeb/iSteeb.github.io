<script>
  import Icon from '@iconify/svelte';
  export let icon;
  export let heading;
</script>

<h2>{heading}</h2>
<Icon {icon} />
<slot />
