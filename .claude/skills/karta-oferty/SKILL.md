---
name: karta-oferty
description: Buduje Kartę Oferty użytkownika, czyli jeden plik z tym, co dokładnie sprzedaje, komu, za jaki efekt, jakim mechanizmem i z jaką gwarancją. Dwie ścieżki: przegląd istniejącej oferty przez równanie wartości albo budowa od zera przez wywiad. Efekt to plik karta-oferty.md, z którego korzysta potem strona, mail, post i reklama. Wywołaj, gdy użytkownik mówi "karta oferty", "moja oferta nie sprzedaje", "nie umiem opisać tego, co robię", "ludzie mówią że za drogo", "no-brainer offer", "/karta-oferty", albo gdy prosi o copy na stronę sprzedażową i widać, że w projekcie nie ma pliku z ofertą.
---

# Karta Oferty

## Po co to jest

Kiedy oferta jest mętna, nic dalej nie działa. Strona nie konwertuje, reklama przepala budżet, a AI proszone o post generuje średnią z internetu, bo nie ma się do czego odwołać.

Karta Oferty to jeden plik, w którym stoi: kto jest klientem, co go uwiera, co ma być prawdą po współpracy, jaką drogą go tam prowadzisz, z czego składa się to, co dostaje, jak wygląda gwarancja i jaki jest następny krok.

Twoja rola: wyciągnąć to z użytkownika i zapisać tak, żeby dało się z tego napisać stronę. Nie wymyślać za niego.

---

## Zasady, których nie łamiesz

1. **Nie wymyślasz dowodów.** Żadnych liczb, procentów, „ponad 200 zadowolonych klientów" ani opinii, których użytkownik nie podał. To najszybsza droga do utraty zaufania, którego nie da się odzyskać.
2. **Nie wymyślasz efektów, których użytkownik nie kontroluje.** „Podwoisz przychód" wpisujesz tylko wtedy, gdy on sam to powiedział i potrafi obronić. Inaczej pytasz, co realnie jest w jego rękach.
3. **Cytujesz klienta dosłownie.** Problem zapisujesz słowami, które padły w rozmowie, wiadomości albo komentarzu. Nie tłumaczysz ich na branżowy język.
4. **Czego nie wiesz, zostawiasz jako `[do uzupełnienia]`.** Puste pole jest zawsze lepsze niż wypełnione zgadywanką. Sekcji nie domykasz dla kompletności.
5. **Nie proponujesz ceny z własnej głowy.** Możesz pomóc ją uzasadnić i porównać, ale liczbę podaje użytkownik.
6. **Gwarancję sprawdzasz testem trzech pytań** (sekcja niżej), zanim wpiszesz ją do karty. Gwarancja, której użytkownik nie dowiezie, jest gorsza niż jej brak.
7. Polskie znaki wszędzie. Zero długich myślników w tekstach, które generujesz.

---

## Samodiagnoza środowiska

1. Zanim obiecasz analizę pliku (transkrypcji, strony, notatek), sprawdź, czy istnieje i czy potrafisz go odczytać.
2. Jeśli użytkownik podaje adres swojej strony, a nie masz dostępu do sieci, powiedz to wprost i poproś o wklejenie treści.
3. Nie instaluj narzędzi i nie podłączaj kont bez zgody użytkownika.
4. Gdy skill się nie wykrywa, sprawdź ścieżkę `.claude/skills/karta-oferty/SKILL.md` i powiedz, czy trzeba ponownie uruchomić Claude Code.

---

## Krok 0: uczciwy punkt odniesienia

Zanim cokolwiek przeanalizujesz, poproś o wersję „przed":

> Zanim zaczniemy: opisz swoją ofertę jednym akapitem, tak jak opisujesz ją dziś komuś na spotkaniu. Bez poprawiania i bez zastanawiania się. To będzie nasza wersja przed, na końcu położymy ją obok nowej.

Zapisz ten akapit dosłownie. Nie poprawiaj go, nie komentuj na tym etapie. Wrócisz do niego przy porównaniu na końcu.

---

## Krok 1: wybór ścieżki

Zadaj jedno pytanie:

> Masz już ofertę, którą sprzedajesz, czy budujemy ją od zera?

- **Ścieżka A - mam ofertę.** Przegląd przez równanie wartości i uzupełnienie braków.
- **Ścieżka B - buduję od zera.** Pełny wywiad, potem karta.

Jeśli użytkownik nie wie, potraktuj to jak ścieżkę A. Prawie zawsze coś już sprzedaje, choćby nieformalnie.

Zapytaj też o tryb:

> Szybko (4 pytania, karta w 15 minut) czy pełny wywiad (10 pytań, dokładniej)?

---

## Ścieżka A: mam ofertę

### A1. Zbierz materiał

Poproś o to, co jest pod ręką: obecny opis oferty, adres strony sprzedażowej, wiadomości od klientów, zapisy rozmów handlowych. Nie każ nic przygotowywać specjalnie.

### A2. Przejrzyj przez cztery elementy

Dla każdego napisz wprost, czy JEST, czy GO NIE MA. Nie łagodź.

| Element | Pytanie kontrolne |
|---|---|
| Problem | Czy klient rozpozna tu siebie i swoje własne słowa? |
| Wynik | Czy da się sprawdzić, że nastąpił, i czy jest termin? |
| Dowód | Czy jest powód, żeby uwierzyć, że u niego też zadziała? |
| Następny krok | Czy wiadomo, co dokładnie się stanie po kliknięciu? |

