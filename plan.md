# BUSIA — Plan implementacji

Plan podzielony na dwa główne etapy. Dopóki Etap 1 nie będzie zaakceptowany, nie przechodzimy do Etapu 2.

---

# ETAP 1: Wygląd i projekt strony

Cel: zaprojektować stronę wizualnie, przejrzeć warianty, nanieść poprawki i zaakceptować finalny wygląd.

## Faza 1.1: Przygotowanie materiałów wizualnych

**Co trzeba mieć przed projektowaniem:**

- [ ] **Joanna:** Zdjęcie okładki książki telefonem (najlepiej na neutralnym tle, w dobrym świetle)
- [ ] **Joanna:** Zdjęcie autorki (mamy) — lub decyzja, że sekcja będzie bez zdjęcia

**Co zrobię ja (Claude):**
- Wybór najlepszych zdjęć z 142 dostępnych do poszczególnych sekcji
- Wybór i propozycja 3-4 screenów z FB (z zamazanymi nazwiskami)
- Przygotowanie mockupu okładki (jeśli nie będzie gotowego zdjęcia)

## Faza 1.2: Pięć wersji projektu graficznego

Zbuduję 5 działających wersji landing page'a do obejrzenia w przeglądarce. Każda z innym podejściem, układem sekcji i paletą kolorów. Przyciski "Zamów" będą na stronie, ale bez podłączonych płatności.

### Wersja 1 — Storytellingowa
- **Podejście:** Narracja, która wciąga krok po kroku. Zaczyna od emocjonalnego cytatu, historia odkrywa się stopniowo podczas scrollowania.
- **Kolejność sekcji:** Cytat otwierający → Fragment książki → O książce → Jak powstała → Głosy czytelników → O autorce → Zakup
- **Paleta:** Ciepła sepia/kremowa — jak kartki starego albumu fotograficznego
- **Layout:** Sekcje płynnie przechodzą jedna w drugą, duże zdjęcia, dużo przestrzeni

### Wersja 2 — Sprzedażowa
- **Podejście:** Od razu produkt i CTA. Jasna oferta, prominentne ceny, krótkie teksty, silne wezwania do działania.
- **Kolejność sekcji:** Okładka + CTA → Social proof (skrót) → O książce (skrót) → Zakup → Fragment → Stopka
- **Paleta:** Elegancki burgund ze złotem — profesjonalna, jak antykwariat
- **Layout:** Dużo białej przestrzeni, karty produktu na pierwszym planie, mniej tekstu

### Wersja 3 — O książce
- **Podejście:** Zaczyna od dużej prezentacji samej książki — co to jest, o czym, dla kogo. Jak rozbudowana karta katalogowa.
- **Kolejność sekcji:** Prezentacja książki → Szczegóły (fabuła, bohaterowie) → Fragment → O autorce → Jak powstała → Głosy → Zakup
- **Paleta:** Ciemna oliwka z mosiądzem — jak stara biblioteka z drewnianymi regałami
- **Layout:** Duże bloki tekstu z towarzyszącymi zdjęciami, encyklopedyczny charakter

### Wersja 4 — Social proof
- **Podejście:** Zaczyna od screenów z Facebooka i liczb (1900 reakcji!). "Książka, o którą prosili czytelnicy" — dowód społeczny jako główny argument.
- **Kolejność sekcji:** Liczby + screeny z FB → Głosy czytelników → Jak powstała → O książce → Fragment → O autorce → Zakup
- **Paleta:** Ciepły ceglasty/terakota z kremem — autentyczność, jak kawiarnia
- **Layout:** Karuzela cytatów, screeny w ramkach, liczby wyeksponowane dużym fontem

