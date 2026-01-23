
# Introducció al cas

Després del nostre assessorament, **TransLògic S.A.** ens encarrega el desplegament dels seus servidors **Windows Server 2025**.

Per aquest motiu, haurem de desplegar diverses màquines virtuals i, amb l’objectiu de ser eficients i seguir bones pràctiques, realitzarem una instal·lació de prova que servirà tant per aprendre els procediments com per elaborar una guia d’instal·lació, que ha de proporcionar una documentació de base a la posterior implantació als sistemes del client.

---

## Procediment

- **Crea una màquina virtual** amb:
  - **8 GB de RAM**
  - **Dos processadors**
  - **Dos discos**:
    - Principal: **32 GB** (on instal·lareu el SO)
    - Secundari: **10 GB**
  - **Dues interfícies de xarxa**:
    - Una en xarxa **NAT (no NAT)**
    - Segona en **host-only**

- **Instal·la Windows Server 2025** en mode **GUI**, idioma **US** però configuració i teclat en **espanyol**.

- **Canvia el nom de l’equip** a `DCxx` (on **xx** és el vostre número de llista).

- **Actualitza la màquina virtual** (un cop fet, **pausa les actualitzacions** tot el temps que sigui possible).

---

## Contingut de la guia

- **Compara la configuració de la màquina virtual** definida a l’apartat anterior amb els requisits indicats per Microsoft.  
  *Són coherents?*

- **Documenta els diversos procediments de la instal·lació** amb:
  - Captures de pantalla
  - Observacions

> Recorda que el format a utilitzar és **Markdown**.

A l'arxiu [solucio.md](solucio.md) esta la solució de la tasca04

[Torna a la pàgina principal](../README.md)
