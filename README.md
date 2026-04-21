# inktime_tsc

# Proiect TSC – Inktime

## Descriere

Acest proiect constă în proiectarea unei plăci de circuit imprimat (PCB) pentru un dispozitiv wearable, realizată în cadrul cursului TSC.

Au fost parcurse toate etapele principale:
- realizarea schemei electrice
- plasarea componentelor pe placă
- rutarea conexiunilor
- verificarea DRC
- vizualizarea 3D

---

## Funcționalități

- proiectare schematică completă
- layout PCB pe mai multe straturi
- rutare semnale (manual + autoroute)
- interfață USB pentru alimentare și comunicare
- puncte de test pentru debugging (SWD, SDA, SCL)
- vizualizare 3D a plăcii

---

## Componente principale

- microcontroller (nRF52)
- conector USB
- regulator de tensiune
- condensatori de decuplare
- rezistențe SMD
- interfață SWD pentru programare/debug
- test points

---

## Design PCB

### Layout 2D
![PCB 2D](images/pcb_2d.png)

### Vizualizare 3D
![PCB 3D](images/pcb_3d.png)

---

## Tehnologii utilizate

- Autodesk Fusion (Electronics)
- schematic capture
- PCB layout
- autorouting și rutare manuală
- modelare 3D

---

## Considerații de proiectare

- componentele au fost grupate funcțional (RF, alimentare, interfețe)
- traseele au fost optimizate pentru lungime și claritate
- plan de masă (GND) utilizat pentru stabilitate
- condensatorii de decuplare plasați aproape de pini
- conectorii plasați pe marginea plăcii pentru acces facil

---

## Limitări

- există erori DRC minore (clearance / overlap)
- rutarea nu este complet optimizată
- necesită ajustări suplimentare pentru producție

---

## Structura repository-ului

- `/images` – imagini cu PCB (2D și 3D)
- fișiere Fusion – schematic + PCB + 3D
