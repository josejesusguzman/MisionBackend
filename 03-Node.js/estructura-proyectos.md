# Estructura de proyectos de Node.js

```gitignore
node_modules
package-lock.json
```

/modules/retrievedate.js
```JavaScript
// Este módulo lo creamos y solo devuelve la fecha actual DEL SERVER
exports.RetrieveDate = function() {
    return Date();
}
```