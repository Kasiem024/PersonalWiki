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
- ladda ner node.js och npm https://nodejs.org/en/
- ladda ner heroku CLI https://devcenter.heroku.com/articles/getting-started-with-nodejs?singlepage=true
- (ladda ner eller uppdatera efter behov)
- npm init (skapar package.json)
- git init
- git add -A
- git commit -m "initial commit"
- code .server.js
- npm install Nodemon -g
## Länkar för att skapa server.js
- https://www.w3schools.com/nodejs/met_http_createserver.asp
- https://nodejs.org/en/knowledge/HTTP/servers/how-to-create-a-HTTP-server/
- https://www.w3schools.com/nodejs/nodejs_filesystem.asp
- https://github.com/herkommer/D210927X1
## Lokal utveckling med NodeJS som webbserver
- Skapa en lokal mapp för dagens uppgift
- .gitignore för NodeJS
- kolla versioner av node, npm och git
- npm init (för att skapa en package.json)
- Visual Code (code .) för att öppna mappen som utvecklingsmiljö i VS Code
- git init (via cmd i VS Code eller via VS Code Git-menyn)
- commit "ready to go"
- npm install nodemon -g (installer node monitor globalt på din dator)
- skapa en server.js fil
- skriv kod för att dra igång en lokal NodeJS webbserver (se länkar nedan för inspo)
- starta med nodemon server.js
- öppna chrome och F12 och kolla localhost:8080 (eller den port du valt)
- Laborera med att sätta header till text/raw vs text/html och se skillnaden via F12 i Chrome
- skapa en index.html
- Använd VS Code för att få html5 snyggt på plats snabbt
- uppdatera server.js med fs modulen och leverera nu index.html filen (se länkar nedan för inspo)
## Deploy (driftsätt) till Heroku
- Skapa ett konto på Heroku 
- Installera Heroku CLI lokalt via Heroku (se länk nedan)
- Öppna mappen för programmet i CMD och kör en heroku login 
- se till att git status är ok (annars add och commit)
- skapa en Heroku app med heroku create
- provkör med heroku local web
- se till att uppdatera package.json med "config "node" = "14.x" och att "start" är server.js (se exempel nedan)
- checka git remote -v (att herokus git länkar  visas)
- git push heroku main (kan ta lite tid...)
- heroku open
- Om det strular, kolla heroku logs --tail (alt direkt på heroku-sidan)
## Data
- (localdb)\mssqllocaldb

## ASPCore
[Länk till guiden](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-6.0&tabs=visual-studio-code)

I CMD: 
dotnet dev-certs https --trust

## DOM
https://www.javascripttutorial.net/javascript-dom/document-object-model-in-javascript/

## Git
For squashing commits https://www.internalpointers.com/post/squash-commits-into-one-git

## TailWind CSS
[Offical Docs](https://tailwindcss.com/docs/installation)

npm install -D tailwindcss postcss autoprefixer

npx tailwindcss -i ./input.css -o ./output.css --watch

CDN Link https://cdn.tailwindcss.com

[All Classes](https://tailwind.build/classes)
