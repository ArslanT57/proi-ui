<script>
  export let className = null;
</script>

<div class="sd-modal-body {className}">
  <slot />
</div>

<style>
  .sd-modal-body {
    padding: 16px;
    font-size: 18px;
  }
</style>
