# Instal·lació de tot • El meu camí

- Descarrego el Windows que més m'agradi.
  - Personalment, sudo del Windows 11; faré servir `Win10_21H2_Spanish_x64.ISO`.
- Instal·lo el Windows en un disc dur buit.
  - Jo utilitzo `Ventoy` o `Rufus` per fer *USBs bootables*.
- Activo el Windows.
  - Segueixo les instruccions del vídeo que millor pinta faci, buscant `activar Windows 10 CMD` a [YouTube](https://youtube.com/results?search_query=activar+windows+10+cmd).
  - Reinicio després d'haver activat Windows.
- Instal·lo *tota la merda* que m'ofereixin (també la opcional) al `Windows Update`.
  - Torno a reiniciar el sistema per acabar d'instal·lar totes les actualitzacions.
- Obro el `Windows PowerShell` (com a administrador) i executo `iwr -useb https://git.io/JJ8R4 | iex` (codi de [Chris Titus Tech](https://github.com/ChrisTitusTech/win10script)).
  - S'obre `Windows Toolbox By Chris Titus`.
  - De la primera columna per l'esquerra, `INSTALL`, instal·lo:
    - `Windows Terminal` (*pijadeta* que substituir el *PowerShell* i és més cmd/linux-style), `PowerToys` (bàsicament pel *Caffeine* i el *Color Picker*), `7-Zip`, `Discord`, `Github Desktop`, `Translucent Taskbar`, `Advanced IP Scanner`, `Everything Search`, `Firefox`, `Google Chrome`, `ShareX (Screenshots)`, `ImageGlass (Image Viewer)`, `GIMP (Image Editor)`, `VLC`, `VS Code`, `Notepad++`, `Adobe Reader DC` i `SumatraPDF`.
- Quan acabo d'instal·lar tot el que vull, deixo el `Windows Toolbox` en *stand-by*.
- Vaig a [Ninite](https://ninite.com).
  - Trio `Steam`, `FileZilla`, `HandBrake`, tot el que hi ha a l'apartat `Runtimes`, `qBittorrent`, `Inkscape` i m'ho descarrego.
  - Instal·lo l'executable que la pàgina em torna quan ja he triat tot.
- Torno al `Windows Toolbox`.
  - De la segona columna per l'esquerra, `SYSTEM TWEAKS`, faig clic a `Essential Tweaks` i, quan acaba el procés, faig clic a `Disable Action Center`.
  - Quan s'acabi el procés, reinicio el sistema per aplicar canvis.

Torno a executar l'script `iwr -useb https://git.io/JJ8R4 | iex` - `Windows Toolbox By Chris Titus`
