# Anko
Anko est une Webapp simple permettant d'importer vos decks Anki sur le bot Kotoba (discord)

Instructions :
--------------
1) Lancer Anki sur Pc
2) Fichier > Exporter > Cartes avec notes en clair
3) Lancer la Anko.html
4) Copier/Coller le contenu du fichier .txt
5) Choisir un mode de conversion : "Question --> lecture" ou "Question --> traduction"
6) Convertir !

Les Modes de Conversion :
-------------------------
A . Question --> lecture　ex: 明日　あした/あす <br>
B . Question --> traduction　ex: 明日 demain <br>
<br>
Mode A 
-------
Ce mode sépare la question de la réponse à partir du premier espace qu'il croise, de ce fait il est impératif que <br>la question ne contienne aucun espace.<br>
Utilisez des virgules, slash ou n'importe quel autre symbole si vous voulez écrire plusieurs mots à la suite.<br>
Cependant la réponse peut inclure autant d'espaces que souhaité.<br>
exemple :<br> 
Q : わたし/あたし<br>
R : je <br>
<br>
Mode B
------
Ce mode sépare la question de la réponse dès qu'un caractère latin ou non-latin est croisé, de ce fait il est nécessaire que la question et la réponse comportent l'un des caractères non-latin et l'autre des caractères latins.<br>
La question et la réponse peuvent tout deux contenir autant d'espaces que souhaité.<br>
<br>
Non-accepté :<br> 
Q : 歯医者 ou 歯科医<br>
R : Dentiste<br><br>
Accepté : <br>
Q: 歯医者, 歯科医<br>
R: Dentiste
