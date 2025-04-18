# BD_Modelis  
**Bakalaura darbs – Klientu gaidīšanas laika samazināšana McDonald’s restorānā**

## Darba autors
- **Maksims Maļinovskis** (Maksims.Malinovskis_2@edu.rtu.lv) — [GitHub](https://github.com/maximalian)

---

## Saturs
1. [Sākotnējā modeļa apraksts](#sākotnējā-modelis)  
2. [Uzlabojumu scenāriji](#uzlabojumu-scenāriji)  
   - [1. Resursu palielināšana](#1-resursu-palielināšana)  
   - [2. Uzdevumu sadalīšana starp pavāriem](#2-uzdevumu-sadalīšana-starp-pavāriem)  
   - [3. Automatizācijas ieviešana virtuves procesos](#3-automatizācijas-ieviešana-virtuves-procesos)  

---

## Sākotnējā modelis
Apraksts: Arenas simulācijas modelis ar 2 kases darbiniekiem, 3 pašapkalpošanās kasēm un 2 pavāriem virtuvē, klientu plūsma 15–25 ārpus pīķa stundām un 30–40 pīķa stundās.  
**Lejupielādēt:** [models/initial_model.ana](./models/initial_model.ana)

---

## Uzlabojumu scenāriji

### 1. Resursu palielināšana
1. **Pārvietot resursus**  
   - 3 pavāri, 1 kase, 3 pašapkalpošanās kases  
   - [models/scenario1_move_resources.ana](./models/scenario1_move_resources.ana)

2. **Pilnīga resursu pārkārtošana**  
   - 5 pavāri, 0 kases, 3 pašapkalpošanās kases  
   - [models/scenario1_full_relayout.ana](./models/scenario1_full_relayout.ana)

3. **Vienkārša pavāru skaita palielināšana**  
   - 3 pavāri, 2 kases, 3 pašapkalpošanās kases  
   - [models/scenario1_add_cooks.ana](./models/scenario1_add_cooks.ana)

### 2. Uzdevumu sadalīšana starp pavāriem
- Pavāru specializācija:  
  - Pavārs A gatavo burgerus un desertus  
  - Pavārs B gatavo dzērienus un frī kartupeļus  
- Nodrošina vienmērīgāku slodzi un ātrāku apstrādi  
- [models/scenario2_task_distribution.ana](./models/scenario2_task_distribution.ana)

### 3. Automatizācijas ieviešana virtuves procesos
- Robotizētas grilēšanas iekārtas burgeru kotletēm (piem., Alpha Grill)  
- Ātrāka gatavošana un lielāka caurlaidspēja  
- [models/scenario3_automation.ana](./models/scenario3_automation.ana)
