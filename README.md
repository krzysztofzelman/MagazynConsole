# Magazyn.Console

Samodzielna konsola magazynu: artykuły (CRUD), PZ/WZ FIFO. Wydzielona z projektu `Magazyn`
2026-11-16 — nie korzysta z API, tylko czyta bazę bezpośrednio.

## Uruchomienie

W Visual Studio: otwórz `MagazynConsole.slnx` → **Ctrl+F5**.

Z terminala:

```
cd "D:\Dane\Projekty\Nauka C#\MagazynConsole"
dotnet run
```

## Baza

Własna, osobna baza: `data\magazyn.db` (SQLite). Tabele `Przedmioty` i `Partie`
tworzą się automatycznie przy pierwszym starcie (albo są już utworzone).

Dane z tej konsoli **nie** są widoczne na stronie `MagazynWeb` — od podziału
(2026-11-16) każdy projekt ma swoją bazę.
