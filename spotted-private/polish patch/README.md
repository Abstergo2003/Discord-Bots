# spotted-private
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

CREATED BY: Abstergo using Discord Bot Maker

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
WAŻNE: PRZECZYTAJ TO PRZED DODANIE BOTA NA SERWER
################################################################################################################
WPROWADZENIE

Ten bot tworzy infrastrukturę spotted an twoim serwerze
gdy dołączy stworzy 3 kanały i jedną rolę

1. kanał spotted	- anonymous messages appear here
2. kanał nsfw		- anonymous fap materials appaer here
3. kanał logs		- widoczny tylko dla administratora, możesz tu zobaczyć kto i co wysłał na kanał spotted/nsfw
4. rola nsfw		- tylko jej posiadacze mogą zobaczyć kanał nsfw

By wysłać spota wyślij wiadomość do bota
#################################################################################################################
KONFIGURACJA:
1. wejdź w https://discord.com/developers/applications
2. stwórz aplikacje swojego bota
3. znajdź jego token i app id
4. wejdź w 'lokalizacja bota'/data/settings.json
5. wklep dane z punktu 3
6. zapisz plik
##################################################################################################################
Rozruch bota

1 metoda - na komputerze (darmowa)
- zainstaluj i otwórz node.js
- wpisz node 'lokalizaja bota'/bot.js
- gotowe
- dodaj bota na server

2 metoda - na heroku (darmowa)
- stwórz Procfile i umieść go w plikach bota
- w procfile wpisz 'worker: node bot.js'
- prześlij pliki na heroku
- zmień dyno formation na worker 
- gotowe
- dodaj bota na server

UWAGA! MUSISZ WPIERW URUCHOMIĆ BOTA A DOPIERO POTEM DODAĆ GO NA SERVER ALO NIE BĘDZIE ON DZIAŁAŁ POPRAWNIE

By dodać bota na server wklej ten link do przeglądarki(uwaga musisz go lekko zmienić): https://discordapp.com/oauth2/authorize?client_id='your aplication id'&scope=bot&permissions=2146958591
########################################################################################################################

Możesz wprowadzać zmiany w moim bocie, jednak jako że zostal on stworzony przy użyciu aplikacji Discord Bot Maker, może to być ciężkie nie używając jej,
Każdy prawdziwy programista powinien raczej napisać swojego bota od zera zamiast go przerabiać

####################################################################################################################