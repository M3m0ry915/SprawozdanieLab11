# SprawozdanieLab11
Na początek trzeba zacząć od sprawdzenia czy docker compose jest zainstalowany można to zrobić takim poleceniem:  
  
`$ docker-compose --version`  
  
Znajdując się w katalogu lab11 wykonujemy polecenie:  
  
`$ docker-compose up -d`  
  
Teraz możemy przejść do:  
* http://localhost:4001 , aby zobaczyć stronę startową PHP (phpinfo).  
* http://localhost:6001 , aby uzyskać dostęp do phpMyAdmin.  
Należy użyć <ins>root</ins> jako użytkownika oraz <ins>example</ins> jako hasła.  
Dołączony został również zrzut ekranu prezentujący założenie testowej bazy danych o nazwie test_docker.
  
Aby sprawdzić status kontenerów wykonujemy polecenie:
  
`$ docker compose ps`

Wyniki oraz efekty tych poleceń zostały dołączone w postaci zrzutów ekranu.
