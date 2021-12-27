# Anko
Anko est une Webapp simple permettant d'importer vos decks Anki sur le bot Kotoba (discord)

<h2>Instructions</h2>
<p>1) Lancer Anki sur Pc<br>
2) Fichier > Exporter > Cartes avec notes en clair<br>
3) Lancer Anko.html (ou le site en ligne)<br>
4) Copier/Coller le contenu du fichier .txt<br>
5) Choisir un mode de conversion : "Question --> lecture" ou "Question --> traduction"<br>
6) Convertir !</p>
 
<h2>Les Modes de Conversion :</h2>
<p>A) Question --> lecture　ex: 明日　あした/あす<br>
B) Question --> traduction　ex: 明日 demain</p>

<h3>Mode A</h3>
<p>Ce mode sépare la question de la réponse à partir du premier espace qu'il croise, de ce fait il est impératif que <br>la question ne contienne aucun espace.<br>
Utilisez des virgules, slash ou n'importe quel autre symbole si vous voulez écrire plusieurs variantes d'un même mot.<br>
Cependant la réponse peut inclure autant d'espaces que souhaité.<br></p>
<p>à noter qu'un espace dans une réponse sera considéré comme un séparateur pour les réponses multiples.</p>
<p>exemple :<br>
Q: わたし/あたし<br>
R: je</p>

<p>Lorsqu'une réponse possède plusieurs réponses différentes veuillez séparer ces réponses avec un espace<br>
 ou l'un des symboles suivants : / \ , ; | 、・ </p>

<h3>Mode B</h3>
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

<p>Lorsqu'une réponse possède plusieurs réponses différentes veuillez séparer ces réponses avec l'un des symboles suivants : / \ , ; | 、・ <br>
remarque: les espaces ne peuvent pas servir de séparateur</p>
