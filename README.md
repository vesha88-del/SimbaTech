# SimbaTech
<!DOCTYPE html>
<html lang="sr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Simulacija procesa | FlexSim rešenja</title>
  <style>
    .gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 15px;
  padding: 1rem;
}
.gallery-grid img {
  width: 100%;
  cursor: pointer;
  border-radius: 8px;
  transition: transform 0.3s ease;
}
.gallery-grid img:hover {
  transform: scale(1.05);
}
#lightbox {
  display: none;
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0,0,0,0.8);
  justify-content: center;
  align-items: center;
  z-index: 999;
}
#lightbox img {
  max-width: 90%;
  max-height: 80%;
  border-radius: 10px;
}
    <script>
function openLightbox(src) {
  document.getElementById("lightbox-img").src = src;
  document.getElementById("lightbox").style.display = "flex";
}
function closeLightbox() {
  document.getElementById("lightbox").style.display = "none";
}
</script>
<body>
  <section id="gallery">
  <h2>Galerija simulacija</h2>
  <div class="gallery-grid">
    <img src="https://www.flexsim.com/wp-content/uploads/sites/2/2018/06/factory-simulation-manufacturing-line.jpg" alt="Simulacija proizvodne linije" onclick="openLightbox(this.src)" />
    <img src="https://www.flexsim.com/wp-content/uploads/sites/2/2018/06/manufacturing-simulation-steel-production.jpg" alt="Simulacija čelične proizvodnje" onclick="openLightbox(this.src)" />
    <img src="https://www.flexsim.com/wp-content/uploads/sites/2/2018/06/flexsim-healthcare-simulation.jpg" alt="Simulacija u zdravstvu" onclick="openLightbox(this.src)" />
  </div>
</section>

<!-- Lightbox prikaz -->
<div id="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img" src="" alt="Uvećana slika" />
</div>
<section id="gallery">
  <h2>Galerija simulacija</h2>
  <p>Pogledajte primere FlexSim modela koje koristimo za optimizaciju procesa:</p>
  <img src="https://www.flexsim.com/wp-content/uploads/sites/2/2018/06/factory-simulation-manufacturing-line.jpg" alt="Simulacija proizvodne linije" width="100%" />
  <br><br>
  <img src="https://www.flexsim.com/wp-content/uploads/sites/2/2018/06/manufacturing-simulation-steel-production.jpg" alt="Simulacija čelične proizvodnje" width="100%" />
<header>
  <h1>Simuliraj. Optimizuj. Napreduj.</h1>
  <p>Digitalna transformacija vaših proizvodnih i logističkih procesa kroz FlexSim simulaciju.</p>
  <nav>
    <a href="#about">O nama</a>
    <a href="#services">Usluge</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Kontakt</a>
  </nav>
</header>

<section id="about">
  <h2>O nama</h2>
  <p>Mi smo tim inženjera i analitičara specijalizovanih za razvoj simulacionih modela u FlexSim-u. Naša misija je da pomognemo kompanijama da optimizuju svoje procese, smanje troškove i donesu bolje odluke — sve to kroz moć vizuelne simulacije.</p>
</section>

<section id="services">
  <h2>Usluge</h2>
  <ul>
    <li>Izrada FlexSim modela za proizvodne linije i skladišta</li>
    <li>Analiza toka materijala i resursa</li>
    <li>Obuka i edukacija za korišćenje FlexSim-a</li>
    <li>Konsultacije za optimizaciju procesa</li>
  </ul>

<section id="videos">
  <h2>Video demonstracije</h2>

  <h3>Uvod u FlexSim</h3>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/ZN--eKDcGMQ" title="Introduction to FlexSim" frameborder="0" allowfullscreen></iframe>

  <h3>Prvi model u FlexSim-u</h3>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/YJgJzyDHZ8o" title="FlexSim 2023 | Build Your First Simulation Model" frameborder="0" allowfullscreen></iframe>

  <h3>Logističke petlje u FlexSim-u</h3>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/RmnB_5ua5ME" title="FlexSim live tutorials #8 Logistic loops in FlexSim." frameborder="0" allowfullscreen></iframe>
</section>
<section id="portfolio">
  <h2>Portfolio</h2>
  <h3>Optimizacija montažne linije</h3>
  <p>Klijent: Auto industrija<br>Rezultat: 18% smanjenje vremena ciklusa</p>

  <h3>Logistika skladišta</h3>
  <p>Klijent: Maloprodajni lanac<br>Rezultat: 25% povećanje efikasnosti rukovanja robom</p>
</section>

<section id="contact">
  <h2>Kontakt</h2>
  <p>Imate ideju, problem ili želite da unapredite svoje procese? Pišite nam — prvi korak ka optimizaciji je simulacija.</p>
  <form>
    <label>Ime:<br><input type="text" name="name" required></label><br><br>
    <label>Email:<br><input type="email" name="email" required></label><br><br>
    <label>Poruka:<br><textarea name="message" rows="5" required></textarea></label><br><br>
    <button type="submit">Pošalji</button>
  </form>
</section>

<footer>
  <p>&copy; 2025 FlexSim Solutions | Sva prava zadržana</p>
</footer>

</body>
</html>
