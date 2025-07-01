# WallpaperSync PowerShell Script

Wechselnde Windows-Wallpaper direkt aus Web-Links via PowerShell.

```powershell
<##
.SYNOPSIS
    Wechselnde Windows-Wallpaper direkt aus Web-URLs via PowerShell.
.DESCRIPTION
    Interaktive Abfrage von Bild-URLs und Wechsel-Intervall; lädt die Bilder herunter und setzt sie als Hintergrund.
#>

# 1) Anzahl der Links abfragen...
# (Der vollständige Code bleibt unverändert und wird hier der Übersicht halber weggelassen.)
```

---

# 📘 README / Anleitung

## 🇩🇪 Deutsch

### GhostDrop Network präsentiert
**WallpaperSync** – dein schlankes PowerShell‑Skript, um Desktop‑Hintergründe zyklisch aus Web‑Links zu wechseln.

#### Features
- **Interaktiv**: Eingabe beliebig vieler Bild‑URLs
- **Flexibles Intervall**: Von Sekunden bis Stunden
- **Automatische Temp‑Verwaltung**: Kein Chaos mit Ordnern
- **Open‑Source & Kostenlos** – by GhostDrop Network

#### Installation
1. **Script speichern**  
   Speichere `wallpaper_sync.ps1` in einem Ordner deiner Wahl.
2. **Execution Policy anpassen**  
   ```powershell
   Set-ExecutionPolicy Bypass -Scope CurrentUser
   ```
3. **Script ausführen**  
   ```powershell
   powershell.exe -WindowStyle Hidden -File C:\Pfad\zu\wallpaper_sync.ps1
   ```
4. **Autostart (optional)**  
   Erstelle eine Verknüpfung zu obigem Befehl in `%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup`.

#### Support / Problemmeldung
Falls es Probleme gibt, melde dich hier:  
https://discord.gg/GhostDrop

---

## 🇬🇧 English

### Presented by GhostDrop Network
**WallpaperSync** – your lightweight PowerShell script to cycle desktop wallpapers from web links.

#### Features
- **Interactive**: Enter any number of image URLs
- **Flexible Interval**: From seconds to hours
- **Automatic Temp‑File Handling**: No folder clutter
- **Open‑Source & Free** – by GhostDrop Network

#### Installation
1. **Save Script**  
   Save `wallpaper_sync.ps1` in a folder of your choice.
2. **Adjust Execution Policy**  
   ```powershell
   Set-ExecutionPolicy Bypass -Scope CurrentUser
   ```
3. **Run Script**  
   ```powershell
   powershell.exe -WindowStyle Hidden -File C:\Path\to\wallpaper_sync.ps1
   ```
4. **Autostart (optional)**  
   Create a shortcut to the above command in `%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup`.

#### Support / Report Issues
If you encounter any problems, report them here:  
https://discord.gg/GhostDrop

---

*Made with ❤️ by GhostDrop Network*
