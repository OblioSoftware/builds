# Casa de marcat Debian / Ubuntu
Plugin-ul Oblio casa de marcat compatibil cu sistemul de operare linux x86 Debian / Ubuntu.

## Descarcare
```bash
wget https://obliosoftware.github.io/builds/casademarcat/debian/oblio-casademarcat.x86_64.deb
```

## Instalare
```bash
sudo dpkg -i ./oblio-casademarcat.deb
```
Adaugare user in grupul dialout, daca nu exista in acest grup sunt necesare privilegii de root.
```bash
sudo usermod -a -G dialout $USER
```

## Limitari
Momentan functioneaza doar cu casele Datecs

