<template>
  <div class="project">
    <h1>Voici les différents projets que j'ai réalisé jusqu'à présent :</h1>
<ul class="cards">
  <li class="cards__item">
    <div class="card">
      <div class="card__image card__image--interface-ri"></div>
      <div class="card__content">
        <div class="card__title">Interface-RI</div>
        <p class="card__text">C'est un projet que j'ai réalisé durant mon stage à la Communauté d'agglomérations du Grand Besançon. J'ai dû modifier un logiciel existant pour y ajouter des fonctions de géo-localisation sur des camions-poubelles ainsi que diverses informations pour faciliter le suivi par la direction.</p>
     <a target="_blank" href="https://github.com/vitalj/interfaceRI"> <button class="fab fa-github"></button></a>
      </div>
    </div>
  </li>
  <li class="cards__item">
    <div class="card">
      <div class="card__image card__image--tech-tracker"></div>
      <div class="card__content">
        <div class="card__title">Tech-Tracker</div>
        <p class="card__text">C'est une application qui permet à l'aide de l'API Github d'afficher qu'elles sont les technologies les plus utilisées par projet dans chaque département français.</p>
     <a target="_blank" href="https://github.com/vitalj/tech-tracker"> <button class="fab fa-github"></button></a>
      </div>
    </div>
  </li>
  <li class="cards__item">
    <div class="card">
      <div class="card__image card__image--wetransfer"></div>
      <div class="card__content">
        <div class="card__title">Wetransfer-Like</div>
        <p class="card__text">Cette application qui permet le partage de fichiers compressés en envoyant un lien par mail aux destinataires.</p>
     <a target="_blank" href="https://github.com/vitalj/wetransfer-like"> <button class="fab fa-github"></button></a>
      </div>
    </div>
  </li>
  <li class="cards__item">
    <div class="card">
      <div class="card__image card__image--explo"></div>
      <div class="card__content">
        <div class="card__title">Explorateur de fichier</div>
        <p class="card__text">Application qui permet d'explorer des fichiers<br>
          Elle est écrit en AJAX ce qui permet d'éviter le rechargement de la page.</p>
     <a target="_blank" href="https://github.com/vitalj/Extracteur-fichier-PHP-AJAX"> <button class="fab fa-github"></button></a>
      </div>
    </div>
  </li>
    <li class="cards__item">
    <div class="card">
      <div class="card__image card__image--pwa"></div>
      <div class="card__content">
        <div class="card__title">Portfolio PWA</div>
        <p class="card__text">C'est une application mobile (PWA) crée au cours de l'année pour montrer les projets créés. <br>
          Elle à été écrite dans le but d'être le plus rapide possible.</p>
     <a target="_blank" href="https://github.com/vitalj/portfolioPWA"> <button class="fab fa-github"></button></a>
      </div>
    </div>
  </li>
    <li class="cards__item">
    <div class="card">
      <div class="card__image card__image--bomberman"></div>
      <div class="card__content">
        <div class="card__title">Bomberman</div>
        <p class="card__text">C'est un jeu copié sur le principe de Bomberman. Ce projet étudiant est écrit en JavaScript et a été créé en trinôme en 3 jours de cours.</p>
     <a target="_blank" href="https://github.com/vitalj/Bomberman-Groupe2"> <button class="fab fa-github"></button></a>
      </div>
    </div>
  </li>
    <li class="cards__item">
    <div class="card">
      <div class="card__image card__image--la-boussole"></div>
      <div class="card__content">
        <div class="card__title">La boussole</div>
        <p class="card__text">C'est un thème Wordpress créé sur mesure de manière bénévole pour une association Bisontine.</p>
     <a target="_blank" href="https://github.com/vitalj/la_boussole_wp"> <button class="fab fa-github"></button></a>
      </div>
    </div>
  </li>
</ul>
  </div> 

 
</template>

<style scoped>

html,
body,
{
  width: 100vw;
}

.project {
  padding-top: 50px;
}

a > button:hover {
  color:  rgb(180, 179, 179);
}

*,
*::before,
*::after {
  box-sizing: border-box;
}

.fab {
  font-size: 1.8rem; 
   color: white;
  background-color: rgba(0, 0, 0, 0);
   border: 1px solid rgba(247, 212, 212, 0);
}
.fab:hover {
  color: black;

}

body {
  font-weight: 400;
  
  letter-spacing: 0;
  padding: 1rem;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -moz-font-feature-settings: "liga" on;
}
img {
  vertical-align: middle;
}
.btn {
  background-color: white;
  border: 1px solid #cccccc;
  color: black;
}


.cards {
  display: flex;
  flex-wrap: wrap;
  list-style: none;
  margin: 0;
  padding: 0;

}
.cards__item {
  display: flex;
  padding: 1rem;
  
}
@media (min-width: 40rem) {
  .cards__item {
    width: 50%;
  }
}
@media (min-width: 56rem) {
  .cards__item {
    width: 33.3333%;
  }
}

.card {
  background-color: rgba(0, 0, 0, 0.45);
  border-radius: 0.25rem;
  box-shadow: 0 20px 40px -14px rgba(0, 0, 0, 0.25);
  display: flex;
  flex-direction: column;
  overflow: hidden;
  border: 1px solid rgb(0, 0, 0);

}
.card:hover .card__image {
  -webkit-filter: contrast(100%);
          filter: contrast(100%);
}
.card__content {
  display: flex;
  flex: 1 1 auto;
  flex-direction: column;
  padding: 1rem;
}
.card__image {
  background-position: center center;
  background-repeat: no-repeat;
  background-size:cover;
  border-top-left-radius: 0.25rem;
  border-top-right-radius: 0.25rem;
  -webkit-filter: contrast(70%);
          filter: contrast(70%);
  overflow: hidden;
  position: relative;
  transition: -webkit-filter 0.5s cubic-bezier(0.43, 0.41, 0.22, 0.91);
  transition: filter 0.5s cubic-bezier(0.43, 0.41, 0.22, 0.91);
  transition: filter 0.5s cubic-bezier(0.43, 0.41, 0.22, 0.91), -webkit-filter 0.5s cubic-bezier(0.43, 0.41, 0.22, 0.91);
}
.card__image::before {
  content: "";
  display: block;
  padding-top: 56.25%;
}
body > div > div.project > ul > li:nth-child(5) > div > div.card__image.card__image--pwa {
    background-size:contain;
}

.card__image--interface-ri {
   background-image: url("../assets/sc/interface-ri.jpg");
}
.card__image--tech-tracker {
   background-image: url("../assets/sc/tech-tracker.jpg");
}
.card__image--explo {
   background-image: url("../assets/sc/explorateur.jpg");
}
.card__image--wetransfer {
   background-image: url("../assets/sc/we-transfer.jpg");
}
.card__image--bomberman {
   background-image: url("../assets/sc/bomberman.jpg");
}
.card__image--la-boussole {
   background-image: url("../assets/sc/la-boussole.jpg");
}
.card__image--pwa {
   background-image: url("../assets/sc/pwa.jpg");
}

.card__title {
  color: black;
  font-size: 1.25rem;
  font-weight: 300;
  letter-spacing: 2px;
  text-transform: uppercase;

}
.card__text {
  flex: 1 1 auto;
  font-size: 0.9rem;
  line-height: 1.5;
  margin-bottom: 1.25rem;
    Font-Family: 'Roboto Slab', Serif;

}


</style>
