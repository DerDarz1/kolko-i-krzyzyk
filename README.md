# ✕ ○ Kółko i Krzyżyk – Multiplayer

Gra dla 2 graczy przez internet. Bez rejestracji, bez serwera.

🌐 **Graj:** `https://TWOJA-NAZWA.github.io/NAZWA-REPO`

## Jak grać

1. Gracz 1 klika **Utwórz pokój** → dostaje 6-znakowy kod
2. Wysyła link znajomemu
3. Gracz 2 klika link lub wpisuje kod → **Dołącz**
4. Gra startuje automatycznie

## Technologia

- **PeerJS** (WebRTC peer-to-peer) — połączenie bezpośrednio między przeglądarkami
- Brak serwera, brak bazy danych
- Działa jako PWA (instalowalna na telefonie)

## Wrzucenie na GitHub

```bash
git init
git add .
git commit -m "init: kolko i krzyzyk multiplayer"
git branch -M main
git remote add origin https://github.com/TWOJA-NAZWA/NAZWA-REPO.git
git push -u origin main
```

Potem: **Settings → Pages → Source: GitHub Actions**
