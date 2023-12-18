# Filtre écran "anomalies mesures"

## Modification de l'écran list 

J'ai ajouté à l'écran liste une partie une partie filtre pour permettre à l'utilisateur de cliquer sur modifier le filtre et de voir les filtres déjà mis.
![image](https://github.com/MathisCastell/Stage-Filtre-cran-anomalies-mesures-/assets/148212506/6d9e3b3b-f960-427f-bea1-86e7968bdc6f)
![image](https://github.com/MathisCastell/Stage-Filtre-cran-anomalies-mesures-/assets/148212506/fff6d282-af3b-47ed-bc34-30ebc576d794)
![image](https://github.com/MathisCastell/Stage-Filtre-cran-anomalies-mesures-/assets/148212506/c3140e15-cc25-410d-9ca0-e47fe978160a)
![image](https://github.com/MathisCastell/Stage-Filtre-cran-anomalies-mesures-/assets/148212506/ecf006ed-bc2a-4693-bad2-caec0112bf5f)

## Création de la page de filtre 

Définition des parties de la page.
Je défini les variables de session.
Dans la partie SQL, pour chaque partie du filtre je récupère dans la base de donnée toutes les options sur lesquelles l'utilisateurs peut filtrer
Ensuite j'appelle une PS de variable de session qui à pour but de renvoyer les valeurs au fichier avec le tableau regroupant toutes les valeurs pour les placer dans le WHERE de la requête SQL.![image](https://github.com/MathisCastell/Stage-Filtre-cran-anomalies-mesures-/assets/148212506/e9aed5f0-294b-4637-84cd-d1b61fa71598)


Ensuite j'affiche les champs dans la page.


Résultat :

![image](https://github.com/MathisCastell/Stage-Filtre-cran-anomalies-mesures-/assets/148212506/7ca64ccf-54f6-42fb-9424-c080dbf2b386)






