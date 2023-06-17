<!doctype html>
<html>
 <head>
  <style>
    body {
  background-color: blueviolet;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  padding: 5px;
}
.titre{
  color: yellow;
  text-align: center;
  font-size: 40px;
}
.principal {
  color: white;
  text-align: center;
  font-size: 40px;
  font-weight: bold;
} 
section, aside {
            background: linear-gradient(to left, rgb(187, 156, 238), rgb(230, 130, 270));
            color: #fff;
            margin: 1.858736059%;
            padding: 20px 0;
            text-align: center;
            border: 1.5mm ridge purple;
         }
         section {
            float: center;
            width: 87%;
            border-radius: 30px;
            margin: auto;
         }
a{
  color: antiquewhite;
  text-decoration: none;
  font-size: 40%;
}
.bonjour{
            background: linear-gradient(to left, rgb(167, 118, 245), rgb(230, 130, 270));
            margin: auto;
            padding: 20px 0;
            text-align: center;
            width: 87%;
            border-radius: 30px;
            float: center;
            color: antiquewhite;
}
.context{
  margin: auto;
  width: 70%;
  text-align: center;
  color: antiquewhite;
  font-size: 10px;
}
@media screen and (max-width: 700px){
  .principal {
    display: none;
  }
}
@media screen and (min-width: 700px){
  .hamburger-menu{
    display: none;
  }
}
#menu__toggle {
  opacity: 0;
}
#menu__toggle:checked + .menu__btn > span {
  transform: rotate(45deg);
}
#menu__toggle:checked + .menu__btn > span::before {
  top: 0;
  transform: rotate(0deg);
}
#menu__toggle:checked + .menu__btn > span::after {
  top: 0;
  transform: rotate(90deg);
}
#menu__toggle:checked ~ .menu__box {
  left: 0 !important;
}
.menu__btn {
  position: fixed;
  top: 20px;
  left: 20px;
  width: 26px;
  height: 26px;
  cursor: pointer;
  z-index: 1;
}
.menu__btn > span,
.menu__btn > span::before,
.menu__btn > span::after {
  display: block;
  position: absolute;
  width: 100%;
  height: 2px;
  background-color: #fff;
  transition-duration: .4s;
}
.menu__btn > span::before {
  content: '';
  top: -8px;
}
.menu__btn > span::after {
  content: '';
  top: 8px;
}
.menu__box {
  display: block;
  position: fixed;
  top: 0;
  left: -100%;
  width: 300px;
  height: 100%;
  margin: 0;
  padding: 120px 0;
  list-style: none;
  background-color: rgb(145, 112, 228);
  box-shadow: 2px 2px 6px rgba(0, 0, 0, .4);
  transition-duration: .25s;
}
.menu__item {
  display: block;
  padding: 12px 24px;
  color: #fff;
  font-family: 'Roboto', sans-serif;
  font-size: 20px;
  font-weight: 600;
  text-decoration: none;
  transition-duration: .25s;
}
.menu__item:hover {
  background-color: rgb(212, 167, 255);
}
.merde{
  font-size: 16px;
  text-align: left;
  padding-left: 15%;
  padding-right: 15%;
}
.explication{
  text-align: left;
  padding-left: 15%;
  padding-right: 15%;
}
.2 {
  text-align: center;
  padding-left: 15%;
  padding-right: 15%;
  font-size: 13px;
  margin: auto;
}
@media screen and (max-width: 700px){
  .bonjour{
    margin-left: 10%;
    margin-right: 10%;
    margin: auto;
  }
}@media screen and (min-width: 700px){
  .bonjour{
    margin-left: 10%;
    margin-right: 10%;
    margin: auto;
  }
}
.mac {
  font-size: 16px;
  text-aling: left;
  padding-left: 15%;
  padding-right: 15%;
  font-weight: 500;
}
.darius {
  text-align:left;
  
}
.mac-os{
  font-size: 16px;
  text-aling: left;
  padding-left: 15%;
  padding-right: 15%;
  font-weight: 500;
}
.darius {
  text-align: center;
}
.ent {
  font-size: 16px;
  font-weight: 500;
  color: purple;
}
.mac-os{
    text-align: left;
  padding-left: 15%;
  padding-right: 15%;
}

