# Le prix d'une frontière

## Profils locaux et densité des ensembles sans progression géométrique

**Aurélien Collado — Prix Fermat Junior 2026**

Ce dépôt accompagne mon mémoire pour le Prix Fermat Junior 2026.

## Résultat principal

$$
0.7397389699 < \alpha < 0.7626348308
$$

Le mémoire final comporte 10 pages.

## Mémoire

Le mémoire complet est disponible ici :

[**Lire le mémoire — PDF**](Le_prix_d_une_frontiere.pdf)

## Reproductibilité

Le paquet complet de vérification associé au mémoire est disponible dans la section **Releases** de ce dépôt.

Télécharger :

`Fermat_Junior_2026_Reproducibility_Package.zip`

Puis extraire l'archive et, depuis sa racine, exécuter :

```bash
python3 VERIFY.py
```

Une vérification complète réussie se termine par :

```text
ALL_VERIFIED
```

Le vérificateur reconstruit les entiers friables et les progressions géométriques à partir de la relation \(b^2=ac\), puis contrôle les témoins et certificats en arithmétique exacte.

Le mémoire distingue explicitement :

- les résultats démontrés directement dans le texte ;
- les résultats finis certifiés par ordinateur ;
- les résultats provenant de la littérature antérieure ;
- les résultats cités seulement comme perspectives.

En particulier, le résultat \(\Delta_{19}(361)=1\) est certifié par ordinateur, mais n'est pas utilisé dans l'encadrement final de \(\alpha\).

## Fichiers

- `Le_prix_d_une_frontiere.pdf` — mémoire final de 10 pages ;
- `Fermat_Junior_2026_Reproducibility_Package.zip` — archive complète de reproductibilité, disponible dans **Releases**.

## Auteur

**Aurélien Collado**  
Prix Fermat Junior 2026  
Octobre 2026
