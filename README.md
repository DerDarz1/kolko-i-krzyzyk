# ✕ ○ Kółko i Krzyżyk – Multiplayer

Gra dla 2 graczy przez internet, oparta na **Firebase Realtime Database**.

🌐 **Graj:** `https://derdarz1.github.io/kolko-i-krzyzyk`

## Konfiguracja Firebase (jednorazowo, darmowe)

1. Wejdź na https://console.firebase.google.com
2. Kliknij **Add project** → nadaj nazwę np. `tkt-game` → utwórz
3. W projekcie kliknij **Realtime Database** → **Create database** → tryb **test mode**
4. Skopiuj URL bazy (np. `https://tkt-game-default-rtdb.firebaseio.com`)
5. Wejdź w **Project settings** (koło zębate) → **Your apps** → **Web app** → zarejestruj
6. Skopiuj obiekt `firebaseConfig`
7. W pliku `index.html` znajdź sekcję `firebaseConfig` i wklej swoje dane

## Wrzucenie na GitHub

```bash
git add .
git commit -m "update"
git push
```
