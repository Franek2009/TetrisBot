# 🧠 AI Tetris Pro Demo

**AI Tetris Pro** to przeglądarkowa implementacja klasycznej gry Tetris z wbudowaną sztuczną inteligencją analizującą planszę i automatycznie podejmującą optymalne decyzje.

Projekt został napisany w **czystym HTML, CSS i JavaScript**, bez żadnych zewnętrznych bibliotek.  
Całość działa bez instalacji – wystarczy otworzyć plik w przeglądarce.

AI analizuje możliwe pozycje dla każdego klocka, ocenia stan planszy i wybiera najlepszy ruch na podstawie heurystyk stosowanych w botach Tetris.

---

# 🎮 Demo funkcjonalności

Projekt zawiera:

- 🤖 **Auto Play (AI)** – sztuczna inteligencja gra sama
- 🧠 **System analizy planszy** – AI ocenia wiele możliwych ruchów
- 👻 **Ghost Piece** – podgląd miejsca lądowania klocka
- 📊 **Statystyki gry**
  - liczba użytych klocków
  - średnia liczba linii na klocek
  - czas przetrwania
- 🎛 **Kontrola prędkości gry**
- 📈 **Tryb analizy AI** – wizualizacja wszystkich rozważanych ruchów
- 🔄 **System 7-bag** (taki jak w nowoczesnych wersjach Tetrisa)

---

# 🧠 Jak działa AI

Sztuczna inteligencja analizuje każdą możliwą pozycję dla aktualnego klocka:

1. obraca klocek
2. przesuwa go w każdą możliwą kolumnę
3. symuluje spadanie
4. ocenia wynikową planszę

Ocena planszy opiera się na kilku czynnikach:

- wysokość kolumn
- liczba dziur
- nierówność powierzchni (bumpiness)
- liczba wyczyszczonych linii
- głębokość studni (wells)
- liczba przejść między pustymi i pełnymi polami

Każdy z tych elementów ma przypisaną wagę, a wynik końcowy decyduje o wyborze najlepszego ruchu.

---

# 🚀 Uruchomienie projektu

Nie jest wymagany żaden build ani instalacja.

### 1️⃣ Pobierz repozytorium

```bash
git clone https://github.com/TWOJ_LOGIN/ai-tetris-pro.git
```

### 2️⃣ Wejdź do folderu

```bash
cd ai-tetris-pro
```

### 3️⃣ Otwórz plik

Otwórz w przeglądarce:

```
tetris.html
```

Możesz też uruchomić lokalny serwer (opcjonalnie):

```bash
python -m http.server
```

a następnie wejść na:

```
http://localhost:8000
```

---

# 🎛 Sterowanie

| Przycisk | Funkcja |
|--------|--------|
| **AUTO PLAY** | włącza / wyłącza AI |
| **SHOW ANALYSIS** | pokazuje wszystkie analizowane ruchy |
| **RESTART GAME** | restart gry |
| **Game Speed** | prędkość spadania klocków |
| **Speed Multiplier** | mnożnik prędkości animacji |

---

# 📊 Statystyki

Panel statystyk pokazuje:

- **Pieces Survived** – ile klocków zostało użytych
- **Avg Lines/Piece** – średnia liczba linii na klocek
- **Time Alive** – czas przetrwania gry

---

# 🛠 Technologie

Projekt został napisany w:

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Canvas API**

Bez użycia:

- frameworków
- bibliotek
- silników gier

Dzięki temu kod jest łatwy do analizy i rozwijania.

---

# 📁 Struktura projektu

```
ai-tetris-pro
│
├── tetris.html
└── README.md
```

Cała logika gry, AI i renderowania znajduje się w jednym pliku.

---

# 👤 Autor projektu

Projekt został przygotowany przez **Kontrabasistę**.

Kontrabasista interesuje się:

- programowaniem
- sztuczną inteligencją
- analizą systemów
- cyberbezpieczeństwem
- projektowaniem własnych narzędzi i eksperymentów technologicznych

AI Tetris Pro jest jednym z projektów eksplorujących:

- podejmowanie decyzji przez algorytmy
- analizę heurystyczną
- wizualizację działania sztucznej inteligencji w czasie rzeczywistym.

---

# 🔮 Możliwe rozszerzenia projektu

Przykładowe kierunki rozwoju:

- AI z **lookahead (2-3 klocki do przodu)**
- **reinforcement learning**
- tryb **manualnej gry klawiaturą**
- zapis rekordów (**localStorage**)
- leaderboard
- wizualizacja heurystyk AI
- trening AI na wielu grach jednocześnie

---

# 📜 Licencja

Projekt jest dostępny do celów edukacyjnych i eksperymentalnych.

Możesz go dowolnie:

- analizować
- modyfikować
- rozwijać

---

⭐ Jeśli projekt Ci się podoba — zostaw gwiazdkę na repozytorium.