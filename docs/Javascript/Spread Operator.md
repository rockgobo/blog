# Spread Operator (...)

Der Spread Operator erlaubt es jedes iterierbares Datenobjekt (String, Array, Map...) für Stellen aufzulösen an denen normalerweise 0 bis n Argumente erwartet werden, zum Beispiel Funktionsparameter. 
Dadurch lassen sich auch sehr einfache Operationen mit Arrays auszuführen, zum Beispiel: 

```javascript
const array1 = [1,2,3];
const array2 = [4,5,6];

const array = [...array1, ...array2];
```