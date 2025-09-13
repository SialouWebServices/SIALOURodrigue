<style>
.carousel {
  max-width: 600px;
  margin: auto;
  position: relative;
}
.carousel img {
  width: 100%;
  height: 600px;
  object-fit: cover;
  border-radius: 12px;
}
.dot {
  cursor: pointer;
  height: 12px;
  width: 12px;
  margin: 0 4px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.3s;
}
.active-dot {
  background-color: #717171 !important;
}

/* Responsive : sur mobile (moins de 480px), réduire la hauteur */
@media (max-width: 480px) {
  .carousel img {
    height: 480px;
  }
}
</style>

<div class="carousel">
  <!-- Images -->
  <div class="mySlides">
    <img src="img/photoSIALOU.jpg" alt="Image 1">
  </div>
  <div class="mySlides" style="display:none;">
    <img src="img/photo2.jpg" alt="Image 2">
  </div>
  <div class="mySlides" style="display:none;">
    <img src="img/photo3.jpg" alt="Image 3">
  </div>
   <!-- <div class="mySlides" style="display:none;">
    <img src="img/photo4.jpg" alt="Image 2">
  </div>
  <div class="mySlides" style="display:none;">
    <img src="img/photo5.jpg" alt="Image 3">
  </div>
    <div class="mySlides" style="display:none;">
    <img src="img/photo6.jpg" alt="Image 2">
  </div> -->
  <div class="mySlides" style="display:none;">
    <img src="img/photo7.jpg" alt="Image 3">
  </div>

  <!-- Boutons -->
  <a style="cursor:pointer; position:absolute; top:50%; left:0; padding:16px; color:white; font-size:24px; font-weight:bold; background:rgba(0,0,0,0.3);" onclick="plusSlides(-1)">&#10094;</a>
  <a style="cursor:pointer; position:absolute; top:50%; right:0; padding:16px; color:white; font-size:24px; font-weight:bold; background:rgba(0,0,0,0.3);" onclick="plusSlides(1)">&#10095;</a>

  <!-- Indicateurs -->
  <div style="text-align:center; position:absolute; bottom:10px; width:100%;">
    <span class="dot" onclick="currentSlide(0)"></span>
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
  </div>
</div>

<script>
let slideIndex = 0;
let slides = document.getElementsByClassName("mySlides");
let dots = document.getElementsByClassName("dot");

function showSlides(n) {
  for (let i = 0; i < slides.length; i++) slides[i].style.display = "none";
  for (let i = 0; i < dots.length; i++) dots[i].classList.remove("active-dot");
  slides[n].style.display = "block";
  dots[n].classList.add("active-dot");
}

function plusSlides(n) {
  slideIndex += n;
  if (slideIndex >= slides.length) slideIndex = 0;
  if (slideIndex < 0) slideIndex = slides.length - 1;
  showSlides(slideIndex);
}

function currentSlide(n) {
  slideIndex = n;
  showSlides(slideIndex);
}

// Défilement automatique toutes les 3s
setInterval(() => {
  plusSlides(1);
}, 3000);

// Initialisation
showSlides(slideIndex);
</script>



# 👋 Bienvenue sur mon Portfolio

![Profile views](https://komarev.com/ghpvc/?username=SialouWebServices&label=👀+Visiteurs)  
![GitHub followers](https://img.shields.io/github/followers/SialouWebServices?style=social)  
![GitHub stars](https://img.shields.io/github/stars/SialouWebServices?style=social)  

---

## 🌍 Qui suis-je ?  
Je m’appelle **SIALOU Koffi Rodrigue**, passionné par la **transformation numérique** et l’**alphabétisation digitale en Côte d’Ivoire**.  
Je combine mon expertise technique (**DevOps, développement web, automatisation no-code, cybersécurité**) et mon engagement social (**alphabétisation numérique, formation, entrepreneuriat associatif**) pour bâtir des solutions utiles aux organisations et aux communautés.  

📌 **Missions** :  
- Promouvoir l’inclusion numérique à travers la formation et l’accompagnement.  
- Concevoir des applications web et mobiles accessibles.  
- Contribuer au développement de projets associatifs et communautaires.  

---

## 🚀 Mes projets phares
- 🔹 [*Réseau Ivoirien des Alphabétiseurs Numériques (RIAN)*](https://huggingface.co/spaces/swservices/rian)  
- 🔹 *Gestion de stock Excel & App Inventor*  
- 🔹 *Application Web – Programmation des volontaires*  
- 🔹 *Protocole d’observation passive du dark web (Python)*  
- 🔹 *Menu ivoirien exportable en Paprika Recipe Manager*

---

## 🛠️ Compétences techniques
![HTML5](https://img.shields.io/badge/Code-HTML5-orange?logo=html5)  
![CSS3](https://img.shields.io/badge/Code-CSS3-blue?logo=css3)  
![JavaScript](https://img.shields.io/badge/Code-JavaScript-yellow?logo=javascript)  
![Python](https://img.shields.io/badge/Code-Python-blue?logo=python)  
![PHP](https://img.shields.io/badge/Code-PHP-purple?logo=php)  
![WordPress](https://img.shields.io/badge/CMS-WordPress-blue?logo=wordpress)  
![Glide](https://img.shields.io/badge/NoCode-Glide-green)  
![Bubble](https://img.shields.io/badge/NoCode-Bubble-blueviolet)  
![Adalo](https://img.shields.io/badge/NoCode-Adalo-lightblue)  
![Zapier](https://img.shields.io/badge/Automation-Zapier-orange?logo=zapier)  

---

## 🎓 Formations
- 🎓 **CQP AN – Lycée professionnel Industriel de Daloa** (2024)
- 🎓 **DevOps – Contournement.io** (2022)  
- 🎓 **Certificat SSI (Udemy)** – Sécurité systèmes & réseaux (2018)  
- 🎓 **Maintenance informatique & NTIC – Gouesse SARL** (2016)  
- 🎓 **Lycée moderne de Bocanda** (2004)  
- 📚 **Référentiel Alphabétiseur Numérique (CQP, 720h – 2023)**  

---

## 🤝 Engagements & Associations
- 🌐 **Réseau Ivoirien des Alphabétiseurs Numériques (RIAN)**  
- 📊 Projets associatifs pour la formation numérique, l’inclusion sociale et l’autonomisation des communautés  
- 🏛️ Participation à la rénovation et au développement communautaire (Salle du Royaume de Oumé)  

---

## 📊 Statistiques GitHub
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=SialouWebServices&show_icons=true&theme=tokyonight)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SialouWebServices&layout=compact&theme=tokyonight)  

---

## 📫 Me contacter
📧 **Email** : sialousialou@gmail.com | sialous@outlook.fr  
📱 **Téléphone** : +225 07 07 44 38 91 / +225 05 06 62 82 14  
🔗 **Réseaux sociaux** : [Facebook](https://facebook.com/sialousialou) | [Instagram](https://instagram.com/sialous) | [LinkedIn](https://linkedin.com/in/sia-rodrigue)  

---

✨ *“L’alphabétisation numérique n’est pas seulement une compétence, c’est une clé d’autonomie et de développement.”*  
