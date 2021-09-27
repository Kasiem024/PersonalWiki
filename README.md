# PersonalWiki
My own personal Wiki
## Create Repository CMD Checklist
- lokalt på din dator, öppna mappen med VS övningen från förra veckan via CMD
- dubbelkolla att du står i rätt mapp
- skapa en .gitignore 
- code .gitignore
- kopiera allt från https://raw.githubusercontent.com/github/gitignore/master/VisualStudio.gitignore
- klistra in i .gitignore Visual CODE
- spara och stäng .gitignore
- dubbelkolla i CMD att filen finns där (> DIR)
- aktivera Git
- git init
- git add -A
- git commit -m "initial commit"
- Next, koppla upp oss mot GitHub!
- GitHub, skapa nytt repository, OBS ett tomt reporsitory, ingen readme eller gitignore
- Kopiera sökvägen till ditt nya git repo
- Tillbaka till CMD
- klistra in: git remote add...xxxxx.git
- testa att det funkade med: git remote -v
- då ska du se origin och sökvägen till github
- Next, "ladda upp din befintliga kod till GitHub": git push origin master
- OBS: det kan vara MAIN istället för MASTER, prova!
- Gå till GitHub och refresha och kolla att du kan se projektet där
- Next, tillbaka till Visual Studio, kolla in på Git-menyerna
- Prova att uppdtaera en fil och spara/commit och push
## Create Server NodeJS Checklist
- skapa mapp
- skapa en .gitignore 
- code .gitignore
- checka om allting är uppdaterat
- npm -v, node -v, git --version, heroku -v
- (ladda ner eller uppdatera efter behov)
- npm init
- git init
- git add -A
- git commit -m "initial commit"
- code .server.js
- npm install Nodemon -g
