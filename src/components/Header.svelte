<script>

</script>

<style>
  .header-container {
    height: 1100px;
  }

  .hero-image {
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
      url("/img/image1.jpg");
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
  }

  .hero-svg {
    position: absolute;
    left: 0;
    bottom: 0;
    right: 0;
  }

  .hero-text {
    text-align: center;
    position: absolute;
    top: 30%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #ffca18;
    font-family: "Sonsie One";
    font-size: 30px;
  }

  .header-logo {
    float: left;
    height: 100px;
    margin: 10px;
    padding: 5px;
    margin-left: 50px;
  }

  .header-menu {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    padding-right: 50px;
  }

  .header-menu li {
    float: right;
    margin: 10px;
  }

  .header-menu-items {
    display: block;
    text-align: center;
    text-decoration: none;
    color: #ffca18;
    line-height: 50px;
    width: 0px auto;
    padding: 10px;
    font-family: Arial, Helvetica, sans-serif;
  }

  .header-menu-items:hover {
    background-color: #ffca18;
    color: #373232;
  }

  .hero-subtitle {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #363232;
    font-size: 20px;
  }
</style>

<div class="header-container">
  <div class="hero-image">
    <div class="header-bar">
      <img
        class="header-logo"
        src="./img/tierra.svg"
        alt="Courses Market Online" />
      <ul class="header-menu">
        <li>
          <a class="header-menu-items" href="#/Ingresar">Ingresar</a>
        </li>
        <li>
          <a class="header-menu-items" href="#/Registro">Registrarse</a>
        </li>
      </ul>
    </div>
    <div class="hero-text">
      <h1>E-Courses</h1>
      <p class="hero-subtitle">The place where you find whatever you need</p>
    </div>
    <svg class="hero-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#FFCA18" fill-opacity="1" d="M0,32L48,64C96,96,192,160,288,170.7C384,181,480,139,576,101.3C672,64,768,32,864,69.3C960,107,1056,213,1152,218.7C1248,224,1344,128,1392,80L1440,32L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>
  </div>
</div>