### Wersja 5 — Historyczna
- **Podejście:** Mama jako wnuczka, która postanowiła napisać książkę o kobiecie z epoki — dwudziestolecie międzywojenne, wojna, powojnie. Kontekst historyczny na pierwszym planie.
- **Kolejność sekcji:** Kontekst epoki (daty, Warszawa) → O książce (na tle historii) → O autorce (więź wnuczka-babcia) → Fragment → Głosy → Zakup
- **Paleta:** Stalowy niebieskoszary ze srebrną patyną — archiwalny, muzealny
- **Layout:** Oś czasu, daty, fakty historyczne przeplatane osobistymi zdjęciami

### Wspólne elementy wszystkich wersji
- Te same teksty z briefu (dostosowane do kontekstu)
- Te same zdjęcia (ale różne w hero i sekcjach kluczowych)
- Responsywność (telefon + komputer)
- Przyciski CTA (bez płatności)
- Sekcja zakupu z kartami druk/PDF
- Stopka z kontaktem
- Fonty: eleganckie, szeryfowe nagłówki — żadnych zaokrąglonych ani odręcznych

### Porównanie po zbudowaniu

Po zbudowaniu 5 wersji przygotuję tabelę porównawczą:
1. **Odbiór ludzki** — na ile strona jest zrozumiała, angażująca, przejrzysta
2. **Szybkość i technika** — czas ładowania, wydajność, responsywność
3. **Trendy UI/UX** — zgodność z aktualnymi standardami projektowania
4. **Rekomendacja** — 2 najlepsze wersje do finalnego wyboru (biorąc pod uwagę cel: opowiedzieć o książce i sprzedać)

## Faza 1.3: Przegląd i feedback od Joanny

**Joanna przegląda 5 wersji, czyta porównanie, wybiera jedną lub wskazuje elementy z różnych wersji do połączenia.**

## Faza 1.4: Poprawki i finalizacja

Nanoszę poprawki na wybraną wersję (lub łączę elementy z kilku), aż Joanna będzie zadowolona.

## Faza 1.5: Akceptacja wyglądu

**Joanna potwierdza: "Wygląd OK, możemy iść dalej."**

Dopiero wtedy przechodzimy do Etapu 2.

---

# ETAP 2: Elementy techniczne

Cel: podłączyć płatności, hosting, domenę i uruchomić stronę publicznie.

## Faza 2.1: Przygotowanie (wymaga działań Joanny i mamy)

- [ ] **Joanna:** Decyzja o domenie i zakup (~60 zł/rok)
- [ ] **Joanna:** Ustalenie kosztów wysyłki (InPost Paczkomaty, kurier)
- [ ] **Mama:** Założenie konta Stripe (dane osobowe: imię, nazwisko, PESEL, nr konta bankowego) — weryfikacja 1-2 dni robocze
- [ ] **Joanna:** Regulamin sprzedaży i polityka prywatności (mogę pomóc wygenerować szablon)

## Faza 2.2: Integracja płatności (Stripe)

1. Konfiguracja produktów w Stripe (książka druk + PDF, ceny w PLN)
2. Konfiguracja kosztów wysyłki (InPost, kurier)
3. Włączenie BLIK i polskich metod płatności
4. Podpięcie przycisków "Zamów" do Stripe Checkout
5. Strona sukcesu ("Dziękujemy za zakup!")
6. Automatyczne emaile:
   - Do klienta: potwierdzenie + link do PDF (dla wariantu cyfrowego)
   - Do mamy: powiadomienie o zamówieniu + dane do wysyłki (dla druku)

## Faza 2.3: Hosting i domena

1. Wrzucenie strony na hosting (Netlify — darmowy)
2. Podłączenie domeny
3. Certyfikat SSL (automatyczny — strona będzie miała "kłódkę" w przeglądarce)

## Faza 2.4: Optymalizacja i SEO

1. Optymalizacja szybkości ładowania (cel: < 3 sekundy na telefonie)
2. SEO: meta tagi, Open Graph (ładny podgląd przy udostępnianiu na FB)
3. Podłączenie analityki (ile osób odwiedza stronę, skąd przychodzą)

