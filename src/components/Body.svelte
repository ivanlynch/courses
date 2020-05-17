<script>

</script>

<style>
  .contenido-container {
    position: relative;
    height: 100%;
    background-color: #ffca18;
  }
  .contenido-container h1{
      font-family: "Sonsie One";
        font-size: 50px;
        text-align: center;
        padding-bottom: 50px;
  }
  .cuadrado {
    display: block;
    background-color: #373232;
    text-align: center;
    width: 95%;
    height: 80%;
    border: 5px solid #373232;
    border-radius: 10px;
    margin: 0px auto;
    box-shadow: 5px 2px 2px 0.8;
  }

  .cuadrado-header {
    height: 10%;
  }

  .cuadrado-body {
    background: rgb(247, 228, 153);
    margin: 5px;
    text-align: start;
    margin-bottom: 5px;
    margin-top: 65px;
  }

  .cuadrado-body img {
    height: 625px;
    margin-left: 0px;
  }

  .mac-buttons {
    float: left;
  }

  .mac-button {
    height: 40px;
    width: 40px;
    margin: 10px;
    background: #fff;
    float: left;
    border-radius: 50%;
  }

  .mac-button.close {
    background: #fe5b52;
  }
  .mac-button.minimize {
    background: #e7c029;
  }
  .mac-button.maximize {
    background: #52c22c;
  }
</style>

<div class="contenido-container">
  <h1>How it works?</h1>
  <div class="cuadrado">
    <div class="cuadrado-header">
      <div class="mac-buttons">
        <div class="mac-button close" />
        <div class="mac-button minimize" />
        <div class="mac-button maximize" />
      </div>
    </div>
    <div class="cuadrado-body">
      <img src="/img/auth.svg" alt="" />
    </div>
  </div>
</div>
