<script>

</script>

<style>
  
  .container {
    height: 100%;
    background: #ffca18;
    margin: 0px;
    padding: 0px;
  }
</style>

<!-- Container -->
<div class="container">
  <!-- Header Slot -->
  <slot name="header" />
  <!-- Content Slot -->
  <slot name="body" />
  <!-- Footer Slot -->
  <slot name="footer" />
</div>
