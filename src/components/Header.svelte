<script>

</script>

<style>
  .header-container {
    height: 1200px;
  }
  .hero-image {
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
      url("/img/image1.jpg");
    height: 50%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
  }

  .hero-text {
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #F50057;
  }

  .hero-text button {
    border: none;
    outline: 0;
    display: inline-block;
    padding: 10px 25px;
    color: #F50057;
    background-color: #ddd;
    text-align: center;
    cursor: pointer;
  }

  .hero-text button:hover {
    background-color: #F50057;
    color: white;
  }

  .header-navigation {
    height: 10%;
  }
</style>

<div class="header-container">
  <div class="header-navigation">
    <span class="header-logo">LOGO</span>
    <ul class="header-menu">
      <li>Ingresar</li>
      <li>Registrarse</li>
    </ul>
  </div>
  <div class="hero-image">
    <div class="hero-text">
      <h1>I am John Doe</h1>
      <p>And I'm a Photographer</p>
      <button>Hire me</button>
    </div>
  </div>
</div>
