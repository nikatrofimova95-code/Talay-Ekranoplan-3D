# 🚀 Propulsion System Modification: Talay Ekranoplan
*(Repository Branch: `feature/u8-motor-upgrade`)*

This branch serves as an engineering addition to the base geometry of the Talay unmanned ekranoplan (`main`). It demonstrates detailed propulsion unit design, brushless motor integration, and a separable nacelle construction optimized for 3D printing.

---

## 📐 1. General Technical Parameters
- **Project Type:** Unmanned Ekranoplan (ground-effect vehicle).
- **Model Scale:** All components and STL files were designed and exported from Blender using a scale factor of **0.05**.
- **Design Environment:** Blender (configured with Ukrainian interface localization).

---

## 🖼️ 2. General View of the Updated Ekranoplan
Below is the general view of the assembled unmanned ekranoplan model in Blender featuring the integrated updated engine nacelles:

![General View of Ekranoplan 1](images/Знімок%20екрана%202026-11-12%20161735.png)

![General View of Ekranoplan 2](images/Знімок%20екрана%202026-11-12%20161756.png)

---

## 🛠️ 3. Nacelle Structural Modifications & Details
This version implements a complete design cycle for the rear nacelle to meet practical assembly requirements:

### Motor Mounting Face
A precise mounting plane with fastener holes and a central wiring channel for power cable routing has been formed on the rear wall of the nacelle.

![Motor Mounting Face (Rear Wall)](images/Знімок%20екрана%202026-11-12%20161829.png)

### Front Cowling & Joint Groove
The structure is split into two separate parts for convenient 3D printing and assembly. Due to the minimal wall thickness, using mechanical screws in this joint area is unfeasible. Therefore, a **3 mm deep cylindrical stepped lap joint groove** has been engineered at the interface for reliable adhesive bonding.

![Front Cowling](images/Знімок%20екрана%202026-11-12%20161838.png)
![3 mm Joint Groove](images/Знімок%20екрана%202026-11-12%20161916.png)

---
## ⚙️ 4. Detailed Propulsion Specifications

Since aerodynamic blades and heavy brushless motors are standardized high-precision industrial products, they do not require manual CAD modeling and are included in the project as strict technical specifications and documentation.

### Electric Motor: T-Motor U8 II KV100

![T-Motor U8 II Motor](images/Знімок%20екрана%202026-11-12%20163037.png)

- **Purpose:** High-power industrial brushless motor designed specifically for heavy-duty multirotors, long-endurance UAVs, and experimental ekranoplans.
- **Key Specifications:** 
  * Low KV rating (KV100) optimized for large propellers operating under high voltage (high-capacity LiPo batteries).
  * High torque at low and medium RPM, which is critical for overcoming water drag during ekranoplan takeoff.
  * Industrial-grade dustproof and waterproof housing construction reliably protects internal windings from water splashes and moisture during surface operations.
  * Mounting interface with standard hub hole patterns (15/16 mm, M3 fasteners), perfectly integrated into the engineered rear nacelle wall.

### Carbon Fiber Propellers: T-Motor Folding Carbon Fiber (28.2 × 9.2)

![T-Motor Carbon Fiber Propellers](images/Знімок%20екрана%202026-11-12%20163222.png)

- **Design Type:** Folding carbon fiber dual-blade propellers.
- **Key Specifications & Advantages:**
  * Dimensions: **28.2 × 9.2 inches**, engineered for direct synergy with T-Motor U8 series motors.
  * Material: High-modulus carbon fiber providing exceptional bending rigidity at minimal weight with zero deformation at maximum operating speeds.
  * Folding blade design reduces aerodynamic drag during gliding or when the propulsion system is inactive, while also simplifying transport and storage.
  * High aerodynamic efficiency of the profiled blade guarantees maximum static thrust for dynamic ekranoplan transition into ground-effect mode.

---

## 📂 5. Repository Structure
- `stl_files/` — folder containing updated STL files (scale factor **0.05**).
- `images/` — folder containing all visual assets and screenshots.
- `ekranoplan02` — Blender project file.
- `README.md` — technical documentation and branch overview.

---

## 🚀 How to Open & Requirements
1. **Blender Project (`ekranoplan02`):** 
   * Recommended to open using **Blender 5.0.1** (or compatible 5.x versions) to correctly inspect meshes, modifiers, and scene structure.
2. **STL Files (`.stl`):** 
   * Can be opened in any standard 3D viewer, CAD software, or slicer (such as Cura or PrusaSlicer) for prototyping or 3D printing individual parts and assemblies. Keep the **0.05 scale** and **0.5 mm wall thickness** parameters in mind during preparation.
# 🚀 Модифікація силової установки: Екраноплан «Талай»

Ця гілка є інженерним доповненням до базової моделі безпілотного екраноплана «Талай» (`main`). Вона демонструє детальне проєктування силового вузла, інтеграцію безколекторного двигуна та рознімну конструкцію мотогондоли для 3D-друку.

---