## Faza 2.5: Testy i uruchomienie

1. Test zakupu w trybie testowym (żadne prawdziwe pieniądze)
2. Testy na telefonach (Safari iOS, Chrome Android)
3. Testy na komputerze
4. Sprawdzenie regulaminu i polityki prywatności
5. Przełączenie Stripe na tryb produkcyjny
6. **Publikacja!**

---

# Informacje techniczne (referencja)

## Stack technologiczny

| Narzędzie | Do czego | Koszt |
|---|---|---|
| **Astro** | Budowa strony (automatycznie zmniejsza zdjęcia, ultraszybkie strony) | 0 zł |
| **Netlify** | Hosting strony + obsługa płatności w tle | 0 zł |
| **Stripe Checkout** | Płatności (BLIK, karty, przelewy) | ~2.50 zł/transakcję |
| **Resend** | Automatyczne emaile po zakupie | 0 zł (do 3000/mies.) |
| **Plausible** | Statystyki odwiedzin (zgodne z RODO) | 0 zł |
| **Domena .pl** | Adres strony | ~60 zł/rok |

**Łączny koszt miesięczny: ~5 zł** + prowizja Stripe od każdej sprzedaży.

## Struktura projektu

```
busia/
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro          -- szkielet strony
│   ├── pages/
│   │   ├── index.astro                -- landing page (wszystkie sekcje)
│   │   ├── sukces.astro               -- strona po płatności
│   │   ├── regulamin.astro            -- regulamin sprzedaży
│   │   └── polityka-prywatnosci.astro -- polityka prywatności
│   ├── components/                    -- poszczególne sekcje strony
│   │   ├── Navigation.astro
│   │   ├── Hero.astro
│   │   ├── About.astro
│   │   ├── Origin.astro
│   │   ├── Testimonials.astro
│   │   ├── Author.astro
│   │   ├── Excerpt.astro
│   │   ├── Product.astro
│   │   ├── Footer.astro
│   │   └── CTAButton.astro
│   ├── styles/
│   │   └── global.css                 -- kolory, czcionki, style
│   ├── data/
│   │   ├── testimonials.json          -- cytaty czytelników
│   │   └── product.json               -- ceny i warianty
│   └── assets/images/                 -- zdjęcia na stronie
├── public/
│   ├── fonts/                         -- czcionki
│   └── og-image.jpg                   -- obrazek do udostępniania na FB
├── netlify/functions/                 -- obsługa płatności (Etap 2)
│   ├── create-checkout.ts
│   └── stripe-webhook.ts
├── astro.config.mjs
├── package.json
└── netlify.toml
```

## Koszty utrzymania (po uruchomieniu)

| Element | Koszt |
|---|---|
| Hosting (Netlify) | 0 zł |
| Domena .pl | ~60 zł / rok |
| Stripe prowizja | ~2.50 zł / transakcję |
| Emaile (Resend) | 0 zł |
| Analityka (Plausible) | 0 zł |
| **Razem miesięcznie** | **~5 zł** + prowizje |

## Uwagi

### Dlaczego Astro a nie "zwykła strona HTML"?
Astro generuje taki sam HTML — ale automatycznie zmniejsza zdjęcia z 61 MB do ~5-8 MB. Bez tego strona ładowałaby się minutami na telefonie.

### Dlaczego Stripe a nie Przelewy24 / PayU?
Prostszy, tańszy (1.5% + 1 zł vs. 2.3% + 0.25 zł), obsługuje BLIK. Najlepsza opcja dla osoby fizycznej.

### Co jeśli nakład się wyczerpie?
Zmiana w jednym pliku (2 minuty) — usunięcie opcji "Druk", zostaje tylko PDF.

### Co z Facebookiem?
Strona zoptymalizowana pod udostępnianie na FB — ładny podgląd z okładką i opisem.
