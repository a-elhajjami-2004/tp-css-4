# Réponses

## Exercie 1

### Sélécteurs

1. ```css
   .main-nav a {
   }
   ```
2. ```css
   a.active
   ```
3. ```css
   article.featured
   ```
4. ```css
   article p:first-child
   ```
5. ```css
   li: nth-of-type(even);
   ```

### Spécifité

1. `p` < `.text` < `p.text` < `#main` < `#main .text p`
2. Celle qui est définie en dernier (cascade)
3. Rend le code difficile à maintenir et débugger

## Exercice 2

### Box Model

1. Largeur totale = 15px (`margin-left`) 5px (`border-left`) + 20px (`padding-left`) + 300px (`width`) + 20px (`padding-right`) + 5px (`border-right`) + 15px (`margin-right`)\
   = 380px
2. Largeur totale = 15px (`margin-left`) + 300px (`width`) + 15px (`margin-right`)\
   = 330px
3. ```css
   *,
   *::before,
   *::after {
   	box-sizing: border-box;
   }
   ```
