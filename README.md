🛡️ GuardKid (wcześniej Korsarz)
Lekki, bezpieczny i przyjazny system kontroli rodzicielskiej dla Windows.
GuardKid to aplikacja stworzona w Pythonie, która pomaga rodzicom skutecznie zarządzać czasem spędzanym przed komputerem przez ich dzieci.
System oferuje dyskretny, pływający licznik, bezpieczny ekran blokady oraz panel zdalnego sterowania dostępny z poziomu smartfona.

✨ Kluczowe Funkcje
Inteligentne Limity: Ustawiaj domyślne limity dobowe lub korzystaj z kalendarza, by planować wyjątki (np. więcej czasu w nagrodę).
Nieugięta Blokada: Po upływie czasu ekran zostaje zablokowany, poprzedzony łagodnym, 5-minutowym ostrzeżeniem.
Zdalne Sterowanie: Wbudowany serwer Flask pozwala rodzicowi dodawać/odbierać czas oraz monitorować status sesji z dowolnego urządzenia w tej samej sieci Wi-Fi.
Blokada Aplikacji: Aktywna ochrona przed uruchamianiem przeglądarek i gier (Roblox, Minecraft, Fortnite) po wyczerpaniu limitu.
Tryb Dyskretny: Minimalistyczny interfejs, który nie przeszkadza w nauce czy zabawie, dopóki limit nie dojdzie do zera.
Zabezpieczenia: Pliki stanu i ustawienia są szyfrowane kluczem sprzętowym unikalnym dla Twojej płyty głównej (UUID).

🚀 Jak Zacząć?
Instalacja: Pobierz najnowszy plik GuardKid.exe z sekcji Releases.
Pierwsze Uruchomienie: Domyślny PIN to 0000. Wejdź w ustawienia, aby go zmienić i ustawić własne limity.
Autostart: Włącz opcję "Autostart" w zakładce konfiguracji, aby ochrona ładowała się automatycznie przy starcie systemu.

🛠️ Technologia
Język: Python 3.x
Interfejs: Tkinter (Własne style graficzne)
Backend: Flask (Panel zdalny)
Bezpieczeństwo: Szyfrowanie XOR powiązane z ID sprzętowym komputera
