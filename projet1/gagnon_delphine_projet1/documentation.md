# Pourquoi avoir choisis ce système de nomenclature ?
 -J'ai nommé mes classes en essayant de leur donner une bonne description claire et courte. Par exemple si un élément faisait partie d'une carte, son nom de classe allait donc commencé par "carte" et suivre avec deux tiret du bas et un autre nom plus spécifique qui me permet de les identifiés entre eux.   
 -Exemple: carte__horaire__title et carte__horaire__desc   

 -Certains composants étaient plus facile à nommer avec une description visuelle comme dans le cas où certaine div était simplement des carrés gris à l'écran ; carte__artiste__gris. Cela me permettait de mieux me repérer et de mieux visualiser ce que je voulais modifier.

# Variables et design tokens  
J'ai uniquement utilisé des variables pour les couleurs pour ne pas avoir à répéter leur code rgba. Je ne voyais pas comment faire des variables pour les espacements allait me bénificier pour ce projet puisque la majorité du temps c'était très spécifique au composant. J'ai alors préféré garder les données de Figma.  

# Liste des composants réutilisables  
( Dans ces composants certains éléments peuvent aussi être réutilisable)
.section  
.section__title  
.section__blue  
.button__yellow 
.hero__button  
.carte__prog  
.carte__horaire  
.carte__artiste  
.carte__billet  
.carte__part  
.temoi__carte  
.carte__contact  

# Défi technique rencontrés + solutions 
Je dirais que le plus gros défi était de bien identifier les div dès le départ. À plusieurs reprises, j'ai du envelopper certaines parties par de nouvelles div pour que le flexbox fonctionne.  
Un autre défi était de le rendre responsive. J'ai fais de mon mieux pour utiliser des pourcentages lorsque j'en avais l'occasion ,mais la majorité du temps j'ai gardé les données de Figma.  

# IA
Pour savoir comment retirer les point de ma liste dans ma nav barre j'ai utilié Chat GPT dans sa version la plus récente (je crois) pour avoir une réponse rapide et efficace ( list-style-type: none; )