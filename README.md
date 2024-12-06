<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon site</title>
</head>
<body>
    <blockquote>
        L'IA Snapchat me fait peur. Elle me dit que je ne mange pas assez sainement ou que je sors trop.
    </blockquote>
    <button onclick="ajouterTexte()">Suite</button>
    <div id="conteneurTexte"></div> <!-- Conteneur où le texte sera ajouté -->

    <script>
        function ajouterTexte() {
            // Sélectionne l'élément <div> avec l'id "conteneurTexte"
            let conteneur = document.getElementById("conteneurTexte");
            // Crée un nouveau paragraphe
            let nouveauParagraphe = document.createElement("p");
            // Ajoute du texte au paragraphe
            nouveauParagraphe.textContent = "Là-bas, je vois mon pote qui me dit : 'C'est un prank.'";
            // Ajoute le paragraphe au conteneur
            conteneur.appendChild(nouveauParagraphe);
        }
    </script>
</body>
</html>

