# El doble intèrpret de JSBach

Documentació de la practica de LP del Quadrimestre de primavera de 2021-2022

## Requeriments

Per poder executar jsbach i generar tots els fitxers de forma correcta abans hem de fer les seguents instalacions:

```bash
sudo apt-get update -y
sudo apt-get install -y lilypond
sudo apt install timidity
sudo apt install ffmpeg
```
Seguidament per poder generar tots els arxius asociats a l'antlr4 haurem d'executar
```bash
antlr4 -Dlanguage=Python3 -no-listener -visitor jsbach.g
```

## jsbach.py

Si el que volem és executar el nostre programa comensant pel procediment per defecte (Main) haurem d'usar la seguent comanda:
```bash
python3 jsbach.py programa.jsb

```
Si el que volem és executar el nostre programa comensant per un altre procediment haurem d'usar la seguent comanda:
```bash
python3 jsbach.py programa.jsb Procediment
```

## Tests

També he afegit els jocs de proves **test-*.jsbper** que apareixen a la documentació original [https://github.com/valubach/README/blob/main/README.md].



## Autor
Valentí Ubach Martínez
valenti.ubach@estudiantat.upc.edu
