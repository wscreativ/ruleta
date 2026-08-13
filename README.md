# Leggance — Roata Norocului

Pagină statică (roata norocului / gamified discount wheel) pentru Leggance.

## Rulare locală

```bash
npm install
npm start
```

Aplicația pornește pe `http://localhost:3000` (sau pe portul din variabila `PORT`).

## Deploy pe Railway

Acest repo conține `package.json` + `railway.json`, deci Railway îl detectează
automat ca proiect Node (Nixpacks) și rulează `npm install && npm start`.

1. În Railway: **New Project → Deploy from GitHub repo** și selectează acest repo.
2. Railway generează automat un domeniu public (sau adaugă unul din
   Settings → Networking → Generate Domain).

## Editare conținut

Toate textele, premiile și codurile de reducere se editează în `index.html`,
în obiectul `CONFIG` din `<script>`.
