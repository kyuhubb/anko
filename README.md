# Anko
Anko est une Webapp simple permettant d'importer vos decks Anki sur le bot Kotoba (discord)

<h2>Instructions</h2>
<p>1) Lancer Anki sur Pc<br>
2) Fichier > Exporter > Cartes avec notes en clair<br>
3) Lancer la Anko.html<br>
4) Copier/Coller le contenu du fichier .txt<br>
5) Choisir un mode de conversion : "Question --> lecture" ou "Question --> traduction"<br>
6) Convertir !</p>

<h2>Les Modes de Conversion :</h2>
<p>A) Question --> lecture　ex: 明日　あした/あす<br>
B) Question --> traduction　ex: 明日 demain</p>
<h2>Mode A</h2>
<p>Ce mode sépare la question de la réponse à partir du premier espace qu'il croise, de ce fait il est impératif que <br>la question ne contienne aucun espace.<br>
Utilisez des virgules, slash ou n'importe quel autre symbole si vous voulez écrire plusieurs mots à la suite.<br>
Cependant la réponse peut inclure autant d'espaces que souhaité.<br></p>
<p>exemple :<br>
Q: わたし/あたし<br>
R: je <br>
</p>
<h2>Mode B</h2>
<p>Ce mode sépare la question de la réponse dès qu'un caractère latin ou non-latin est croisé, de ce fait il est nécessaire que la question et la réponse comportent l'un des caractères non-latin et l'autre des caractères latins<br>
La question et la réponse peuvent tout deux contenir autant d'espaces que souhaité.</p>
<p>
Non-accepté :<br> 
Q : 歯医者 ou 歯科医<br>
R : Dentiste<br><br>
Accepté : <br>
Q: 歯医者, 歯科医<br>
R: Dentiste
</p>
