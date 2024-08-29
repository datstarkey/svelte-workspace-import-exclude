<script lang="ts">
  type Props = {
    text: string;
  };

  let {text}: Props = $props();
</script>


<div>{text}</div>