@media screen and (max-width: 700px){
  .lignes {
    display: none;
  }
}
@media screen and (min-width: 700px){
  .hamburger-menu{
    display: none;
  }
}

   </style>
  <title>Les systèmes d'explatoitation
  </title>
  <link rel="stylesheet" href="style.css">
 </head>
 <body>
  <center>
   <br>
   <a
    href="https://youtube.com/shorts/SXHMnicI6Pg?feature=share"><img
     src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5f/Happy_Mac.svg/1200px-Happy_Mac.svg.png"
     width="100px"></a>
  </center>
  <br>
  <section>
   <h1 class="titre">
    Systèmes d'exploitation
   </h1>
   <p class="principal">
    <a href="/mac.html">Mac OS</a>&nbsp
    <a href="/windows.html">Windows</a> &nbsp
    <a href="/ios.html">Iphone OS</a>&nbsp
    <a href="/android.html">Android</a> &nbsp
    <a href="/linux.html">Linux</a>&nbsp
    <a href="/temple.html">Temple OS</a>&nbsp
    <a href="bonus.html">Bonus</a>
    
    
   <p>
   <div class="hamburger-menu">
    <input id="menu__toggle"
     type="checkbox" />
    <label class="menu__btn"
     for="menu__toggle">
     <span></span>
    </label>
    
    <ul class="menu__box">
     <li><a class="menu__item"
       href="/mac.html">Mac OS</a></li>
     <li><a class="menu__item"
       href="/windows.html">Windows</a></li>
     <li><a class="menu__item"
       href="/ios.html">Iphone os</a></li>
     <li><a class="menu__item"
       href="/android.html">Android</a></li>
     <li><a class="menu__item"
       href="/temple.html">Temple os</a></li>
     <li><a class="menu__item"
       href="/linux.html">Linux</a></li>
     <li><a class="menu__item"
       href="/bonus.html">Bonus</a></li>
     <br>
     <li>
      <FORM>
       <INPUT type="button"
        value="Nombre de lignes de code"
        onclick="afficher()">
      </FORM>
     </li>
     <br>
     
    </ul>
   </div>
  </section>
  <br>
  <section class="bonjour">
   
   <p class="merde">
    Un système d'exploitation (operating
    system) est un logiciel essentiel qui
    gère les ressources matérielles et
    logicielles d'un ordinateur et permet aux
    utilisateurs d'interagir avec
    l'ordinateur. Voici quelques-unes des
    principales fonctions d'un système
    d'exploitation :
    <br>
   <div class="explication">
    <details>
     <summary><strong> Gestion des ressources
      </strong></summary>
     <p>
      Le système d'exploitation contrôle et
      alloue les ressources matérielles
      telles que le processeur, la mémoire,
      le disque dur, les périphériques
      d'entrée/sortie, etc. Il s'assure que
      chaque programme en cours d'exécution
      obtient les ressources dont il a besoin
      et les utilise de manière efficace.
     </p>
    </details>
    </p>
    
    <details>
     <summary><strong> Interface utilisateur
      </strong></summary>
     <p>
      Le système d'exploitation fournit une
      interface pour permettre aux
      utilisateurs d'interagir avec
      l'ordinateur. Cela peut inclure des
      interfaces graphiques conviviales, des
      lignes de commande ou une combinaison
      des deux.
     </p>
    </details>
    <br>
    <details>
     <summary><strong> Gestion des fichiers
      </strong></summary>
     <p>
      Le système d'exploitation gère les
      fichiers sur le disque dur ou tout
      autre support de stockage. Il permet de
      créer, de modifier, de supprimer,
      de rechercher et d'organiser les
      fichiers et les répertoires.
     </p>
    </details>
    <br>
    <details>
     <summary><strong> Gestion des
       processus</strong></summary>
     <p>
      Le système d'exploitation permet
      l'exécution simultanée de plusieurs
      programmes ou processus. Il attribue
      des ressources aux processus, les
      planifie et les supervise pour assurer
      un fonctionnement harmonieux du
      système.
     </p>
    </details>
    <br>
    <details>
     <summary><strong> Gestion de la
       mémoire</strong></summary>
     <p>
      Le système d'exploitation alloue et
      gère la mémoire disponible
      aux programmes en cours d'exécution. Il
      s'assure que chaque programme
      a suffisamment d'espace mémoire pour
      fonctionner correctement et évite
      les conflits entre les programmes.
     </p>
    </details>
    <br>
    <details>
     <summary><strong> Gestion des
       périphériques</strong></summary>
     <p>
      Le système d'exploitation facilite la
      communication avec les périphériques
      matériels tels que les imprimantes, les
      claviers, les souris, les moniteurs,
      etc.
      Il fournit des pilotes logiciels pour
      permettre aux périphériques de
      fonctionner
      avec l'ordinateur.
     </p>
    </details>
    <br>
    <details>
     <summary><strong> Sécurité</strong>
     </summary>
     <p>
      Le système d'exploitation met en place
      des mécanismes de sécurité pour
      protéger les données et les ressources
      du système.
      Il gère les autorisations d'accès aux
      fichiers, les pare-feu, les antivirus
      et d'autres mesures de sécurité.
     </p>
    </details>
    <div class="kevin">
     <p class="2">
      En résumé, un système d'exploitation
      joue un rôle crucial en fournissant une
      plateforme stable, conviviale et
      efficace pour l'exécution des logiciels
      et
      l'interaction avec l'ordinateur. Il
      agit en tant qu'intermédiaire entre les
      utilisateurs, les applications et le
      matériel, permettant ainsi la
      réalisation
      de diverses tâches et opérations.
     </p>
     <div>
  </section>
  ​</div>
  </section>
  <br>
  <p class="context">
   <a
    href="https://qb8ffm.mimo.run/index.html"><button>Deutsch</button></a>
   <center>
    
    <br>
    <FORM>
     <INPUT class="lignes" type="button"
      value="Nombre de lignes de code"
      onclick="afficher()">
    </FORM>
   </center>
   
   <br>
  <p class="context">
   Copyright © 2023 Les cramptés Inc. All
   rights reserved
  </p>
  <br>
  </center>
  <br><br><br>
  <br>
  <br>
  </p>
  <script LANGUAGE="JavaScript">
   document.write("")
   
   function afficher()
   {
   alert("3550 lignes de code !")
   }
   
  </script>
 </body>
</html>







<FORM>
 <INPUT type="button" value="Cliquez ici"
  onclick="afficher()">
</FORM>
