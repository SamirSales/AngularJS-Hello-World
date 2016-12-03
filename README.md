### app.js
Nesse arquivo o módulo ***app*** é declaparado.

### MainController.js
Esse arquivo define o escopo do módulo ***app***.

### index.html
Aqui, objeto ***app*** será utilizado. Exemplos:

html | angularjs
-----|------
body | ng-app="myApp"
div  | ng-controller="MainController"
div  | ng-repeat="product in products"
p    | ng-click='plusOne($index)'
