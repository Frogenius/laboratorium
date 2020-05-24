# laboratorium

## Cwiczenie laboratoryjne nr 1 - Podstawy HTML
### Strona wizytowka zawierajaca: 
* Main Page
* The OCT principles
* The OCT measurements
* Specification of laboratory OCT systems
* Contacts

## 1.1. Wstęp
> Celem ćwiczenia jest zapoznanie studentów z podstawowymi elementami języka HTML.
Zostaną omówione takie elementy jak struktura strony, formatowanie akapitów, wstawianie
elementów graficznych, tworzenie list, formularzy oraz odnośników do innych dokumentów.
>
### Przed przystąpieniem do ćwiczeń należy bezwzględne:
* przeczytać materiał z wykładu,
* przestudiować instrukcję do ćwiczenia,
* zainstalować na własnym komputerze środowisko Microsoft Visual Studio (VS)
możliwie najnowszą wersję,
* zapoznać się ze środowiskiem VS w zakresie projektowania i testowania stron HTML. 
## 1.2. Pierwsza strona HTML
> Uruchom środowisko Microsoft Visual Studio i otwórz w nim kod strony L1_F0_01.htm.
Przeanalizuj kod strony i spróbuj zidentyfikować gdzie są sekcje head i body. Zastanów się
jakie informacje zapisywane są w tych sekcjach. 
#### Zwróć uwagę:
* jak definiuje się kodowanie znaków w dokumencie,
* jakie znaczniki akapitów zostały użyte,
* jak wygląda struktura dokumentu,
* w jaki sposób można formatować styl akapitów,
* jak umieszcza się elementy grafiki w dokumencie.
Następnie zmień styl akapitów h2 i h3 (zastosuj atrybut style np.
<p style="color:blue;margin-left:20px;">
* zmień kolor na czerwony,
* dodaj niebieską ramkę,
* zmień wysokość i krój czcionki,
  
 ## Instrukcja
#### Krok 0
Załóż własny katalog na dysku D nazwany twoim imieniem i nazwiskiem. Zapisuj
tam wszystkie pliki, na których będziesz pracować.
## Krok 1 (2 pkt.):
Przeanalizuj dokument i zdefiniuj style poszczególnych akapitów. Zwróć uwagę, że
niektóre akapity różnią się między sobą tylko niewielką ilością cech np. kolorem czy też
wyróżnieniem poprzez pochylenie lub podkreślenie tekstu. W takim przypadku do opisu
formatowania takiego akapitu zastosuj klasy. Opis stylów i formatowania poszczególnych
akapitów wykonaj z wykorzystaniem poniższej tabeli. Na podstawie tabeli uzupełnij
plik style.css.
## Krok 2 (1 pkt):
Przeanalizuj plik Szablon.htm. Jest to szablon dokumentu HTML składający się z sekcji
nagłówka oraz dwóch kolumn rozdzielonych pionową linią. Sprawdź czy rozmieszczenie i
wymiary poszczególnych elementów odpowiadają poniższemu opisowi.
* Nagłówek: wysokość 150 px; szerokość całego dokumentu.
* Kolumna lewa: szerokość 200 px, pełna wysokość dokumentu.
* Kolumna prawa: szerokość 750 px, wysokość zależna od treści.
Rozmiary, tło oraz parametry nagłówka i kolumn zapisz w pliku style.css z
wykorzystaniem identyfikatorów. Szablon dokumentu stwórz w oparciu o znaczniki div.
## Krok 3 (3 pkt):
Na podstawie szablonu HTML stwórz pierwszą stronę intro.htm. W nagłówku strony
umieść logo Politechniki Gdańskiej oraz wydziału ETI wraz z nazwą laboratorium,
ćwiczenia i uczelni tak jak jest to przedstawione w oryginalnym dokumencie.
W lewej kolumnie umieść menu z odsyłaczami do wszystkich stron HTML: intro.htm,
oct.htm, examples.htm, labOCT.htm oraz contact.htm.
W prawej kolumnie strony intro.htm umieść treść z sekcji Introduction dokumentu
źródłowego z zachowaniem odpowiedniego formatowania.
W podobny sposób utwórz kolejne dwie strony oct.htm (treść z „The OCT principles of
operations”) i examples.htm (treść: „The examples of OCT measurements”). Zwroć
szczególną uwagę na formatowanie i rozmieszczenie elementów graficznych w
dokumencie. Do podpisów rysunków użyj znacznika <caption>.
##  Krok 4 (2 pkt)
Podobnie jak powyżej, na podstawie szablonu dokumentu HTML przygotuj plik
labOCT.htm. Przygotuj nagłówek i lewą kolumnę tak samo jak w kroku 3. W prawej
kolumnie dokumentu umieść tabelę składającą się z ośmiu wierszy i czterech kolumn.
Hasła umieszczone w pierwszym wierszu i pierwszej kolumnie wyróżnij pogrubieniem.
Rozdziel komórki pojedynczą linią ciągłą oraz zastosuj schemat kolorów zbliżony do
tabeli umieszczonej w dokumencie źródłowym.
## Krok 5 (2 pkt)
Przygotuj plik contact.htm w podobny sposób jak poprzednie dokumenty. W prawej
kolumnie umieść formularz składający się z dwóch pól tekstowych do wprowadzenia
imienia i nazwiska, przycisków typu radio oraz pola tekstowego do wprowadzenia treści
wiadomości. Ustaw atrybut action formularza tak aby po naciśnięciu przycisku Submit
można było wysłać e-mail z treścią wprowadzoną do formularza na adres
ala.i.kot@gmail.com. Zachowaj oryginalne formatowanie formularza.
