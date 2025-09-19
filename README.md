# US Keyboardlayout for German
Adds Umlauts and more to US-Layout keyboards. Perfect for Germans with a US-Layout keyboard (US-ANSI or US-ISO).

## Key Assignments

### Lowercase Umlauts
| Key | Modifier | Character |
|-----|----------|-----------|
| A   | AltGr    | ä         |
| O   | AltGr    | ö         |
| U   | AltGr    | ü         |
| S   | AltGr    | ß         |

### Uppercase Umlauts
| Key | Modifier        | Character |
|-----|----------------|-----------|
| A   | Shift + AltGr   | Ä         |
| O   | Shift + AltGr   | Ö         |
| U   | Shift + AltGr   | Ü         |

### Euro & Other Special Characters
| Key       | Modifier | Character | Use             |
|-----------|----------|-----------|-----------------|
| , (comma) | AltGr    | «         | Left guillemet  |
| . (period)| AltGr    | »         | Right guillemet |
| 5         | AltGr    | €         | Euro sign       |

### Notes
- **AltGr = Right Alt (also Ctrl + Alt)**  
- **Shift + AltGr** → Uppercase umlauts  
- Regular Left Alt and Ctrl+Key combinations remain available for Windows shortcuts.  
- Dead keys are disabled → characters are entered immediately.

## Installation

1. Install Microsoft Keyboard Layout Creator (MSKLC)
2. Open the project or import the layout. (QWERTY+.klc file)  
3. Build → DLL and Setup Package.  
4. Run the installer as Administrator.  
(After installing the custom layout, you **must restart your PC** (or at least log out and back in) for the layout to appear in Windows.)
5. Windows 11: Settings → Time & Language → Language & Region → Add Keyboard → Select your custom layout.  
6. Use **Win + Space** to switch between layouts.

---

## License

This project is licensed under the **MIT License** – free to use, modify, and commercially distribute. See [LICENSE](LICENSE) for details.
