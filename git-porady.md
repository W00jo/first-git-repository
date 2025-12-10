# GIT porady

To Twoja ściąga z obsługi GitHuba w projekcie gry. Używamy angielskich nazw = taki standard w game devie i ogólnie tego typu środowiskach :/

## Cykl pracy

### KROK 1: Start dnia

**Zanim otworzysz Godota:**

1. Otwórz **GitHub Desktop**.
2. Upewnij się, że jesteś na właściwym branchu (zazwyczaj `main` lub Twój `feature/...`).
3. Kliknij **Fetch origin** (Sprawdź, czy są nowości).
4. Jeśli pojawi się przycisk **Pull origin** – **KLIKAJ!**
    * *Dlaczego?* Musisz mieć najnowszą wersję gry, żeby nie nadpisać pracy kolegów.

### KROK 2: Działam

1. Rób swoje (koduj, rysuj, układaj poziom).
2. **Pro tip:** Jeśli robisz nową, dużą mechanikę (np. system ekwipunku), stwórz dla niej osobny **Branch**!

### KROK 3: Zapisywanie (Commit)

1. Wróć do GitHub Desktop.
2. Spójrz na listę **Changes** (po lewej).
    * Czy są tam tylko Twoje pliki?
    * Czy nie ma śmieci (temp, build)? Jeśli są: Prawy Przycisk Myszy -> **Ignore file**.
3. Zaznacz pliki (checkboxy).
4. Wpisz **Summary** (Tytuł Commita). Pamiętaj o angielskim i trybie rozkazującym:
    * ✅ `Add double jump logic`
    * ✅ `Fix player sprite glitch`
    * ❌ `poprawki`, `final version`, `asdasd`
5. Kliknij **Commit to...** (To Twój lokalny Save Point).

### KROK 4: Wysyłka (Push)

1. Kliknij **Push origin** (na górnej belce).
2. Dopiero teraz Twój zespół widzi zmiany.
    * *Zasada: Rób Push przynajmniej raz dziennie (przed wyłączeniem komputera)!*
