# 造纸工程与外贸实战笔记：OCC 包装纸工艺、双长网分层与封闭水处理 Q&A

> **背景说明**：本笔记整理自「埃及亚历山大 250 TPD 双长网包装纸生产线项目」技术审阅与方案打磨过程中的核心工程问答（Q&A）及行业专业英语学习要点，涵盖**包装纸品类辨析、双长网分层机理、废纸分级制浆、两级气浮+生化水处理逻辑、项目产能核算公式及国际外贸高频术语**。

---

## 目录

1. [包装纸三大品类与瓦楞纸箱结构（Products & Box Structure）](#一包装纸三大品类与瓦楞纸箱结构products--box-structure)
2. [核心概念辨析：Liner vs Ply，以及面/底层纤维铁律](#二核心概念辨析liner-vs-ply以及面底层纤维铁律)
3. [OCC 废纸制浆：为什么要“分级”？什么情况“分层”或“混抄”？](#三occ-废纸制浆为什么要分级什么情况分层或混抄)
4. [造纸污水处理深度 Q&A：两级 CAFP 气浮与高浓生化的底层逻辑](#四造纸污水处理深度-qa两级-cafp-气浮与高浓生化的底层逻辑)
5. [国际造纸项目审图与产能验算核心公式（Engineering Audit）](#五国际造纸项目审图与产能验算核心公式engineering-audit)
6. [造纸与水处理外贸高频英语词典与实战句型（English Learning）](#六造纸与水处理外贸高频英语词典与实战句型english-learning)

---

## 一、包装纸三大品类与瓦楞纸箱结构（Products & Box Structure）

### 1. 瓦楞纸板（Corrugated Board）的“三明治”结构
日常快递箱、家电箱、出口果蔬箱均由三层（或五层、七层）原纸粘合而成：

```text
─────────────────────────────────────────  ← 面纸 Outer Liner / Top Liner（直接朝外：要美观、耐破、耐折、适于印刷）
  ╱╲   ╱╲   ╱╲   ╱╲   ╱╲   ╱╲   ╱╲   ╱╲    ← 芯层 Fluting / Corrugating Medium（波浪拱形结构：提供抗压挺度与缓冲减震）
─────────────────────────────────────────  ← 里纸 Inner Liner / Back Liner（纸箱内壁：封底贴合、辅助支撑）
```

### 2. 三大核心纸种对比（Fluting vs Testliner vs Kraftliner）

| 对比维度 | 高强瓦楞原纸 | 测试挂面纸 / 仿牛卡纸 | 纯木浆牛卡纸（真牛卡） |
| :--- | :--- | :--- | :--- |
| **国际标准英文** | **Fluting** / **Corrugating Medium**<br>*(高强瓦：High-Performance Fluting)* | **Testliner** *(按品质分 1 / 2 / 3 级)*<br>**Imitation Kraftliner** *(中国俗称仿牛卡)* | **Kraftliner** *(Virgin Kraft Liner)* |
| **在纸箱中的位置** | 中间波浪形**瓦楞芯层** | 纸箱**最外层面纸（Outer Liner）**或**内层里纸（Inner Liner）** | 高档/重型包装箱、冷链防潮箱**最外层面纸** |
| **原料构成** | **100% 废纸（OCC）** | **100% 废纸（OCC）** + 表面施胶淀粉 + 棕黄牛皮色染料 | **≥80% 原生本色硫酸盐针叶木长纤浆（UKP）** |
| **核心物理指标** | **环压强度（RCT）**、**平压强度（CMT）**<br>*(讲究硬挺抗压，夹在内部故不讲究表面黑点)* | **耐破度（Burst）** + **环压（RCT）** + **表面尘埃度（Dirt Count）** + **平滑度** | **极高耐破度（Burst）**、耐折度、撕裂度及抗水防潮性（**Cobb 值**） |
| **主流克重范围** | `80 – 140 g/m²` *(105–120 gsm 最常见)* | `110 – 200 g/m²` | `125 – 250+ g/m²` |

> **💡 外贸常识补充**：
> * 中国国内俗称的**“仿牛卡纸”**，在国际和中东/欧洲贸易标准中对应的就是最高等级的再生挂面纸 —— **`Testliner 1`**（通过面层精细除杂、染牛皮棕黄色、光泽压榨及表面施胶，使外观与指标逼近真牛卡 `Kraftliner`）。
> * 做厚纸箱板用的牛皮卡纸叫 **`Kraftliner`**；而做手提袋、水泥袋、信封用的薄牛皮纸英文叫 **`Kraft paper`** 或 **`Sack kraft paper`**。

---

## 二、核心概念辨析：Liner vs Ply，以及面/底层纤维铁律

### Q1：什么领域叫 `Liner`？什么领域叫 `Ply`？
这两个词按**上下游产业链**严格区分：
* **下游【纸箱包装厂 / 瓦楞纸板厂（Corrugated Box Plant）】$\rightarrow$ 叫 `Liner`**
  * 指纸箱厂买来的**一整卷独立的成品平张原纸**（面纸 `Outer Liner`、里纸 `Inner Liner`）。
* **上游【造纸厂 / 造纸机械（Paper Mill / Paper Machine）】$\rightarrow$ 叫 `Ply`（层）**
  * 造纸厂在生产那一卷箱板纸时，用**双长网（Double Fourdrinier / 2-Ply PM）**把上下两张网上的湿纸浆在湿态下叠合压制成**同一张纸**。撕开这张纸横截面看到的内部上下分层，分别叫 **`Top Ply`（面层）** 和 **`Bottom Ply` / `Base Ply`（底层）**。
* **一句话串记**：造纸厂用双长网把 **`Top Ply` + `Bottom Ply`** 压合成一卷成品 **`Testliner`**，卖给纸箱厂做纸箱的 **`Outer Liner`**。

---

### Q2：做 `Testliner`（仿牛卡）时，面层用短纤维增加柔软度、底层用长纤维提强度吗？
**❌ 错误！恰恰相反！千万不要把“生活用纸（抽纸）”和“工业纸箱板”搞反了：**

* **抽纸 / 面巾纸（Tissue）**：面层才用短纤维（阔叶木浆），追求亲肤柔软度（Softness）。
* **箱板纸 / 仿牛卡（`Testliner`）**：最怕软！追求的是**结实、硬挺、折角不裂**，标准黄金搭配是：
  * **`Top Ply`（面层，占约 25%–30% 薄层）= 必须用【长纤维】！**（经浮选除黑点 + 盘磨分丝后的优质长纤）
  * **`Bottom Ply`（底层，占约 70%–75% 厚层）= 用【短纤维】！**（筛分剩下的次级短纤/普通浆）

#### 为什么 `Testliner` 面层必须用长纤维、底层用短纤维？
1. **防“折角爆线（Cracking）”**：纸板折成 90° 直角做纸箱时，**最外侧的面层（`Top Ply`）受到最大的拉伸应力**，内侧的底层受挤压。如果面层铺短纤维，纸箱一折弯外表面就会崩裂露底（俗称“爆线”）。只有长纤维交织成网，才能抗拉伸、高耐破，同时经盘磨与光泽压榨后平整适印。
2. **好料撑门面，碎料填肚子**：一锅废纸里长纤维是最金贵的精华，集中铺在 `Top Ply` 刀刃上；筛出来的短纤维拉力虽弱，但细密紧实，铺在看不见的 `Bottom Ply` 占大头厚度，既能把纸板硬挺度（抗压不塌箱）撑起来，又省去了打浆电费。

---

## 三、OCC 废纸制浆：为什么要“分级”？什么情况“分层”或“混抄”？

### Q3：既然做 `Fluting`（瓦楞芯纸）可以把两个浆池混起来抄，那做 `Testliner`（仿牛卡）也能混起来抄吗？
**不能混抄！做 `Testliner` 必须分层抄造。** 这里必须把**制浆车间的“分级”**和**抄纸车间的“分层”**分两步看清：

1. **第 1 步 —— 制浆车间：无论做什么纸，都要“先分级”（Fractionation & Selective Refining）**
   * 通过多级分级筛（Fractionating Screen）把同一锅 OCC 废纸筛分成**长纤维**和**短纤维**两路。
   * **核心目的**：**只把长纤维送进盘磨机（Refiner）打浆分丝，短纤维完全不进盘磨机！** 如果不分筛直接混磨，短纤维会被过度切断变成“浆糊”（导致上纸机滤水困难、断头降速），还白白浪费近一半磨浆电耗。
2. **第 2 步 —— 抄纸车间：看目标纸种，决定“分层”还是“混抄”**
   * **生产 `Testliner`（仿牛卡/挂面纸）$\rightarrow$ 必须【分层抄造（Stratified Forming）】**：精磨净化的长纤维专走上长网做 `Top Ply`（面层），免磨洗涤的短纤维专走主长网做 `Bottom Ply`（底层）。若混抄则会把长纤维埋没在底层、短纤维混入面层，废掉双长网的核心价值。
   * **生产 `Fluting`（高强瓦楞芯纸）$\rightarrow$ 采用【混合抄造（Mixed Forming）】**：瓦楞芯纸夹在纸箱中间不分正反面，将精磨长纤（充当钢筋骨架）与短纤（充当水泥填充增挺）按配比混合后同时供上下网抄造，高产稳速。

### Q4：如何理解设备商说的“表面尘埃度可以保证，但纸张强度取决于废纸质量”？
这是造纸机械厂非常实在的**技术性能边界划分**：
* **尘埃度（Dirt / Specks）靠设备保证**：黑点、泥沙、塑料热熔胶（Stickies）属于物理杂质，依靠细缝筛（0.15mm）、三段除渣器、浮选机和网前双鼓筛即可干净脱除，因此设备厂敢承诺达标。
* **绝对物理强度（Burst / RCT）受制于原料纤维长度**：机器只能梳理分丝纤维，**不能把短纤维变成长纤维**。例如埃及本地废纸（Local OCC）经过多次循环回收，纤维已被反复切断且灰分极高；若要生产高耐破等级的 `Kraftliner` 或顶级 `Testliner 1`，必须在面层掺配进口美废（AOCC）/ 欧废（EOCC）或原生本色木浆板（UKP），并配合表面施胶淀粉增强。

---

## 四、造纸污水处理深度 Q&A：两级 CAFP 气浮与高浓生化的底层逻辑

典型封闭循环工艺链：
`车间白水 (SS 1000mg/L)` $\rightarrow$ **`一级 CAFP-300 气浮`** *(75% 澄清水直回碎浆；25% 高浓水进生化)* $\rightarrow$ **`GSF 高浓生化反应器`** $\rightarrow$ **`二级 CAFP-100 气浮`** $\rightarrow$ `清水回用 (COD≤500, SS≤50mg/L)`

### Q5：第一道气浮出来 SS 已经降到 `50 mg/L` 了，为什么经过生化降完 COD/BOD 后，后面还要再加第二台气浮去降 SS？
* **核心原理**：**生化处理的本质，是把水里“看不见的溶解态有机物（COD/淀粉/糖类）”喂给微生物吃掉，繁殖转化成“看得见的细菌团块（活性污泥 Biomass = 新的生物态 SS）”！**
  $$\text{溶解态 COD/BOD} + \text{好氧微生物} \longrightarrow \text{CO}_2 + \text{H}_2\text{O} + \mathbf{\text{大量新增微生物菌胶团（新 SS！）}}$$
* **数据量级**：进生化前水虽清澈（`SS = 50 mg/L`），但溶满有机物（`COD = 4000 mg/L`）；在 `1,800 m³/d` 水量下每天削减约 `6.3 吨` COD，光新繁殖长出的菌泥每天就有 `2～3 吨`（干重），加上反应器内原本循环的菌群，生化出水混合液悬浮物（**MLSS**）高达 **`3,000～8,000 mg/L`**！
* 因此，任何生化反应器后面**必须紧跟泥水分离设备**（二级 `CAFP-100` 在此替代了传统的混凝土“二沉池”），把菌泥捞干净后水才能回用。
* **旁路肾脏式设计（Kidney Loop）亮点**：总水量约 `7,000 m³/d`，一级气浮捞除纸毛后 75% 直接回制浆化纸（碎浆不怕少量溶解 COD），仅抽 **25%（`1,800 m³/d`）** 进生化做深度脱 COD 与除阴离子垃圾，节省了 3/4 的生化设备投资与运行电费。

---

### Q6：既然 `CAFP` 涡凹气浮占地小、分离快，为什么绝大多数市政和大中型污水厂仍然用传统混凝土初沉池、二沉池？
核心是 **4 本工程与商业账**：
1. **运行成本账（免费重力 vs 24h 烧药剂电费）**：重力二沉池靠免费的地球引力自然沉降，**无需投加任何化学药剂**，刮泥机仅 `1.5–3 kW`；而 `CAFP` 气浮必须 24 小时连续投加 **PAC（聚合氯化铝混凝剂）** 和 **PAM（聚丙烯酰胺絮凝剂）** 才能让颗粒抱团挂泡，吨水药剂+电费高出 `0.3–0.8 元`，日处理十万吨级市政厂根本烧不起。
2. **污染物比重不同（造纸爱飘 vs 市政爱沉）**：造纸白水里的细小植物纤维、热熔胶、塑料微粒比重接近水甚至比水轻，重力沉降极慢，用气泡往上一托反而顺势快浮；高浓生化泥浓易带气上浮，也适合气浮。而市政泥沙和常规低浓活性污泥比水重，静置自然沉底最划算。
3. **水质极限与药剂残留风险**：涡凹气浮叶轮剪切大、气泡偏粗，出水 SS 一般在 `30–50 mg/L`，且长期投加 PAM 高分子药剂在闭路循环中残留过多易“糊网、糊毛布”（高压洗网/洗毛布喷淋前通常需加装精密自清洗过滤器）；而优质重力二沉池不加药自然溢流 SS 可稳定 `< 15–20 mg/L`。
4. **商业分工账**：混凝土大沉淀池产值归当地土建施工队；而成套不锈钢 `CAFP` + 钢制反应器可在机械厂模块化制造装箱出口，既方便机械厂集成报价，也帮海外业主省去大规模挖坑浇筑土建工期。

---

### Q7：二级气浮分离出的菌泥“一路回流进生化池、一路排去压泥机”，机器不长眼睛，是怎么区分好细菌和死菌泥的？
* **真相**：**机器完全不区分！** 它是把同一锅混在一起的菌泥，直接通过三通管和阀门**按流量比例盲分**（例如 **85% 回流 + 15% 排走**）。
* **为什么盲分也能保证全是年轻好细菌？（控制“污泥龄 SRT”）**
  * 就像**“老面发馒头”**或**“军队每年退伍 15%、招新兵 15%”**：只要**每天排走的剩余污泥量（15%）刚好等于当天细菌吃 COD 新繁殖出来的增量（15%）**，整个系统里的细菌每 **7～12 天（泥龄 SRT）** 就会自动整体换血更新一轮，菌群永远保持青壮年高活性状态！
  * **物理粗分辅助**：`CAFP 涡凹气浮沉淀机` 兼具“上部刮浮渣 + 底部锥斗排沉渣”结构——矿化老死的重菌团与钙镁无机结垢颗粒优先沉入底斗排去污泥池，轻盈活跃的菌胶团随回流管返回反应器。

---

## 五、国际造纸项目审图与产能验算核心公式（Engineering Audit）

拿到客户询价单（RFQ）与技术方案时，第一时间用以下公式验算**门幅、定量、车速与烘缸**是否自洽：

$$\text{实际稳定日产量 (TPD)} = \frac{\text{净纸宽 Trim (m)} \times \text{工作车速 Speed (m/min)} \times \text{定量 GSM (g/m}^2\text{)} \times 1440}{1,000,000} \times \eta_{\text{综合效率}}$$

*(其中行业常规综合效率 $\eta = \text{抄造率} \times \text{复卷成品率} \approx 90\% \sim 92\%$)*

### 实战验算案例（埃及亚历山大 250 TPD 项目）：
* **客户硬指标**：净纸宽 `3850 mm`（`3.85 m`）、卷取毛宽 `3910 mm`、设计基准定量 `120 g/m²`、定量范围 `80–200 g/m²`、日产 `250 TPD`。
* **反推所需车速**：
  * 若只开 `300 m/min` $\rightarrow$ 日产仅 $3.85 \times 300 \times 120 \times 1.44 \times 0.91 \div 1000 = \mathbf{181.6\text{ TPD}}$（严重不达标！`80 g/m²` 时仅 `121 TPD`）。
  * 要稳定达产 `250 TPD` $\rightarrow$ **实际工作车速必须达到 `415–420 m/min`**，因此纸机与流浆箱**结构设计车速必须定为 `450–500 m/min`**！
* **配套干燥与工程漏项必查点**：
  1. **烘缸数量**：`3850 mm` 幅宽产 `250 TPD`（含表面施胶），标准需配 **`44–48 只 Φ1800` 烘缸**（前烘 ~30只 + 后烘 ~16只）。
  2. **核心辅机防漏项**：水环真空泵组/透平真空风机（约 `600–900 kW`）、烘干部密闭气罩与排风热回收、蒸汽与冷凝水热泵系统、湿/干损纸碎浆系统（Broke Pulpers）、稀油集中润滑站、**交流变频独立分部传动（AC Motor + VFD Sectional Drive）**。
  3. **海外清关红线**：二手翻新铸铁烘缸属于旧压力容器，出口埃及等中东国家前务必核实当地二手工业设备进口许可（GOEIC / ACI）及第三方压力容器壁厚水压安全认证（SGS/BV/ASME）。

---

## 六、造纸与水处理外贸高频英语词典与实战句型（English Learning）

### 1. 纸种、结构与物理指标词汇
| 英文术语 | 中文释义 | 记忆与应用场景 |
| :--- | :--- | :--- |
| **Fluting / Corrugating Medium** | 瓦楞原纸 / 瓦楞芯纸 | 纸箱中间压波浪的夹芯层 |
| **Testliner (TL1 / TL2 / TL3)** | 测试挂面纸 / 再生箱板纸 | TL1 即国内常说的“仿牛卡纸（Imitation Kraftliner）” |
| **Kraftliner** | 纯木浆牛卡纸（挂面纸板） | 原生本色长纤木浆制造的高耐破面纸 |
| **OCC (Old Corrugated Containers)** | 废旧瓦楞纸箱（黄板废纸） | AOCC（美废）、EOCC（欧废）、Local OCC（本地废纸） |
| **UKP (Unbleached Kraft Pulp)** | 本色硫酸盐木浆 | 原生长纤木浆板，常掺于高端面层提耐破 |
| **Outer Liner / Fluting / Inner Liner** | 面纸 / 瓦楞芯纸 / 里纸 | **纸箱厂领域**：瓦楞纸板的三层原纸名称 |
| **Top Ply / Middle Ply / Bottom (Base) Ply** | 面层 / 芯层 / 底层 | **造纸厂领域**：单张纸在多叠网上的内部复合层 |
| **Basis Weight / Grammage (GSM, g/m²)** | 定量 / 克重 | 如 Design basis weight: 120 gsm |
| **Trim Width / Reel Width / Wire Width** | 净纸宽 / 卷取纸宽 / 网宽 | 如 Trim 3850 mm, Reel 3910 mm |
| **Bursting Strength / Burst Index** | 耐破强度 / 耐破指数 | 牛卡纸与仿牛卡最核心的抗爆裂指标 |
| **RCT (Ring Crush Test)** | 环压强度 | 箱板纸与高瓦纸最核心的抗压立箱挺度指标 |
| **CMT (Concora Medium Test)** | 平压强度（瓦楞起楞后） | 专门考核瓦楞芯纸（Fluting）起槽后的抗扁塌能力 |
| **Dirt Count / Specks / Stickies** | 尘埃度 / 黑点杂质 / 胶粘物 | 决定仿牛卡纸表面洁净度与印刷外观 |

### 2. 制浆、抄纸与传动装备词汇
| 英文术语 | 中文释义 |
| :--- | :--- |
| **Double Fourdrinier / Twin-Wire Paper Machine** | 双长网造纸机 |
| **Stock Preparation** | 制浆备浆系统 |
| **Fractionating Screen** | 分级筛（将浆料拆分为 Long fiber 与 Short fiber） |
| **Selective Refining / Disc Refiner** | 分级打浆 / 盘磨机 |
| **High/Low Density Cleaner** | 高浓 / 低浓除渣器 |
| **Flotation Cell / Deinking & Cleaning** | 浮选槽 / 浮选脱墨除杂 |
| **Approach Flow System & Double-Drum Screen** | 网前流送系统 & 双鼓网前筛 |
| **Pressurized Headbox** | 压力流浆箱 |
| **Combi-Press / Gloss Press (Calender)** | 复合压榨部 / 光泽压榨部 |
| **Pre-Dryer / Size Press / After-Dryer** | 前干燥部 / 表面施胶机 / 后干燥部 |
| **Pope Reel & Slitter Rewinder** | 气动卷纸机 & 分切复卷机 |
| **AC VFD Sectional Drive** | 交流变频独立分部传动（AC Motor + Variable Frequency Drive） |

### 3. 环保水处理词汇
| 英文术语 | 中文释义 |
| :--- | :--- |
| **Closed-Loop Water System / Zero Liquid Discharge (ZLD)** | 废水封闭循环系统 / 液体零排放 |
| **CAF / DAF (Cavitation / Dissolved Air Flotation)** | 涡凹气浮（CAFP）/ 溶气气浮 |
| **Primary Clarifier / Secondary Clarifier** | 初沉池 / 二沉池 |
| **COD / BOD / SS (Suspended Solids)** | 化学需氧量 / 生化需氧量 / 悬浮物浓度 |
| **MLSS (Mixed Liquor Suspended Solids)** | 混合液悬浮固体浓度（生化池内的菌泥浓度） |
| **Activated Sludge / Biomass** | 活性污泥 / 微生物菌体 |
| **RAS (Return Activated Sludge) / WAS (Waste Activated Sludge)** | 污泥回流（回反应器干活）/ 剩余污泥排放（去压泥机外运） |
| **SRT (Sludge Retention Time)** | 污泥龄（菌群平均更新换代周期） |
| **Anionic Trash / DCS (Dissolved and Colloidal Substances)** | 阴离子垃圾 / 溶解与胶体物质（封闭循环重点清除对象） |

### 4. 对外商务技术沟通实战英文金句

1. **解释双长网分层做 `Testliner` 的优势（长纤做面、短纤做底）**：
   > *"After fiber fractionation, the cleaned and refined **long fibers** are fed to the **Top Ply** to ensure high burst strength, crack resistance on box folding, and a clean printing surface; meanwhile, the unrefined **short fibers** form the **Bottom Ply** for bulk, stiffness (RCT), and lower refining power consumption."*
2. **解释生产 `Fluting` 与 `Testliner` 的模式切换**：
   > *"For **Testliner / Imitation Kraftliner**, we run stratified two-ply forming; when switching to **Fluting**, the short-fiber and refined long-fiber chests can be blended together to maximize runnability and machine speed."*
3. **解释为什么生化后面还要配二级气浮除 SS**：
   > *"During biological treatment, dissolved COD is consumed by bacteria and converted into new **biological sludge (biomass)**, raising the mixed-liquor SS significantly. Therefore, a **Secondary Flotation Unit (CAFP-100)** is installed right after the bioreactor to separate the biomass—returning active sludge to the reactor while discharging excess sludge for dewatering."*
