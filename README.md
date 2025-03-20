## Ez a MÁV utastájékoztató tanuló verziója

Induló és érkező vonatok
Ez a weboldal **HTML** és **CSS** sgítségével készült és egy táblázatot jelenít meg.

### 🔹Funkciók
- 🔺 Érkező és induló vonatok megjelenítése táblázatban
- 🔺 Érkezési és indulási idők és vágányszámok megmutatása
- 🔺 letisztult dizájn

### 🔹Használat
A projekt élőben megtekinthető a https://szabojuli642.github.io/2025_01_30_MAV_utastajekoztato/ linken.

### 🔹 Alap HTML szerkezet
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MÁV induló járatok</title>
    <link rel="stylesheet" href="indulo_vonatok.css">
</head>
```

### 🔹 Alap CSS szerkezet
```css
table{
  border:1px solid ;
  /* background-color: blue; */
  color: rgb(247, 247, 250); /* betűszín */
  font-family: 'Courier New';/* betűtípus */
  font-size: 30px;/* betűméret */
}
```

### 🔹 Fejlesztési lehetőségek
- ❎ valós idejű megjelenítés
- ✅ keresési lehetőségek