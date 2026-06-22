# Journal de bord décrivant les étapes


## Installation

Les étapes d'installation sont :

1. Clone `git clone https://github.com/HugoBlox/theme-academic-cv.git academic-test` du projet dans academic-test.
2. Ouverture dans VS Code.
3. Vérification du gestionnaire de modules : Le projet utilisant déjà Go Modules (go.mod présent), inutile de faire un hugo mod init.
4. Synchronisation via `hugo mod get -u` et `hugo mod tidy` pour s'assurer d'avoir les dernières versions du Schéma de Hugo Blox.
5. Lancement du serveur avec `hugo server`.
6. `git remote set-url origin git@github.com:ggenestoux-cmd/test-academic.git`
7. `git commit -m "Init" && git push origin main`

## Tailwindcss

1. `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process`
2. `npm install -D tailwindcss postcss autoprefixer`