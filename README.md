**Twig - 01. Démarrage et utilisation**

Critères de validation

- Il y a un fichier Twig products.html.twig dans le dossier de src/View.
- La syntaxe de Twig est correctement utilisée (il doit y avoir au minimum une boucle).
- Dans ton navigateur, la page index.php affiche bien les 6 produits, à raison de 3 par ligne. Ainsi que le résultat dump() du tableau de produit.

**Twig - 02. Héritage et inclusion**

Critères de validation

- parent() est utilisé dans le fichier home.html.twig
- Les bonnes pratiques de nommage sont appliquées

**Twig - 03. Les globales**

Critères de validation

- Il y a bien un $twig->addGlobal() dans config/twig.php pour déclarer un email de contact
- Il y a bien l'inclusion du fichier src/View/_footer.html.twig dans le layout.html.twig
- Les bonnes pratiques de nommage sont appliquées
