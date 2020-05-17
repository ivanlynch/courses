<script>

</script>

<style>
  
  .container {
    height: 1500px;
    color: black;
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
