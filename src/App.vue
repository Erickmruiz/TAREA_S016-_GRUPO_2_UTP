<template>
  <div id="app">
    <header class="header">
      <h1>LA MARINERA PERUANA</h1>
    </header>

    <div class="container">
      <aside class="sidebar">
        <div class="content-container">
          <h2>Sobre la Marinera</h2>
          <p>La marinera es una de las danzas más representativas y emblemáticas del Perú...</p>
        </div>
        <div class="content-container">
          <h2>Características</h2>
          <ul>
            <li>Música y ritmo alegres...</li>
            <li>Coreografía elegante y coqueta...</li>
            <li>Vestimenta tradicional colorida...</li>
          </ul>
        </div>
        <div class="content-container">
          <h2>Variantes Regionales</h2>
          <p>La marinera no es una danza uniforme; a lo largo del país, ha desarrollado diferentes variantes dependiendo de la región. Las principales variantes son:</p>
          <ul>
            <li>Marinera Norteña...</li>
            <li>Marinera Limeña...</li>
            <li>Marinera Serrana...</li>
          </ul>
        </div>
        <div class="content-container">
          <h2>Importancia Cultural</h2>
          <p>La marinera es un importante vehículo de la identidad cultural peruana...</p>
        </div>
      </aside>

      <main class="main-content">
        <section>
          <h2>Galería de Imágenes</h2>
          <div class="grid">
            <div class="grid-item">
              <img src="./assets/imagen/norteña.jpg" alt="Marinera Norteña">
              <h2>MARINERA NORTEÑA</h2>
            </div>
            <div class="grid-item">
              <img src="./assets/imagen/limeña.jpg" alt="Marinera Limeña">
              <h2>MARINERA LIMEÑA</h2>
            </div>
            <div class="grid-item">
              <img src="./assets/imagen/serrana.jpg" alt="Marinera Serrana">
              <h2>MARINERA SERRANA</h2>
            </div>
          </div>
        </section>

        <section>
          <h2>Videos</h2>
          <div class="video-container">
            <video controls>
              <source src="./assets/videos/MARINERA HUARACINA.mp4" type="video/mp4">
              Tu navegador no soporta el elemento de video.
            </video>
          </div>
          <div class="video-container">
            <video controls>
              <source src="./assets/videos/Marinera Limeña y Resbalosa.mp4" type="video/mp4">
              Tu navegador no soporta el elemento de video.
            </video>
          </div>
          <div class="video-container">
            <video controls>
              <source src="./assets/videos/Marinera Norteña Concheperla.mp4" type="video/mp4">
              Tu navegador no soporta el elemento de video.
            </video>
          </div>
        </section>

        <section>
          <h2>Sonidos</h2>
          <div class="audio-container">
            <audio controls>
              <source src="./assets/audios/Marinera Norteña Concheperla.mp3" type="audio/mpeg">
              Tu navegador no soporta el elemento de audio.
            </audio>
          </div>
          <div class="audio-container">
            <audio controls>
              <source src="./assets/audios/Marinera Limeña y Resbalosa.mp3" type="audio/mpeg">
              Tu navegador no soporta el elemento de audio.
            </audio>
          </div>
          <div class="audio-container">
            <audio controls>
              <source src="./assets/audios/Marinera Limeña y Resbalosa.mp3" type="audio/mpeg">
              Tu navegador no soporta el elemento de audio.
            </audio>
          </div>
        </section>
      </main>
    </div>

    <footer>
      <p>&copy; 2024 Información Cultural. Todos los derechos reservados.</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style scoped>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background: linear-gradient(#333, #a2c0e2);
  }

  .header {
    background: linear-gradient(#d35400, #d35400);
    color: #fff;
    text-align: center;
    padding: 10px 0;
  }

  .container {
    display: flex;
    flex-wrap: wrap;
    padding: 20px;
    text-align: justify;
  }

  .sidebar {
    flex: 1;
    min-width: 200px;
    background: linear-gradient(#fad7a0, #E3DAC9);
    padding: 20px;
    margin-right: 20px;
    border-radius: 8px;
  }

  .content-container {
    background: #fff;
    padding: 15px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .main-content {
    flex: 3;
    padding: 20px;
    background: linear-gradient(#fad7a0, #E3DAC9);
    border-radius: 8px;
    text-align: center;
  }

  footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr); 
    gap: 20px; 
  }

  .grid-item {
    background-color: #ddd;
    padding: 10px;
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .grid-item img {
    width: 100%; 
    height: auto; 
    border-radius: 8px;
  }

  .video-container,
  .audio-container {
    margin: 20px 0;
  }

  video {
    width: 80%;
    height: 300px;
    border-radius: 20px;
  }

  audio {
    width: 60%;
    height: 50px;
    border-radius: 8px;
  }
</style>

