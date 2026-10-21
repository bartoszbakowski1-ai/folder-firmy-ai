# Folder firmy dla AI

Gotowy folder, w którym ChatGPT (Codex) i Claude mają tę samą wiedzę o Twojej firmie.
Materiał ze szkolenia „AI w codziennej pracy małej firmy” (WM:HTC, Olsztyn, 22.10.2026), prowadzący: [Bartek Bąkowski](https://bartbakowski.com).

## Co jest w środku

| Plik | Po co |
|---|---|
| `AGENTS.md` | Wiedza o firmie i zasady pracy AI. Czyta go ChatGPT i Codex |
| `CLAUDE.md` | Wczytuje `AGENTS.md`, więc Claude ma tę samą wiedzę |
| `komendy/start.md` | Co AI robi na hasło „start”: stan firmy, kalendarz, poczta, 3 priorytety |
| `komendy/koniec.md` | Co AI robi na hasło „koniec”: podsumowanie, aktualizacja stanu |
| `pamiec/STAN.md` | Co się teraz dzieje w firmie: priorytety, otwarte sprawy, decyzje |
| `sesje/` | Podsumowania rozmów, jeden plik na sesję |
| `.claude/commands/` | Komendy `/start` i `/koniec` w Claude Code |

## Jak zacząć

1. Pobierz: zielony przycisk **Code > Download ZIP** (albo **Use this template**, jeśli masz konto GitHub).
2. Rozpakuj w dowolnym miejscu, np. w Dokumentach.
3. Uzupełnij `AGENTS.md` (pola w nawiasach kwadratowych). Możesz wkleić instrukcje z kroku 2b szkolenia.
4. Otwórz folder w aplikacji Claude na komputerze, w Claude Code, w ChatGPT albo w Codex.
5. Na początku pracy napisz „start”, na końcu „koniec”.

Prompty ze szkolenia: https://bartbakowski.com/zasoby/ai-w-pracy

## Zasady pracy AI (wpisane w AGENTS.md)

- Niczego nie wysyła i nie publikuje. Maile tylko jako szkic do sprawdzenia.
- Zanim napisze, że coś jest zrobione, sprawdza to w źródle.
- Zaznacza, czego nie wie na pewno, i dopytuje.
- Hasła, numery kont i PESEL nie trafiają do AI.
