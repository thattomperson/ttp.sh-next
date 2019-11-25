<style>
  .section {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
  }
</style>

<script>
export let title = ''
</script>



<h1>{ title }</h1>
<div class="section">
  <slot></slot>
</div>