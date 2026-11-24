# Installer Organisation IA

Ouvrez les [versions publiées](https://github.com/NeoliaTeams/organization-ia-downloads/releases). Téléchargez le fichier de votre système et `SHA256SUMS.txt` depuis la même version. Comparez l’empreinte affichée à la ligne qui porte le nom exact du fichier. En cas d’écart, n’ouvrez pas le fichier et contactez le [support](https://getneolia.com/support/contact/?app=organization-ia&need=technical).

## macOS sur Apple Silicon

1. Vérifiez le DMG dans Terminal avec `shasum -a 256 "Organisation-AI-0.5.20-macos-arm64.dmg"`.
2. Ouvrez le DMG, glissez l’application dans **Applications**, puis ouvrez-la depuis ce dossier.
3. Le DMG 0.5.20 est signé et notarisé. Si macOS bloque son ouverture, transmettez le texte de l’alerte au support. Si l’application affiche une erreur de démarrage, utilisez le lien vers le journal proposé dans la boîte de dialogue.

## Windows x64

1. Vérifiez le ZIP dans PowerShell avec `Get-FileHash ".\Organisation-AI-0.5.20-windows-x64.zip" -Algorithm SHA256`.
2. Dans l’Explorateur, choisissez **Extraire tout**. Dans le dossier extrait, ouvrez `Organization IA.exe`. Laissez les fichiers livrés à côté de l’exécutable.
3. L’exécutable 0.5.20 est livré sans signature Authenticode. SmartScreen peut afficher **Éditeur inconnu**. Consultez le [guide Windows officiel de GetNeolia](https://getneolia.com/apps/organization-ia/docs/telechargements.html) pour les messages propres à l’installation. En cas d’alerte antivirus ou de blocage par la politique de votre entreprise, contactez le support ou votre administrateur.

La [version web](https://organisation-ai.getneolia.com/) est également accessible sans installation.
