# Instal·lació de tot • El meu camí

- `Descarrego Windows` (faré servir *Win10_21H2_Spanish_x64.iso*)
- `Preparo l'USB bootable` (per fer-ho, utilitzo [Rufus](https://rufus.ie); o, millor encara, [Ventoy](https://github.com/ventoy/Ventoy/releases))
- `Instal·lo Windows` en un disc dur buit (**quan *el sistema es reinicia*; extrec l'USB** i s'acaba la instal·lació)
- `Activo Windows` (seguint les instruccions del vídeo que millor pinta faci, buscant *activar Windows 10 CMD* a [YouTube](https://youtube.com/results?search_query=activar+windows+10+cmd))
- `Reinicio Windows` (per aplicar canvis després d'haver-lo activat)
- `Instal·lo les actualitzacions` (totes les que m'ofereixin, també les opcionals, del *Windows Update*)
- `Reinicio Windows` (per acabar d'instal·lar totes les actualitzacions)
- `Obro Windows PowerShell` (com a administrado, per executar *Windows Toolbox - [Chris Titus Tech](https://github.com/ChrisTitusTech/win10script)*)
  - `Copio al PowerShell` ` **iwr -useb https://git.io/JJ8R4 | iex** `
  - De la primera columna, `instal·lo el software`: `Windows Terminal`, `PowerToys`, `7-Zip`, `Discord`, `Github Desktop`, `Translucent Taskbar`, `Advanced IP Scanner`, `Everything Search`, `Firefox`, `Google Chrome`, `ShareX (Screenshots)`, `ImageGlass (Image Viewer)`, `GIMP (Image Editor)`, `VLC`, `VS Code`, `Notepad++`, `Adobe Reader DC` i `SumatraPDF`.
- Quan acabo d'instal·lar tot el que vull, deixo el `Windows Toolbox` en *stand-by*.
- Vaig a [Ninite](https://ninite.com).
  - Trio `Steam`, `FileZilla`, `HandBrake`, tot el que hi ha a l'apartat `Runtimes`, `qBittorrent`, `Inkscape` i m'ho descarrego.
  - Instal·lo l'executable que la pàgina em torna quan ja he triat tot.
- Torno al `Windows Toolbox`.
  - De la segona columna per l'esquerra, `SYSTEM TWEAKS`, faig clic a `Essential Tweaks` i, quan acaba el procés, clico `Disable Action Center`.
- **Reinicio el sistema** per aplicar canvis.
- Torno a executar l'script `iwr -useb https://git.io/JJ8R4 | iex` des de la `Terminal` per obrir el `Windows Toolbox` un altre cop.
