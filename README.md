## Passwordless authentication
> Projekt ma na celu ukazanie praktycznego zastosowania wybranych metod uwierzytelniania bezhasłowego.
>  - Kod wysyłany w wiadomości e-mail
>  - Captcha

**1. Wykorzystane technologie**
 -   **SimpleCaptcha** - biblioteka stworzona dla języka Java umożliwiająca implementację bezhasłowej metody uwierzytelniania typu Captcha,
 -   **JavaFX** - technologia umożliwiająca tworzenie interfejsów graficznych dla aplikacji napisanych w języku Java. 

**2. Wymagania funkcjonalne**
Aplikacja spełnia poniższe wymagania funkcjonalne:
 - Użytkownik uruchamia aplikację.
 - Aplikacja zaraz po uruchomieniu wyświetla użytkownikowi interfejs graficzny, przy pomocy którego może realizować czynności.
 - Użytkownik wpisuje adres e-mail, przy pomocy którego chce się zalogować.
 - Aplikacja wyświetla użytkownikowi grafikę (tzw. Captchę).
 - Użytkownik przyciskiem prosi o ponowne wygenerowanie grafiki (tzw. Captchy),
 - Użytkownik wpisuje treść widoczną na grafice (tzw. Captchy).
 - Użytkownik przyciskiem żąda wysłania kodu na adres e-mail, przy pomocy którego będzie mógł się zalogować.
 - Użytkownik wpisuje otrzymany w wiadomości e-mail kod.
 - Użytkownik przyciskiem loguje się na konto. 
 - Użytkownik zamyka aplikację.

**3. Wymagania niefunkcjonalne**
Aplikacja spełnia poniższe wymagania niefunkcjonalne:

 - Aplikacja wykorzystuje nazewnictwo języka polskiego. 
 - Aplikacja zaprogramowana jest w języku programowania Java. 
 - Interfejs graficzny aplikacji stworzony jest przy pomocy technologii JavaFX. 
 - Grafiki (tzw. Captche) tworzone są przy pomocy biblioteki SimpleCaptcha. 
 - Kod generowany przez aplikację i wysyłany na adres e-mail ma ograniczony termin ważności, po którym staje się bezużyteczny. 
 - Kod generowany przez aplikację i wysyłany na adres e-mail może być skutecznie wykorzystany tylko przez konkretny adres e-mail w celu logowania, dla innych adresów e-mail jest on bezużyteczny.

> Projekt został zrobiony na studia w grupie 3-osobowej.
