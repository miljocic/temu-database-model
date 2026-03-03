# Temu - Database Design Project

Relational database model for a Temu-style e-commerce platform, covering the full lifecycle of a marketplace: products, sellers, orders, delivery, promotions, inspections, and penalties.

---

## Tool

Designed using **Oracle SQL Data Modeler**, with three levels of modeling:

| Model | Description |
|-------|-------------|
| **Logical Model** | Entities, attributes, and relationships |
| **Relational Model** | Tables, columns, primary and foreign keys |
| **Process Model** | Business process flows |

Open `Temu.dmd` directly in Oracle SQL Data Modeler.

---

## Domain Overview

**Users & People**
`Osoba`, `Korisnik`, `Zaposleni`, `Pol`, `Grad`, `Drzava`, `Lokacija`

**Products & Catalog**
`Proizvod`, `Kategorija`, `Potkategorija`, `Tag`, `Cena`, `Merna jedinica`

**Orders & Delivery**
`Porudzbina`, `Isporuka Porudzbine`, `Slanje porudzbine`, `Distributivni Centar`, `Kurirska Sluzba`, `Skladiste`

**Sellers & Partners**
`Partnerska Firma`, `Prodavnica`, `Carina`, `Pravilo uvoza`

**Promotions**
`Promocija`, `Reklama`, `Popust`, `Tip popusta`

**Compliance & Penalties**
`Inspekcija`, `Rezultati Inspekcije`, `Zalbe i Reklamacije`, `Kazna`, `Ban Firme`, `Suspenzija Firme`, `Novcana Kazna za Firmu`

---

## Files

| File | Description |
|------|-------------|
| `Temu.dmd` | Oracle Data Modeler project file (open this) |
| `Temu/` | Model directory — logical, relational, process, and datatype models |
| `Nedelja 12.pdf` | Project documentation |

---

## Authors
Milica Jocic, Anastasija Jovanocic, Milos Ivkovic - RAF, 2024/25
