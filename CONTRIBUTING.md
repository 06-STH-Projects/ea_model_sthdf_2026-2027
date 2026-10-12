# Ako pracovať s modelom / How to work with the model

> SK: krátke pravidlá. Podrobný návod bude v KNIFE (K000002). 
> EN: short rules. The full guide will be a KNIFE article (K000002).

## Pravidlá / Rules
1. **Jeden balík = jeden vlastník.** Menej konfliktov. / One package, one owner.
2. **Vždy najprv `git pull`.** / Always `git pull` first.
3. **Pracuj na vlastnej vetve** `ST0XX-nazov-balika`. / Work on your own branch.
4. **Pred commitom ulož model a zavri EA** (súbor `.qea` musí byť uvoľnený). / Save and close EA before committing.
5. **`.qea` sa nemerguje v GitHub UI.** Konflikt riešiš lokálne v LemonTree: *parent* (spoločný predok), *ours*, *theirs*. / Never merge `.qea` in the GitHub UI; resolve conflicts locally in LemonTree.
6. **Malé zmeny, časté commity.** / Small changes, frequent commits.
