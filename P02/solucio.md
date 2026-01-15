
# P02: Llicenciament Windows Server 2025

---

## 1. Analitzar el model de llicenciament per nucli (core) de Windows Server 2025

- **Servidor físic:** 1 unitat  
- **Total nuclis:** 24 (2 processadors x 12 nuclis cadascun)  
- **Màquines virtuals:** 12  
- **Usuaris:** 45  

El **Windows Server 2025** es llicencia per **nuclis (cores)**.  
Cal llicenciar **tots els nuclis del servidor** i complir amb els mínims obligatoris:
- **8 nuclis per CPU** (mínim)
- Les llicències es venen en **packs**:
  - Pack de **16 nuclis**
  - Pack de **8 nuclis**
  - Pack de **2 nuclis**

---

  <img width="594" height="178" alt="image" src="https://github.com/user-attachments/assets/78e17e41-fd72-41d0-a104-2f30211367e1" />

---

> **Important:** Les llicències de nuclis **no inclouen CALs**.  
Les CALs són necessàries per a usuaris o dispositius que accedeixen a:
- Active Directory
- Servidor d'Arxius
- Servidor d'Impressores
- Bases de dades
- Aplicacions en servidor

---

## 2. Càlcul del cost total segons les dues opcions principals: **Standard** i **Datacenter**

### **Opció Standard**
1. **Preu per nucli:**  
   1.131,05 € / 16 = **70,69 € per nucli**
2. **Cost per 24 nuclis:**  
   24 x 70,69 € = **1.696,58 €**
3. **Cost 45 User CALs:**  
   45 x 48,39 € = **2.177,55 €**
4. **Subtotal (sense IVA):**  
   1.696,58 € + 2.177,55 € = **3.874,13 €**
5. **IVA (21%):**  
   3.874,13 € x 0,21 = **813,56 €**
6. **Total amb IVA:**  
   **4.687,69 €**

---

### **Opció Datacenter**
1. **Pack 16 nuclis:** 6.510,52 €  
2. **Pack 2 nuclis:** 813,82 €  
   Per 24 nuclis:  
   - 1 pack de 16 nuclis = 6.510,52 €  
   - 4 packs de 2 nuclis = 3.255,28 €  
   **Total nuclis:** 9.765,80 €  
3. **Cost 45 User CALs:**  
   45 x 48,51 € = 2.182,95 €  
4. **Subtotal (sense IVA):**  
   9.765,80 € + 2.182,95 € = **11.948,75 €**  
5. **IVA (21%):**  
   11.948,75 € x 0,21 = **2.509,24 €**  
6. **Total amb IVA:**  
   **14.457,99 €**

---

## 3. Determinar quin tipus de CAL és més econòmic (User vs Device)

### **User CAL**
- Preu: 48,53 € (sense IVA)  
- Cost total:  
  45 x 48,53 € = **2.183,85 €** (sense IVA)  
  Amb IVA: **2.642,40 €**

### **Device CAL**
- Preu: 37,67 € (sense IVA)  
- Dispositius:  
  - 30 treballadors d’oficina (PC + portàtil) = 60 dispositius  
  - 15 mossos (5 tauletes compartides) = 5 dispositius  
  **Total:** 65 dispositius  
- Cost total:  
  65 x 37,67 € = **2.448,55 €** (sense IVA)  
  Amb IVA: **2.962,70 €**

**Conclusió:**  
User CAL és més econòmic (estalvi aproximat: 265 € sense IVA, 320 € amb IVA).

---

## 4. Justificació de la decisió final

- **Cost inicial vs cost real:**  
  Standard és més barat inicialment, però només cobreix 2 VMs per llicència. Per 12 VMs, el cost puja molt.  
  Datacenter cobreix **VMs il·limitades** amb una sola llicència.
- **Escalabilitat:**  
  Datacenter permet afegir VMs sense cost addicional → ideal per creixement futur.
- **Funcionalitats clau:**  
  Datacenter inclou:
  - **Storage Spaces Direct** (alta disponibilitat)
  - **Shielded VMs** (seguretat)
  - **SDN** (gestió avançada de xarxa)
- **CALs:**  
  User CAL és la millor opció per TransLògic (45 usuaris).

**Recomanació final:**  
**Windows Server 2025 Datacenter + 45 User CALs**  
Encara que el cost inicial és més alt, és més rentable a llarg termini i aporta funcionalitats crítiques.

---

## 5. Presentació al client

Crear una presentació (5-10 minuts) amb:
- Explicació clara i visual
- Comparativa de costos (Standard vs Datacenter)
- Beneficis de Datacenter (escalabilitat, seguretat, disponibilitat)
- Elecció de CALs (User vs Device)
- Recomanació final amb justificació

---

[Torna a l'enunciat](README.md)

[Torna a la pàgina principal](../README.md)




