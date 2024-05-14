<div align="center">
    <article style="display: flex; flex-direction: column; align-items: center; justify-content: center;">
        <p align="center"><img width="400" src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/upgit_20240513_1715611797.png"/></p>
        <h1 style="width: 100%; text-align: center;">GeRoNiMo</h1>
    </article>
</div>





[![Python 3.12](https://img.shields.io/badge/python-3.12-yellow.svg)](https://www.python.org/downloads/release/python-380/) [![QGIS 3.34.0](https://img.shields.io/badge/qgis-3.34.0-green.svg)](https://www.qgis.org/) ![release](https://img.shields.io/badge/postgresql-16-blue.svg)![release](https://img.shields.io/badge/release-v0.1-red.svg)



**[GeRoNiMo](src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/Diapo__Projet%20dev.pptx.pdf" )**  (Outil de Gestion de Rondes au Niveau du Mobilier urbain) est un outil de mise en place et synchronisation de rondes pour la gestion de mobilier urbain à partir d'une base de données pour les collectivités territoriales.



## News

- 3 Mai 2024 [v0.1] : 1......

   

## Fonctionnalités

- Création de rondes en sélectionnant des points sur une carte 

- Calcul d'itinéraires et d'isochrones à partir des points sélectionnés 

- Synchronisation des données des rondes avec une base de données PostgreSQL 

- Suppression des rondes une fois la synchronisation terminée

  

## Installation

1. Téléchargez et installez [QGIS](https://www.qgis.org/en/site/), [QField](https://qfield.org/) et clonez le repo :

   ```git
   git clone gitgit@gitlab.com:Thomas.Andre.Archgeo/projet-geodev-pdi21.git
   ```

2. Ouvrez QGIS, cliquez sur la colonne "Plugin", sélectionnez "Install from ZIP", sélectionnez le fichier zip téléchargé depuis GitLab, puis cliquez sur "Install Plugin" pour le télécharger:

   

   <img width="800" src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/upgit_20240510_1715301380.png" alt="image-20240509204857740" />

   

## Utilisation

### Desktop (Qgis)(à faire)

- mIoU from PaddlePaddle and other from ONNX.





### Mobile (Qfield)



1. Lancez Qfield et cliquez sur le "Projet QFieldCloud".

   <img width="400" src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/upgit_20240510_1715301386.jpg" alt="SmartSelect_20240226_145243" />
   
   
   
2. Cliquez "Répertoire de QField".

   <img width="400" src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/upgit_20240510_1715301391.jpg" alt="SmartSelect_20240226_145303" />
   
   
   
3. Choisissez "Importer un projet à partir d'un dossier" (ou avec votre moyen préféré).

   <img width="400" src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/upgit_20240510_1715301406.jpg" alt="SmartSelect_20240226_145330" />
   
   
   
4. Importez un fichier, ouvriez un projet.

   <img width="400" src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/upgit_20240510_1715301414.jpg" alt="SmartSelect_20240226_145432" />
   
   
   
5. Sur le côté gauche de l'interface, on trouve les couches configurées par l'administrateur.

   <img width="400" src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/upgit_20240510_1715301417.jpg" alt="SmartSelect_20240226_145532" />
   
   
   
6. Sélectionnez la couche vectorielle correspondante et cliquez sur les données ponctuelles correspondantes pour passer en mode édition.

   <img width="400" src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/upgit_20240510_1715301420.jpg" alt="SmartSelect_20240226_145621" />
   
   
   
7. Modification des données.

   <img width="400" src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/upgit_20240510_1715301424.jpg" alt="SmartSelect_20240226_150905" />
   
   
   
8. Cliquez sur "synchronisation" pour synchroniser les données.

   <img width="400" src="https://raw.githubusercontent.com/xiejiongru/GeRoNiMo/master/2024/05/upgit_20240510_1715301427.jpg" alt="SmartSelect_20240226_145549" />
   



## Maintaineurs：

Ce projet a été réalisé en collaboration par les étudiants de première année du master de l'[École Nationale des Sciences Géographiques](https://ensg.eu/fr) (ENSG-Géomatique) pour l'année académique 2023-2024, au sein du groupe GeRoNiMo. Il a été supervisé conjointement par l'ENSG-Géomatique et [Coexya](https://coexya.eu/).

Membres du groupe :

- Thomas ANDRE
- Thomas BOUTONNÉ
- Antonin OLLIER
- Romain THIRIOT
- Jiongru XIE

GeRoNiMo est actuellement maintenu par le groupe GeRoNiMo.

**![img](https://lh7-us.googleusercontent.com/cMGB8VPhosYzesKnoxCR4cG0ozOn9X3ATqCzkw81rUnXjZGtMC-O8mmatzxswO80AwZ_NfRPOzoDmsdXsRkhim0SEQzXtpQkeqK1qfQpfpGT0IzAlRJUPyW0RMm9SQSSZJAhcez1oS78u-JTIk6712w)**

