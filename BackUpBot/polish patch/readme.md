# dice-roller
##############################################################################################################################################################


By twój bot działał w wersji po polsku zwtczajnie podmień plik commands.json w folderze data na ten załączony tutaj


################################################################################################################################################################# 
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

CREATED BY: Abstergo using Discord Bot Maker

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
UWAGA: PRZECZYTAJ TO PRZED URUCHOMIENIEM BOTA
################################################################################################################
WSTĘP

Cześć,
Z tej strony BackUp Bot, od teraz wszytskie wiadomości wysłane na twoim serwerze są kopiowane do bezpiecznej bazy danych, byś mógł je w każdej chwili odzyskać.

Komendy:
/gbackup - generuje surowy plik kopii zapasowej który zawiera: text wiadomości, id nadawcy, i link do jego zdjęcia profilowego(wytłumaczę później)
/bbackup - generuje ładny plik kopi zapasowej (w html) który jest tak zaprojektowany by wygladał jak czat Discord (po to potrzebowałem linka do profilowego)
!!! Pliki kopii zapasowej są wysyłane tylko do właściciela serwera !!!

Wydarzenia:
W każdą niedzielę otrzymasz surowy plik kopii zapasowej
#################################################################################################################
Konfiguracja bota:

Muszisz zrobić to sam,
1. wejdź na https://discord.com/developers/applications
2. stwórz aplikacje bota, nazwij ją jak chcesz
3. znajdź 'app id' i 'bot token'
4. wejdź w  'lokalizacja bota'/data/settings.json
5. wprowadź dane z punktu 3. we wskazane pola
6. zapisz plik
##################################################################################################################################################################
Start twojego bota

1 metoda - na własnym komputerze (twój komputer będzi musiał cały czas działac by bot był online)(DARMOWA)

- zainstaluj node.js i uruchom go
- w konsoli wpisz: node 'lokalizacja bota'/bot.js
- gotowe
- możesz dodać bota do servera

2 metoda - na heroku (DARMOWA)
- stwórz Procfile i umieść go w lokalizacji bota
- w procfile wpisz 'worker: node bot.js'
- prześlij pliki na heroku
- zmień dyno formation na worker 
- możesz dodać bota na server

By dodać pota na server wklej ten link w przeglądarkę: https://discordapp.com/oauth2/authorize?client_id='id twojej aplikacji'&scope=bot&permissions=2146958591
###################################################################################################################################################################

Możesz wprowadzać zmiany w moim bocie, jednak jako że zostal on stworzony przy użyciu aplikacji Discord Bot Maker, może to być ciężkie nie używając jej,
Każdy prawdziwy programista powinin raczej napisac swojego bota od zera zamiast go przerabiać

######################################################################################################################################################################