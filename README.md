# Folder firmy dla AI

Gotowy folder, w którym ChatGPT (Codex) i Claude mają tę samą wiedzę o Twojej firmie.
Materiał ze szkolenia „AI w codziennej pracy małej firmy” (WM:HTC, Olsztyn, 22.10.2026), prowadzący: [Bartek Bąkowski](https://bartbakowski.com).

## Co jest w środku

| Plik | Po co |
|---|---|
| `AGENTS.md` | Wiedza o firmie, zasady pracy AI, hasła i lista skilli. Czyta go ChatGPT i Codex |
| `CLAUDE.md` | Wczytuje `AGENTS.md`, więc Claude ma tę samą wiedzę |
| `komendy/pierwsze-uruchomienie.md` | AI robi z Tobą wywiad i samo wypełnia `AGENTS.md` i `pamiec/STAN.md` |
| `komendy/start.md` | „start”: stan firmy, kalendarz, poczta, 3 priorytety |
| `komendy/workflow.md` | „workflow”: zapisuje powtarzalne zadanie jako plik w `workflowy/` |
| `komendy/koniec.md` | „koniec”: podsumowanie rozmowy i aktualizacja stanu |
| `pamiec/STAN.md` | Co się teraz dzieje w firmie |
| `workflowy/` | Twoje zadania rozpisane krok po kroku (szablon w środku) |
| `sesje/` | Podsumowania rozmów |
| `.claude/skills/` | Gotowe skille: karta głosu, karta oferty, teksty reklam Meta |
| `.claude/commands/` | Te same hasła jako `/start`, `/koniec` itd. w Claude Code |

Folder `.claude` jest ukryty. Na Macu pokażesz go w Finderze skrótem Cmd + Shift + kropka.

## Jak zacząć

1. Pobierz: zielony przycisk **Code > Download ZIP** (albo **Use this template**, jeśli masz konto GitHub).
2. Rozpakuj w dowolnym miejscu, np. w Dokumentach.
3. Otwórz folder w aplikacji Claude na komputerze, w Claude Code, w ChatGPT albo w Codex.
4. Napisz **pierwsze uruchomienie**. AI zrobi krótki wywiad i samo wypełni `AGENTS.md`.
5. Na co dzień: **start** na początku pracy, **workflow** gdy zadanie ma się powtarzać, **koniec** na końcu.

## Skille w paczce

| Skill | Co robi | Jak uruchomić |
|---|---|---|
| Karta głosu | Twój styl pisania z Twoich maili, nagrań albo postów, żeby AI pisało jak Ty | „zróbmy moją kartę głosu” |
| Karta oferty | Twoja oferta w jednym pliku: co, komu, za jaki efekt, za ile | „zróbmy kartę oferty” |
| Teksty reklam Meta | Reklamy na Facebooka i Instagrama po polsku, pod 5 poziomów świadomości klienta | „napisz reklamę dla [produkt]” |

Więcej skilli: https://bartbakowski.com/wiedza/skille-do-claude

## Zasady pracy AI (wpisane w AGENTS.md)

- Niczego nie wysyła i nie publikuje. Maile tylko jako szkic do sprawdzenia.
- Zanim napisze, że coś jest zrobione, sprawdza to w źródle.
- Zaznacza, czego nie wie na pewno, i dopytuje.
- Hasła, numery kont i PESEL nie trafiają do AI.
