# Fizika Jegyzetek - PDF Megtekintő

Ez egy egyszerű HTML-alapú PDF megtekintő, amely kifejezetten a Fizika Jegyzetek projekt számára készült. A GitHub Pages szolgáltatáson keresztül teszi lehetővé PDF fájlok könnyű megtekintését és megosztását.

## 🌟 Funkciók

- **PDF megtekintés**: PDF fájlok megjelenítése közvetlenül a böngészőben
- **Responsive design**: Mobilon és asztalon egyaránt jól használható
- **Magyar nyelvű felület**: Teljesen magyar nyelvű kezelőfelület
- **Több betöltési mód**: Közvetlen és Google Viewer alapú betöltés
- **URL mentés**: A legutóbb használt URL automatikus mentése
- **Billentyűparancok**: Gyors használat billentyűkombinációkkal

## 📖 Használat

### 1. PDF URL megadása

Három módja van PDF fájlok betöltésének:

#### a) GitHub-on tárolt PDF fájlok
Ha a PDF fájl GitHub repository-ban van tárolva:
```
https://raw.githubusercontent.com/felhasználónév/repository-név/branch/útvonat/fájl.pdf
```

**Példa:**
```
https://raw.githubusercontent.com/20HDMI04/Fizika-Jegyzetek/main/notes/mechanika.pdf
```

#### b) Külső URL-ek
Bármilyen nyilvánosan elérhető PDF URL:
```
https://example.com/document.pdf
```

#### c) Google Drive megosztott fájlok
Google Drive-ból megosztott PDF fájlokhoz használd a következő formátumot:
```
https://drive.google.com/file/d/FÁJL_ID/view?usp=sharing
```

### 2. Betöltési módok

- **PDF Betöltése**: Automatikus kompatibilitás-ellenőrzéssel
- **Közvetlen betöltés**: PDF közvetlen megjelenítése iframe-ben
- **Új ablakban megnyitás**: PDF megnyitása új böngészőablakban

### 3. Billentyűparancsok

- `Ctrl+Enter` (vagy `Cmd+Enter` Mac-en): PDF betöltése
- `Ctrl+Backspace` (vagy `Cmd+Backspace` Mac-en): Megtekintő törlése
- `Enter` az URL mezőben: PDF betöltése

## 🔧 Testreszabás

### Saját PDF lista hozzáadása

A `sample-urls` szakaszban könnyen hozzáadhatsz saját PDF-eket:

```html
<a href="#" class="sample-url" onclick="loadSamplePDF('YOUR_PDF_URL')">
    PDF címe
</a>
```

### Stílus módosítása

A CSS könnyen testreszabható. A főbb színek és méretek a `:root` szelektorban vannak definiálva.

## 🚀 GitHub Pages telepítés

1. **Repository beállítása**:
   - Menj a repository Settings oldalára
   - Görgess le a "Pages" szekcióhoz
   - Válaszd ki a forrást: "Deploy from a branch"
   - Válaszd a "main" branch-et és "/ (root)" mappát
   - Mentsd el

2. **URL elérése**:
   A weboldal elérhető lesz a következő címen:
   ```
   https://felhasználónév.github.io/repository-név/
   ```

## 📱 Böngésző támogatás

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobil böngészők

## ⚠️ Fontos megjegyzések

- **CORS korlátozások**: Egyes PDF fájlok CORS beállításai miatt lehet, hogy nem töltődnek be közvetlenül
- **GitHub raw fájlok**: A legjobb kompatibilitás GitHub raw URL-ekkel érhető el
- **Fájlméret**: Nagy PDF fájlok esetén a betöltés hosszabb időt vehet igénybe
- **Mobil használat**: Kisebb képernyőkön a PDF olvashatósága korlátozottabb lehet

## 🤝 Hozzájárulás

Ha javítási javaslatod vagy új funkcióötleted van:

1. Fork-old a repository-t
2. Hozz létre egy új branch-et (`git checkout -b feature/új-funkció`)
3. Commitold a változásokat (`git commit -am 'Új funkció hozzáadása'`)
4. Push-old a branch-et (`git push origin feature/új-funkció`)
5. Nyiss egy Pull Request-et

## 📄 Licenc

Ez a projekt a MIT licenc alatt áll. Lásd a `LICENSE` fájlt a részletekért.

## 👤 Szerző

Készítette: 20HDMI04  
Repository: [Fizika-Jegyzetek](https://github.com/20HDMI04/Fizika-Jegyzetek)

---

**Jogi nyilatkozat**: A szerző nem vállal felelősséget a jegyzetekben található esetleges hibákért, hiányosságokért, vagy azok pontatlanságáért. A jegyzet használata a felhasználó saját felelősségére történik.