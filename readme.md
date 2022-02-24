# MIT African Futures


## Hugo
Pour installer Hugo
```
brew install hugo
```
Mise à jour avec
```
brew upgrade hugo
```


## Install

Pour cloner avec le thème
```
git clone git@github.com:noesya/mit-africanfutures.git --recurse-submodules
```
Pour récupérer le thème
```
git pull --recurse-submodules
```


## Launch

Pour lancer le site
```
yarn
yarn watch
```


## Netlify
Pour déployer le site avec Netlify, penser à ajouter la deploy key.


## Params

Les params principaux sont dans config.yaml du theme, pour en ajouter ou modifier il faut overider dans config/_defaults/config.yaml
```
cdnkey: https://osuny-1b4da.kxcdn.com
cookie_banner:
  enable: true
  blank: true
  page: https://gdpr.eu/cookies/
```
