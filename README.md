# GLF-Cikutra

## About

Cikutra is a expressive display type family available as a variable font from Thin to Black, featuring a retro-funky style with distinct personality. Its design pairs structured geometry with sharp inner ink traps and dynamic curved stems. Offering complete weight flexibility, the lighter styles deliver sleek, refined elegance, while the heavier weights provide a bold, experimental presence perfect for eye-catching display headlines, music artwork, event posters, and standout branding identities.

### Prerequisites
Make sure you have **Python 3.10 or higher** installed on your system.

### Installation
Open your terminal and install the required font engineering tools via pip:
```bash
pip install fontmake glyphsLib fontbakery[googlefonts] gftools
```

### Build Instructions
Run the following command to generate desktop-ready OpenType and TrueType fonts:
```bash
# Create destination directories
mkdir -p fonts/ttf fonts/otf

# Compile the .glyphs source file
fontmake -g sources/GLF_Cikutra.glyphs -o ttf --output-dir fonts/ttf/
fontmake -g sources/GLF_Cikutra.glyphs -o otf --output-dir fonts/otf/
```
The compiled files will appear inside the newly created `fonts/` directory.

## License
This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
https://openfontlicense.org

## Contributors
Sidiq Kamal Nurmawan <sidiq.nurmawan@gmail.com>
Erwin Wirianata <wirianata.erwin@gmail.com>
