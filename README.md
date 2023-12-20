# Prérequis

* NodeJS >=16
* React 18.2.0
* React Native 0.72.7

## 1 - Démarrer le serveur Metro

Tout d'abord, vous devrez démarrer **Metro**, le _bundler_ JavaScript livré avec React Native.

Pour démarrer Metro, exécutez la commande suivante depuis la _racine_ de votre projet React Native :

```bash
# en utilisant npm
npm start

# OU en utilisant Yarn
yarn start
```

## 2 - Démarrez l'application

Laissez Metro Bundler s'exécuter dans son propre terminal. Ouvrez un nouveau terminal depuis la racine de votre projet React Native. Exécutez la commande suivante pour démarrer votre application Android ou iOS :

### Pour Android

```bash
# avec npm
npm run android

# OU avec Yarn
yarn android
```

### Pour iOS

```bash
# avec npm
npm run ios

# OU avec Yarn
yarn ios
```

Si tout est configuré correctement, vous devriez voir votre nouvelle application s'exécuter dans votre émulateur Android ou simulateur iOS peu de temps après, à condition d'avoir correctement configuré votre émulateur/simulateur.

C'est une façon de lancer votre application. Vous pouvez également l'exécuter directement depuis Android Studio et Xcode respectivement.

## 3 - Modifier l'application

1. Ouvrir `App.tsx` dans votre éditeur de texte favori et modifiez certaines lignes.
2. Pour **Android**: Appuyez deux fois sur la touche <kbd>R</kbd> ou sélectionnez **"Reload"** dans le **Menu Développeur** (<kbd>Ctrl</kbd> + <kbd>M</kbd> (sur Windows et Linux) ou <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (sur macOS)) pour voir vos modifications

   Pour **iOS**: Appuyez sur <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> dans votre simulateur iOS pour recharger l'application et voir vos modifications 

## Constuire l'APK

Pour générer le fichier apk de l'application, lancez la commande suivante :

``` bash
cd android && ./gradlew assembleRelease
```

L'apk sera disponible dans le dossier suivant : /android/app/build/outputs/apk/release/

# Documentation

- [Site React Native](https://reactnative.dev)
- ["Getting Started"](https://reactnative.dev/docs/environment-setup)
- ["Learn the Basics"](https://reactnative.dev/docs/getting-started) 
- [Blog Officiel React Native](https://reactnative.dev/blog) 