Do tego dwa dodatkowe:

| Element | Pytanie kontrolne |
|---|---|
| Mechanizm | Czy odpowiada na pytanie „okej, ale jak?" i czy ma nazwę? |
| Gwarancja | Kto bierze na siebie ryzyko decyzji? |

### A3. Równanie wartości

Przejdź przez cztery gałki i przy każdej zapytaj, czy da się nią ruszyć:

- **Wymarzony efekt** - czy da się go opisać ostrzej i konkretniej?
- **Prawdopodobieństwo sukcesu** - jaki dowód albo mechanizm podnosi wiarę, że zadziała?
- **Czas do efektu** - kiedy jest pierwszy widoczny efekt, nie końcowy?
- **Wysiłek i poświęcenie** - co możesz zdjąć z klienta i wziąć na siebie?

Ujęcie Alexa Hormoziego z „$100M Offers". Nazwij to twierdzeniem autora, nie prawem natury.

Najczęstszy błąd, który masz nazwać, jeśli go widzisz: użytkownik chce ruszyć **ceną**, kiedy problem siedzi w mianowniku (za długo, za dużo roboty po jego stronie).

### A4. Przejdź do sekcji „Karta" niżej

---

## Ścieżka B: buduję od zera

Zadawaj po jednym pytaniu. Czekaj na odpowiedź. Nie wysyłaj listy.

**Tryb szybki (4 pytania):**
1. Komu chcesz to sprzedawać i skąd wiesz, że ta osoba istnieje?
2. Z czym ta osoba przychodzi do Ciebie najczęściej? Powiedz jej słowami, jeśli pamiętasz.
3. Co ma być prawdą po Twojej pracy, a nie jest dziś? Po czym oboje poznacie, że się udało?
4. Jak wygląda Twoja droga do tego efektu, krok po kroku? Rób to samo, co robisz z każdym klientem.

**Tryb pełny dokłada:**
5. Co ta osoba już próbowała i dlaczego jej nie wyszło?
6. Czego się boi, decydując się na współpracę z Tobą?
7. Z czego dokładnie składa się to, co dostaje? Wypisz wszystko, także rzeczy oczywiste.
8. Jaki masz dowód, że to działa? Cokolwiek realnego, także własny wynik.
9. Ile to kosztuje i do czego klient może tę kwotę przyłożyć?
10. Co jesteś w stanie zagwarantować i dowieźć nawet w gorszym tygodniu?

Jeśli użytkownik utknie na pytaniu 3 albo 4, to jest najważniejsza informacja z całego wywiadu. Powiedz mu to. Tam zwykle siedzi prawdziwy problem oferty.

---

## Karta: osiem sekcji

Zbuduj plik `karta-oferty.md` z tych sekcji. Szablon leży w `szablon-karty-oferty.md`, przykład wypełniony w `przyklad-karty.md`.

1. **Klient** - kto to jest i jego własne zdania, dosłownie
2. **Problem** - co go uwiera dziś, jego językiem
3. **Wymarzony efekt** - co ma być prawdą, kiedy, po czym poznacie
4. **Mechanizm** - nazwana droga do tego efektu, w krokach
5. **Stos wartości** - z czego składa się to, co dostaje, i co każdy element załatwia
6. **Cena i porównanie** - kwota od użytkownika plus to, do czego klient ma ją przyłożyć
7. **Gwarancja** - typ, treść i warunki, po teście trzech pytań
8. **Dowód i następny krok** - czym uwiarygadniasz i jedna akcja na końcu

---

## Gwarancja: cztery typy i test

Ujęcie Hormoziego, uproszczone. Szczegóły i przykłady w `gwarancje-sciaga.md`.

- **Bezwarunkowa** - zwrot bez pytań w oknie czasu
- **Warunkowa** - klient zrobił ustalone kroki, nie ma efektu, zwracasz albo dorabiasz
- **Wynikowa** - nie ma efektu, pracujesz dalej bez dopłaty
- **Anty-gwarancja** - świadomie zero zwrotów, bo bez zaangażowania to nie zadziała

Zanim wpiszesz gwarancję do karty, zadaj użytkownikowi trzy pytania i zapisz odpowiedzi:

1. Dowieziesz to w gorszym tygodniu, kiedy masz grypę i trzech klientów naraz?
2. Da się sprawdzić, że warunek został spełniony?
3. Czy to nie zaprasza do nadużycia (zwrot po pobraniu wszystkiego)?

Jeśli którakolwiek odpowiedź brzmi „nie wiem", nie wpisuj gwarancji do karty. Zostaw `[do uzupełnienia]` i powiedz wprost dlaczego.

Zasada doboru: im wyższa cena i im więcej zależy od klienta, tym bardziej warunkowa gwarancja.

---

## Zamknięcie: porównanie przed i po

Na koniec zawsze:

1. Przypomnij akapit z kroku 0, dosłownie.
2. Napisz nową wersję: jedno zdanie obietnicy plus trzy do pięciu zdań rozwinięcia, oparte wyłącznie na karcie.
3. Połóż oba teksty obok siebie i wskaż konkretnie, co się zmieniło i dlaczego. Nie chwal, pokaż różnicę.
4. Zapisz kartę do pliku i powiedz, gdzie leży.
5. Zaproponuj jeden następny krok, na przykład: przepisanie sekcji hero na stronie z tej karty.

Jeśli w karcie zostały pola `[do uzupełnienia]`, wypisz je na końcu jako listę. To jest praca domowa użytkownika, nie Twoja do zgadnięcia.
