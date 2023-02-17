# spotted-bot-dc
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

CREATED BY: Abstergo using Discord Bot Maker

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
WAŻNE: PRZECZYTAJ TO ZANIM URUCHOMISZ ALBO DODASZ BOTA NA SERWER
#################################################################################################
WSTĘP

Ten bot tworzy infrastrukturę spotted na twoim serwerze
gdy dołączy do serwera stworzy dwa kanały i jedną rolę

1. kanał Spotted 	- bot wysyła tutaj anonimowe wiadomosci po użyciu komendy /spotted

2. kanał Logs 		- tylko administrator widzi ten kanał
			- tutaj zbierane są logi z kanału spotted
			- to twoja jedyna opcja ny ukarać trolli
3. Rola cholernego Trola	- ta rola piętnuje i zabrania użytkownikom używania komendy spotted
#################################################################################################
Inne komendy

/rc - odtwarza infrastrukturę spotted (nie odtwarza wiadomosci z kanałów)(w razie zdrady jednego z adminów)

/cl - komenda czyszcząca - w razie ataku trola usuwa masowo wiadomosći z kanałow spotted i nsfw

/nsfw - to dodatek tworzący spotted do nsfw

/add-banned-word - dodaje wybrane przez ciebie słowo do listy zbanowanych
####################################################################################################
dodatek /nsfw

Tworzy jeden kanał i jedną rolę:
1. kanał nsfw - dokładnie taki jak spotted ale do materiałów nsfw (nie widzoczny bez roli)
2. rola nsfw-spotter - pozwala użytkownikom zobaczyć kanał nsfw (sam decydujesz kto ma dostęp)
###################################################################################################
Konfiguracja bota:

Musisz to zrobić sam
1. wejdź na https://discord.com/developers/applications
2. stwórz aplikacje swego bota
3. znajdź id i token swojej aplikacji
4. otwórz 'lokalizacja bota'/data/settings.json
5. wprowadź wcześniej zebrane dane w podpisane pola (zostaw "")
6. zapisz plik
####################################################################################################
Uruchom bota

MUSZISZ WPIERW URUCHOMIĆ BOTA PRZED DODANIEM GO DO SERWERA

1 metoda - na komputerze (twój komputer musi cały czas działać by działał bot)

- zainstaluj node.js i otwórz
- wpisz node 'lokalizacja bota'/bot.js
- gotowe
- możesz dodać bota na serwer

2 metoda - na heroku (darmowa)
- stórz Procfile i umieść go w lokalizacji bota
- w pliku Procfile wpisz 'worker: node bot.js'
- zuploaduj bota na heroku
- zmień dyno na worker
- możesz dodać bota na serwer
- gotowe



By dodać bota na serwer wklej ten link w przegladarkę (uwaga zmodyfikuj go): https://discord.com/api/oauth2/authorize?client_id=YOUR BOT APP ID&permissions=8&scope=bot%20applications.commands
################################################################################################################

Możesz wprowadzać zmiany do bota ale został on stworzony przy użyciu Discord Bot Maker'a więc moze to być trudne lub niemozliwe.
Każdy prawdziwy programista powinie raczej napisać własnego bota używając tego jako wzoru

####################################################################################################################
