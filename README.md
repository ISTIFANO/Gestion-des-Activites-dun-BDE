# Gestion-des-Activites-dun-BDE
<h1 align="center">
  <a href="https://www.linkedin.com/in/aamir-el-amiri-5672ba262/">
    <img src="./img/MCD.png">
  </a>
</h1>


<h1>modèle logique de donnée (MLD)</h1>

<h1 align="center">
  <a href="https://www.linkedin.com/in/aamir-el-amiri-5672ba262/">
    <img src="./img/MLD.png">
  </a>
</h1>

<p>Evenement = (id_evenement INT, nom VARCHAR(50), description VARCHAR(50), membresBde VARCHAR(50), dateEvents DATE, lieu VARCHAR(50), budget DOUBLE);<br>
Sponsors = (id_sponsors INT, ___nom VARCHAR(50), contact INT, Montantsponsorise DOUBLE, Telecontact INT);<br>
Participant = (ID_Participant_ VARCHAR(50), Nom VARCHAR(50), Email VARCHAR(50), Statut VARCHAR(50), Prenom VARCHAR(50));<br>
Role = (id INT, titre VARCHAR(50), description VARCHAR(50));<br>
Membre = (ID_Membre INT, nom VARCHAR(50), prenom VARCHAR(50), email VARCHAR(50), Datedadhesion DATETIME, #id);<br>
organiser = (#ID_Membre, #id_evenement);<br>
sinscrir = (#id_evenement, #ID_Participant_);<br>
Soutien = (#id_evenement, #id_sponsors);<br>
</p>