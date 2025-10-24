# Quiz o Cyberbezpieczeństwie i Płatnościach Online

Prosty, statyczny quiz stworzony w HTML + JavaScript + JSON.  
Nie zapisuje żadnych odpowiedzi — wszystko działa lokalnie w przeglądarce.

## 🔧 Struktura

```
quiz-cyber/
├── index.html
├── questions.json
└── README.md
```

## 🚀 Uruchomienie lokalne

1. Pobierz projekt jako ZIP lub sklonuj repozytorium.
2. Otwórz plik `index.html` w przeglądarce.
3. Quiz powinien działać od razu.

## 🌐 Publikacja online

### GitHub Pages
1. Utwórz nowe repozytorium na GitHubie (np. `quiz-cyber`).
2. Wgraj powyższe pliki do repozytorium.
3. W ustawieniach (`Settings → Pages`) wybierz branch `main` i folder `/ (root)`.
4. Po kilku minutach quiz będzie dostępny pod adresem  
   `https://twoja-nazwa.github.io/quiz-cyber/`.

### Netlify
1. Zaloguj się na [netlify.com](https://www.netlify.com/).
2. Połącz swoje repozytorium.
3. Kliknij **Deploy site** – gotowe!

## ✏️ Edycja pytań
Wszystkie pytania znajdują się w pliku `questions.json`.  
Każdy wpis zawiera:
```json
{
  "id": "q1",
  "q": "Treść pytania",
  "choices": ["A", "B", "C"],
  "correct": 1,
  "explanation": "Krótki komentarz"
}
```
Po zapisaniu zmian odśwież stronę, aby wczytać nowe pytania.

---

© 2025 – Edukacyjny quiz o cyberbezpieczeństwie (CC BY-NC)
