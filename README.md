# VueJSValidator

Vi fik stillet en opgave, som gik ud på at tilføje et felt hvor man kunne indtaste sit nummer.
Feltet skulle selvfølgelig have validering på, som de allerede eksisterende felter har.
Forskellen var at dette felt krævede at det kun var 8 cifre der kunne blive indtastet.

Jeg har løst dette ved at lave en regular expression som kun tager imod tallene 0-9, og der skulle angives mindst og max 8 cifre.