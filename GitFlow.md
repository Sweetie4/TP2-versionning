# Git Flow

Git flow est un workflow parmis plein d'autres qui a été proposé par Vincent Driessen en 2010 dans un blog.

il découpe la production de logiciel en plusieur branches de travail.

### les deux principales sont : 

main et developp

### les secondaires sont :

#### hotfixes, release 

en lien direct avec la branche main. 

#### et "features" 

en lien avec la branche develop

Hotfix est branch depuis mains puis merge avec main directement alors que release est branch de develop puis merge sur le main.

le principe est de laisser la branche main le plus clean possible. on y mergera uniquement les hotfixes et les releases.

les releases auront été testé et débeugué au préalable depuis des test sur la branche develop sur laquelle auront été merge les branches de features.