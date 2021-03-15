# les .env

- Les points exist aussi coté back que front  
  ce sont des variables dites d'environnement.

- le point .env doit etre surtout personnel, il ne doit pas etre push sur github.

- Il doit contenir les informations relative au développement local ou product selon le mode de travail.

- Dans le fichier .env.exemple la différenciation  
  des variables personnelles ou communes se fera avec les symboles suivant :

```css
- * => personnelle
- $ => communes
```

- Pour acceder aux variables d'environnement dans le code il faut utiliser `process.env`
