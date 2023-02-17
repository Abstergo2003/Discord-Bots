# Moderator Bot
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

CREATED BY: Abstergo using Discord Bot Maker

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
Ważne: PRZECZYTAJ TO ZANIM DODASZ BOTA NA SERWER
################################################################################################################
WSTĘP

Cześć,
Moderator Bot, zapewnia usługę planowania streamów, chatu online dla tegoż streama (zamyka się po zakończeniu streama), oraz piękny backup czatu.

Komendy:
/mshed - podajac godziny i minuty do startu planujesz swojego streama
/cstream - odwołuje twoje przyszłe streamy
/muse - użyj wzorca wiadomości do wysłania na chat
/mend - kończy stream, czeka 2h, usuwa i odtwarza kanał live stream, wysyła z niego piękny backup.

Cały czas w użyciu:
/moderator - używa się za każdym razem gdy na kanał live-chat wysłana jest wiadomość, filtruje ją, i gdy zjadzie przekleństwo to ją usuwa
/save - zapisuje wiadomości wysłane na kanał live-chat, do późniejszego backupu
!!! Pliki pięknego backupa są wysyłane na nowy kanał live-chat !!!


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