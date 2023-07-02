# cw_praca_z_kodem

1.Uruchomienie aplikacji flask: flask run
2.Uruchom komendy  pip install –r requirements.txt, flask run za pomocą Makfile.
3.Po uruchomieniu aplikacji, wykonaj następujące polecenia:
Wejdź na adres http://127.0.0.1:5000/ i wykonaj w terminalu polecenie:
curl http://127.0.0.1:5000/
Wejdż na adres http://127.0.0.1:5000/hello i wykonaj w terminalu polecenie:
curl http://127.0.0.1:5000/hello
Wejdż na adres http://127.0.0.1:5000/hello/<name> i wykonaj w terminalu
polecenie:
curl http://127.0.0.1:5000/hello/<name>
4. W pliku app.py znajdź funkcję hello, zamień parametr “name”, który przyjmuje metoda
render_template na swoje imię. Wykonaj polecenie
curl http://127.0.0.1:5000/hello
5. Zainstaluj narzędzie pylint pip install pylint.
6. Dodaj w pliku Makefile komendę sprawdzającą kod: pylint
app.py.
