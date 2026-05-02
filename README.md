# Dziennik Tradera

Osobisty dziennik tradera z kalendarzem, statystykami i synchronizacją w chmurze.

## Pliki
- `index.html` — główna aplikacja
- `manifest.json` — konfiguracja PWA
- `sw.js` — service worker (offline)
- `icon-192.png` / `icon-512.png` — ikony aplikacji

## Jak wdrożyć na Vercel (krok po kroku)

### 1. GitHub
1. Wejdź na github.com i zaloguj się
2. Kliknij **"New repository"** (zielony przycisk)
3. Nazwa: `dziennik-tradera`
4. Kliknij **"Create repository"**
5. Na stronie repozytorium kliknij **"uploading an existing file"**
6. Przeciągnij WSZYSTKIE pliki z tego folderu
7. Kliknij **"Commit changes"**

### 2. Vercel
1. Wejdź na vercel.com
2. Kliknij **"Sign up"** → zaloguj się przez GitHub
3. Kliknij **"Add New Project"**
4. Wybierz repozytorium `dziennik-tradera`
5. Kliknij **"Deploy"**
6. Po chwili dostaniesz link np. `dziennik-tradera.vercel.app` — to Twoja strona!

### 3. Firebase — włącz logowanie emailem
1. W Firebase Console wejdź w **Authentication** → **Sign-in method**
2. Kliknij **Email/Password** → włącz → Save

## Używanie
- Otwórz link z Vercel w przeglądarce
- Zarejestruj konto emailem i hasłem
- Na telefonie: otwórz w Chrome → menu (⋮) → "Dodaj do ekranu głównego"
- Masz apkę na telefonie! Dane synchronizują się między urządzeniami.
