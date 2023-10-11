# projetDansLaMontagne ([en](./README-EN.md)
> Projet tutoré de troisième année de BUT Informatique.

## L'équipe

Nous sommes une équipe de cinqs étudiants à l'[IUT de Bayonne](https://www.iutbayonne.univ-pau.fr/presentation.html) en troisième (et dernière) année de [BUT informatique](https://www.iutbayonne.univ-pau.fr/but/informatique).

## Le projet

Le [refuge de Pineta](https://www.valpineta.eu/fr/el-refugio/) et ses randonneurs ont besoin d'une application mobile afin d'avoir accès au tracés et aux cartes et d'y placer des points d'intérêts (belle vue, arbre blocant le chemin, ...) lors d'une balade. N'ayant pas souvent de connexion, l'application doit pouvoir fonctionner hors-ligne.

## Les technologies
- [React Native](https://reactnative.dev/) avec [TypeScript](https://www.typescriptlang.org/) pour l'application.

  Cela nous permet d'avoir un seul code pour une application à la fois sur iOS et sur Android.
- API/Plugin Wordpress pour la communication avec la BD.
- Fichiers binaires compilés grâce à [Rust](https://www.rust-lang.org/)

  Ces fichiers nous permettent d'effectuer les comparaisons entre fichiers GPX, passage de GPX à JSON, ect... Voir [le repo](https://github.com/projetDansLaMontagne/gpx-coords-tools) pour plus d'infos.
