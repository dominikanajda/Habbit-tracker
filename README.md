# Habbit-tracker

**_Habit Tracker_** - aplikacja desktopowa w Pythonie do śledzenia codziennych nawyków w wybranym miesiącu. 
Pozwala na dodawanie własnych rutyn i codziennie odznaczanie ich na w tabeli. 
Aplikacja umożliwia podgląd statystyk z linią trendu. 

## Zawartość
1. **main.py** - uruchamia główne okno aplikacji
2. **app.py** - GUI - zawarte trzy widoki: Setup, Tablica, Statystyki
3. **models.py** - Klasy danych: Session, Day, HabitEntry, Habit
4. **storage.py** - zapis i odczyt stanu sesji do pliku data.json
5. **requirements.txt** - lista wymaganych bibliotek
6. **.gitignore** - pliki zignorowane przez Git.

## Wymagania
- Python 3.13 lub nowszy
- pip

## Instalacja i uruchomienie
1. Sklonuj repozytorium
2. Zainstaluj zależności:
   pip install -r requirements.txt
3. Uruchom aplikację
   python main.py

## Jak używać
1. Przy pierwszym uruchomieniu wypełnij formularz:
- wpisz nazwę sesji
- wybierz miesiąc i rok (obecny lub poprzedni)
- dodaj nawyki które chcesz śledzić (zasugerowane lub wpisz własne)
2. Kliknij START - otworzy się tabela z siatką nawyków i dniami wybranego miesiąca
3. Zaznaczaj checkboxy dla każdego minionego dnia
4. Kliknij _Statystyki_ aby zobaczyć wykres postępu
5. Kliknij _Reset_ aby rozpocząć nową sesję

## Funkcje 
+ Siatka nawyków - wiersze to nawyki, kolumny to dni miesiąca
+ Automatyczna liczba dni na podstawie wybranego miesiąca
+ Statystyki - wykres postępu
+ Reset sesji i tworzenie nowej

## Technologie
* Python 3.13+
* CustomTkinter - GUI
* Matplotlib - wykresy
* Numpy - linia trendu
