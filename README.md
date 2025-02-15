# Music-Player
**Ziel:** Eine einfache Web-App, mit der Nutzer Songs hochladen, abspielen und Playlists verwalten können.
Tools:
https://react.dev/
https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API
https://tailwindcss.com/

---

## **1. Technologie-Stack**

- **Frontend:** React (Vite oder Create React App), Tailwind CSS
- **Audio API:** Web Audio API
- **Speicherung:** IndexedDB (lokale Speicherung)

---

## **2. Funktionen & Features**

### **Grundfunktionen** (MVP – Minimal Viable Product)

✅ **Song hochladen & abspielen** (lokale Dateien)  
✅ **Lautstärke, Play/Pause, Skip, Loop**  
✅ **Letzte Wiedergabe speichern (IndexedDB)**

### **Erweiterungen (Optional)**

🚀 **Equalizer mit Visualisierung (Canvas API)**  
🚀 **Drag & Drop für Playlists**  
🚀 **Dark Mode**  
🚀 **Cloud-Speicherung mit Firebase**

---

## **3. Projektstruktur (Ordner & Dateien)**

````
music-player/
├── node_modules/ 
│── public/                # Statische Dateien (Icons, Logo, etc.)
│── src/
│   ├── components/        # Wiederverwendbare Komponenten
│   │   ├── PlayerControls.jsx
│   │   ├── Progress.jsx
│   │   ├── ExtraControls.jsx
│   │   ├── Visualizer.jsx
|   |   ├── Volume.jsx
|   |   ├── SongImage.jsx
|   |   ├── SongDetails.jsx
│   ├── styles/
|   |   ├── PlayerControls.css
|   |   ├── Progress.css
|   |   ├── SongDetails.css
|   |   ├── Volume.css
│   ├── App.jsx
│   ├── main.jsx
|   ├── index.css
│── package.json
│── tailwind.config.js
│── index.html
│── README.md
````

---

## **4. Entwicklungsphasen & Meilensteine**

### **Phase 1 – Grundstruktur & Basisfunktionen**

✅ React-Projekt aufsetzen  
✅ UI-Design mit Tailwind CSS  
✅ Hochladen & Abspielen von Songs mit `FileReader`  
✅ IndexedDB für lokale Speicherung integrieren

### **Phase 2 –  Steuerung**

✅ Audio-Steuerung (Play, Pause, Skip, Loop, Lautstärke)  
✅ Letzte Wiedergabe speichern

### **Phase 3 – Erweiterungen & Feinschliff

✅ Equalizer mit Web Audio API  
✅ Drag & Drop für Playlists  
✅ Mobile-Optimierung & Dark Mode  

---

## **5. Aufgabenteilung für 3 Personen**

Noch nicht sicher
