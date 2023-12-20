# Cas Kaggle APC UAB 2023-24
### Arnau Berenguer Jiménez
### Dataset: [Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

## Resum
Aquest dataset conté dades sobre les aplicacions de la Google Play Store i està format per valors String i Numèrics.
Conté els següents atributs:
 * **App**: Nom de l'aplicació, tipus String.
 * **Category**: Categoria de l'aplicació, tipus String.
 * **Rating**: Nota mitjana posada pels usuaris, tipus Float entre 0 i 5.
 * **Reviews**: Nombre de comentraris dels usuaris sobre l'app, tipus Integer.
 * **Size**: Pes de l'aplicació, tipus String.
 * **Installs**: Nombre de descàrregues de l'aplicació, tipus String.
 * **Type**: Aplicació gratuita o de pagament, tipus String.
 * **Price**: Preu de l'aplicació, tipus Float.
 * **Content Rating**: Categoria de gent a la que va dirigida l'app, tipus String. (Adolescents, nens, adults...)
 * **Genres**: Gèneres als que pertany l'aplicació, tipus String.
 * **Last updated**: Última vegada que es va llançar una actualització, tipus String.
 * **Current ver**: Versió actual de l'aplicació, tipus String.
 * **Android ver**: Versió mínima requerida del SO Android per poder-la instal·lar, tipus String.

 ## Objectiu
Detectar quines característiques fan que una aplicació es descarregui més per poder crear una aplicació i rentabilitzar-la.

## Preprocessing
El dataset contenia nuls que hem eliminat, duplicats que també hem eliminat, i hem hagut de tractar diferents formats de dades i transformar-los. Hem hagut de transformar el nombre de descàrregues, que contenia +, K o M, el tamany, que contenia K o M, i els gèneres per agafar-ne només el principal. També hem adaptat l'atribut Last Updated a un valor numèric que representa la diferencia entre la ultima actualització general i la última actualització de l'aplicació en concret.

## Models
Hem utilitzt els següents models:
* **Regressió Lineal**
* **Regressió Logística**
* **Decision Tree**
* **Random Forest**
* **Màquina de Vectors de Suport**

## Requisits
* Matplotlib
* Pandas
* Numpy
* Seaborn
* Sklearn
* Pylab

## Llicència
Projecte desenvolupat per Arnau Berenguer Jiménez.