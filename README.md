# To-Do Organizer

Aplikacja desktopowa / webowa służąca do zarządzania codziennymi zadaniami, planowania projektów oraz śledzenia postępów prac. Umożliwia organizację obowiązków z wykorzystaniem kategorii, priorytetów oraz precyzyjnych terminów wykonania.

## Skład zespołu
- Jakub Pawłowski (indeks: 170546) 
- Mateusz Mazur (indeks: 170579) 

## Wymagania funkcjonalne

1. **Tworzenie i edycja zadań**
   - Dodawanie nowych zadań z określeniem nazwy oraz opcjonalnego opisu tekstowego.
   - Możliwość modyfikacji parametrów i treści zadania w dowolnym momencie.

2. **Oznaczanie statusu realizacji**
   - Zmiana statusu zadania (np. Oczekujące, W trakcie, Ukończone).
   - Możliwość cofnięcia statusu ukończenia i przywrócenia zadania do realizacji.

3. **Kategoryzacja zadań (Etykiety/Projekty)**
   - Tworzenie, edycja oraz usuwanie własnych kategorii (np. Praca, Dom, Uczelnia).
   - Przypisywanie zadań do jednej lub wielu kategorii jednocześnie.

4. **Określanie priorytetów**
   - Nadawanie priorytetu zadaniu (np. Niski, Średni, Wysoki, Pilny).
   - Wizualne wyróżnienie pozycji na liście w zależności od wybranego poziomu ważności.

5. **Terminy realizacji (Due dates)**
   - Przypisywanie daty końcowej (deadline) oraz konkretnej godziny wykonania zadania.

6. **Filtrowanie zadań**
   - Zawężanie widoku listy według: kategorii, poziomu priorytetu, statusu realizacji oraz zakresu dat (np. „Dzisiaj”, „Ten tydzień”, „Przeterminowane”).

7. **Sortowanie listy zadań**
   - Sortowanie według terminu wykonania (rosnąco/malejąco), priorytetu (od najwyższego) oraz daty utworzenia lub alfabetycznie po tytule.

8. **Wyszukiwanie pełnotekstowe**
   - Wyszukiwanie zadań w czasie rzeczywistym na podstawie frazy kluczowej w tytułach i opisach.

9. **Usuwanie zadań i czyszczenie ukończonych**
   - Trwałe usuwanie pojedynczych pozycji.
   - Masowe usuwanie lub archiwizacja wszystkich zadań oznaczonych jako ukończone.

10. **Powiadomienia i alerty o zbliżających się terminach**
    - Generowanie powiadomień informujących o nadchodzących deadline'ach oraz o zadaniach przeterminowanych.

## Technologie
- **Język programowania:** Java (np. wersja 17 lub 21)
- **Framework / Warstwa wizualna:** JavaFX (aplikacja okienkowa) lub Spring Boot (aplikacja webowa)
- **Baza danych / Przechowywanie danych:** PostgreSQL / H2 Database / SQLite
- **Budowanie i zarządzanie zależnościami:** Maven lub Gradle
- **Kontrola wersji:** Git / GitHub
