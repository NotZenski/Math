# web-minecraft
<i>Minecraft w przeglądarce!</i>

> **Pro tip:** Przy uruchamianiu na lokalnej maszynie potrzebna jest najnowsza wersja node.js i npm.<br>
>  Instalacja CoffeeScripta nie jest wymagana do włączenia gry.<br>
>  Zalecam grę włączać na przeglądarce Google Chrome</u>.<br>

<h4>Szykujące się updaty:</h4>
<li>
	Dynamiczne ładowanie i odładowywanie chunków
</li>
<li>
	Generowanie nieskończonego terenu
</li>
<li>
	Połączenie z prawdziwym serwerem minecraftowym
</li>



<i>
</i>
<h3>Instalacja repozytorium</h3>

```bash

#Instalacja repozytorium
git clone https://github.com/michaljaz/web-minecraft
cd web-minecraft

#Instalacja niezbędnych bibliotek
npm install

```

<h3>Uruchamianie gry</h3>

```bash

#Uruchamianie serwera express i websocket
npm start

```

Po uruchomieniu serwera gra zostanie hostowana pod linkiem: <a href="http://localhost:8080">http://localhost:8080</a>



<h3>DEMO</h3>

DEMO gry znajduje się pod adresem: <a href="http://mc.grok.eu">http://mc.grok.eu</a>

<h3>Przydatne narzędzia:</h3>

```bash

#Komilator coffeeScript
npm run coffee

#Ignorowanie folderu node_modules
npm run gitignore

#Generowanie atlasu tekstur
npm run atlas

```

<img src="src/screenshot.png"
     alt="screenshot"
     style="float: left; margin-right: 10px;" />


