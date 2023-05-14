- [1. Obiekty](#1-obiekty)
  - [1.1. Imprezy i miejsca](#11-imprezy-i-miejsca)
  - [1.2. Kupno produktów](#12-kupno-produktów)
- [2. Reguły dotyczące zamawiania miejsc przez stronę internetową](#2-reguły-dotyczące-zamawiania-miejsc-przez-stronę-internetową)
  - [2.1. Nie do złamania](#21-nie-do-złamania)
  - [2.2. Miękkie](#22-miękkie)
  - [2.3. Rozważone, odrzucone](#23-rozważone-odrzucone)
- [3. Procesy dotyczące produktów](#3-procesy-dotyczące-produktów)
  - [3.1. Nie do złamania](#31-nie-do-złamania)
  - [3.2. Miękkie](#32-miękkie)
- [4. Procesy](#4-procesy)
  - [4.1. Rezerwacja stolików](#41-rezerwacja-stolików)
  - [4.2. Modyfikacja rezerwacji](#42-modyfikacja-rezerwacji)
  - [4.3 Kupowanie voucherów](#43-kupowanie-voucherów)
  - [4.4 Kupowanie przedmiotów](#44-kupowanie-przedmiotów)
  - [4.5 Dodawanie kodów promocyjnych.](#45-dodawanie-kodów-promocyjnych)
# 1. Obiekty

## 1.1. Imprezy i miejsca
1. W parku rozrywki znajdują dzieją się imprezy
2. Imprezy mają swoje lokacje
3. Lokacje mają swój podział na okna w których można wynajmować stoliki.
4. W lokacjach można kupować jedzenie i napoje

## 1.2. Kupno produktów
1. Produkty można zamawiać używając kiosków samoobsługowych lub kas
2. Jest wiele kas samoobsługowych oraz miejsc odbioru.
3. Produkty można zamówić z dostawą do wykupionego miejsca.

# 2. Reguły dotyczące zamawiania miejsc przez stronę internetową

## 2.1. Nie do złamania

1. Każde miejsce w danym okienku czasowym może być wynajmowane przez tylko jedną osobę.
2. Każde miejsce musi należeć do pewnego tieru.
3. Każda lokacja oraz impreza może definiować swoje własne okna czasowe, ceny oraz miejsca.
4. Miejsca można wynająć jedynie przed rozpoczęciem okna czasowego.
5. Rezerwacja musi być potwierdzona i zaliczka zapłacona przed oknem czasowym

## 2.2. Miękkie

1. Rezerwacja musi być w pełni opłacona przed oknem wynajęcia.
2. Miejsce które osoba dostaje musi być dokładnie w tym miejscu które wybrała.
3. Miejsca mogą mieć swoją własną cenę niezależną od swojego tieru.
4. Jeżeli zaliczka nie jest zapłacona przez 15 minut po rezerwacji istnieje możliwość utraty rezerwacji.
5. Użytkownik musi posiadać konto w trakcie rezerwacji

## 2.3. Rozważone, odrzucone

1. Zamawianie produktów przez stronę internetową
2. Rezerwacja bez płatności

# 3. Procesy dotyczące produktów


## 3.1. Nie do złamania

1. Produkt kupiony raz nie może być wydany więcej niż raz.
2. Produkty mające ograniczenia wiekowe muszą zostać wydane po okazaniu dowodu.
3. Vouchery oraz kody zniżkowe muszą być użyte ograniczoną, przewidzianą liczbę razy.
4. Użytkownik może sprawdzić stan swojego zamówienia  


## 3.2. Miękkie

1. Produkt powinien być wydany w wybranym punkcie wybrania.
2. Produkt musi być wydany w przewidzianym w trakcie zamówienia czasie.
3. Dokładnie zamówiony produkt powinien zostać wydany - może być wydany zamiennik po zgodzie.

# 4. Procesy
## 4.1. Rezerwacja stolików

1. Użytkownik na stronie wybiera imprezę oraz okienko czasowe.
2. Użytkownik wybiera interesujące go miejsca.
3. Użytkownik tworzy rezerwację.
4. Użytkownik zakłada konto (jeśli nie był zalogowany)*
5. Użytkownik podaje swoje dane (jeśli nie jest zalogowany)
5. Użytkownik opłaca zaliczkę (bądź pełną kwotę).
6. Użytkownik dostaje potwierdzenie rezerwacji (w postaci pliku pobranego na stronie lub wysłanego na mail).

Możliwe błędy:
- użytkownik zgubi plik rezerwacji (rozwiązanie - rezerwacja ma imię i nazwisko nawet bez konta)
## 4.2. Modyfikacja rezerwacji
Możliwe tylko jeśli użytkownik posiada konto oraz jeśli do wynajętego okna czasowego została więcej niż godzina
1. Użytkownik loguje się
2. Użytkownik wybiera swoje zamówienie
3. Użytkownik wybiera stoliki które chce mieć po zmianie oraz ich okno czasowe.
4. Użytkownik akceptuje zmiany.
5. Użytkownik płaci dodatkową zaliczkę jeśli dodał miejsca*   
* - opcjonalne

## 4.3 Kupowanie voucherów

1. Użytkownik loguje się na stronę internetową.
2. Użytkownik wybiera interesujące go vouchery
3. Użytkownik płaci
4. Użytkownik dostaje voucher w postaci kodu QR. 
5. Użytkownik używa kodu na imprezie.

Możliwe błędy:
- z powodu braku internetu na imprezie serwer lokalny nie wie o zakupionym voucherze (rozwiązanie - zapisanie danych vouchera w postaci jwt)
  
## 4.4 Kupowanie przedmiotów
1. Użytkownik podchodzi do kiosku samoobsługowego(lub kasy)
2. Użytkownik wybiera swoje zamówienie
3. Użytkownik wprowadza swoje vouchery oraz kody promocyjne.
4. Użytkownik płaci
5. Użytkownik dostaje wydruk z kodem QR i swoim numerkiem.
6. Użytkownik dostaje informację gdzie ma odebrać swoje zamówienie.
7. Użytkownik odbiera swoje zamówienie.

## 4.5 Dodawanie kodów promocyjnych.
1. Administrator wybiera nazwę kodu promocyjnego.
2. Administrator wybiera okres działania kodu promocyjnego.
3. Administrator wybiera liczbę użyć
4. Administrator wybiera zniżkę kodu
5. Administrator potwierdza wybór
