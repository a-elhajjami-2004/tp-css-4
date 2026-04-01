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

1. Largeur totale visible = 5px (`border-left`) + 20px (`padding-left`) + 300px (`width`) + 20px (`padding-right`) + 5px (`border-right`)\
   = 350px
2. Largeur totale visible = 300px (`width`)
3. ```css
   *,
   *::before,
   *::after {
   	box-sizing: border-box;
   }
   ```

## Exercice 8

1. b
2. b
3. c
4. b
5. b