## 📐 1. Загальні технічні параметри моделі
* **Тип проєкту:** Безпілотний екраноплан (транспортний засіб з наземним ефектом).
* **Масштаб моделі:** Усі компоненти та STL-файли спроектовані та експортовані з Blender із масштабом **0,05**.
* **Середовище проєктування:** Blender (з використанням українськомовної локалізації інтерфейсу).

---

## 🖼️ 2. Загальний вигляд оновленого екраноплана
Нижче наведено загальний вигляд зібраної моделі безпілотного екраноплана в Blender із інтегрованими оновленими мотогондолами:

![Загальний вигляд екраноплана 1](images/Знімок%20екрана%202026-11-12%20161735.png)

![Загальний вигляд екраноплана 2](images/Знімок%20екрана%202026-11-12%20161756.png)


---

## 🛠️ 3. Конструктивні зміни мотогондоли та деталі
У цій версії реалізовано повний цикл доопрацювання задньої мотогондоли під реальні монтажні вимоги:

### Посадкове місце двигуна
На задній стінці мотогондоли сформовано точну площину з отворами під кріплення та центральним каналом для виведення силової проводки.

![Посадкове місце двигуна (задня стінка)](images/Знімок%20екрана%202026-11-12%20161829.png)

### Передній обтічник та з'єднувальний паз
Конструкція розділена на дві окремі деталі для зручності 3D-друку та збірки. Оскільки товщина стінок мінімальна і використання гвинтів у цій зоні неможливе, на стику передбачено **циліндричне ступінчасте заглиблення (паз завглибшки 3 мм)** для клейової фіксації.

![Передній обтічник](images/Знімок%20екрана%202026-11-12%20161838.png)
![З'єднувальний паз 3 мм](images/Знімок%20екрана%202026-11-12%20161916.png)

---
## ⚙️ 4. Детальна специфікація силової установки

Оскільки аеродинамічні лопаті та важкі безколекторні двигуни є стандартизованими промисловими виробами високої точності, вони не потребують ручного моделювання в CAD-системах, а додаються до проєкту у вигляді суворої технічної специфікації та документації.

### Електродвигун: T-Motor U8 II KV100

![Двигун T-Motor U8 II](images/Знімок%20екрана%202026-11-12%20163037.png)

* **Призначення:** Промисловий безколекторний двигун високої потужності, розроблений спеціально для важких багатороторних платформ (Heavy-duty Multirotors), безпілотників великої тривалості польоту та експериментальних екранопланів.
* **Основні характеристики:** 
  * Низький показник KV (KV100) оптимізований під роботу з великими пропелерами під високою напругою (LiPo акумулятори високих ємностей).
  * Високий крутний момент (Torque) на низьких і середніх обертах, що критично важливо для подолання водного опору під час зльоту екраноплана.
  * Пиловологозахищена конструкція корпусу промислового рівня надійно захищає внутрішні обмотки від бризок води та вологи під час руху над поверхнею.
  * Посадковий інтерфейс з отворами під стандартизований хаб (15/16 мм, кріплення M3), ідеально інтегрований у спроєктовану задню стінку мотогондоли.

### Карбонові пропелери: T-Motor Folding Carbon Fiber (28.2 × 9.2)

![Карбонові пропелери T-Motor](images/Знімок%20екрана%202026-11-12%20163222.png)

* **Тип конструкції:** Складні дволопатеві карбонові пропелери (Folding Carbon Fiber Propeller).
* **Основні характеристики та переваги:**
  * Розмірність: **28.2 × 9.2 дюйма**, розрахована на пряму синергію з двигунами серії T-Motor U8.
  * Матеріал: Високомодульний карбон (вуглеволокно), що забезпечує надзвичну жорсткість на вигин при мінімальній вазі та відсутності деформацій на максимальних робочих обертах.
  * Складна конструкція лопатей знижує аеродинамічний опір у момент планування або під час непрацюючої силової установки, а також полегшує транспортування та зберігання апарата.
  * Висока аеродинамічна ефективність профільованої лопаті гарантує максимальний статичний тяговий зусилля для динамічного виходу екраноплана на екранний режим.

---

## 📂 5. Структура репозиторію
* `stl_files/` — папка з оновленими STL-файлами (масштаб **0,05**).
* `images/` — папка з усіма візуальними матеріалами та скріншотами.
* `ekranoplan02` — файл проєкту Blender.
* `README.md` — технічна документація та опис гілки.

---

## 🚀 How to Open & Requirements
1. **Blender Project (`ekranoplan.blend`):** 
   * Recommended to open using **Blender 5.0.1** (or compatible 5.x versions) to correctly inspect meshes, modifiers, and scene structure.
2. **STL Files (`.stl`):** 
   * Can be opened in any standard 3D viewer, CAD software, or slicer (such as Cura or PrusaSlicer) for prototyping or 3D printing individual parts and assemblies. Keep the **0.05 scale** and **0.5 mm wall thickness** parameters in mind during preparation.
