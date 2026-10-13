# Microduck Replica · SolidWorks 3D CAD Files & Assembly Manual

**English** · [简体中文](README.md)

> **Editable SolidWorks source files** (not STL meshes), plus a 21-page assembly installation manual. **Two versions:**
> **v2.1 Feetech HD-1910 version** (2026-09-25, merged rim + tire) and **v1.1 original XL330 version** (2026-09-15, synchronized ankle / calf / foot updates).
> Companion main repository: [**fanhao375/microduck-replica**](https://github.com/fanhao375/microduck-replica) — full-robot replication, circuit boards, and reverse-engineering analysis are all maintained there.

> **Models and print files are unified in this repository (2026-09-28).** Outdated upstream STL downloads have been removed from the main repository. Please select either the Feetech or XL330 version before checking specific accessories; mating parts for the two servo options cannot be mixed.

> 📦 **Archives are available on the [Releases page](../../releases) (in the right sidebar), not in the file tree above.** 374 MB of SolidWorks files are not suitable for Git tracking.
> 🖨️ Feetech print project details are in the [3D Printing section](#3d-printing) below. The `.3mf` in this repository is the **2026-09-15 edition and does not yet include the v2.1 TPU merged tire**; this tire modification belongs to the roller-skating variant. The [MakerWorld project](https://makerworld.com.cn/zh/models/2963569-microduck#profileId-3478428) was uploaded by 机械行者Robo; the online version has not been verified in this cycle.

> 📺 **Video Assembly Tutorial: [Bilibili series "MicroDuck Assembly from Scratch"](https://space.bilibili.com/312747174/lists/9279084?type=season)** by 机械行者Robo, assembling one subassembly per episode. 6 of 8 episodes released so far → [Episode List](#video-assembly-tutorial)

<div align="center">
  <img src="assets/飞特版装机-正面.jpg" alt="Feetech HD-1910 build" width="360">
  <br><sub>2026-09-13 · Feetech HD-1910 build completed, all 15 servos in place</sub>
</div>

<div align="center">
  <img src="组件图/00-microduck装配体.png" alt="microduck assembly" width="300">
  <img src="组件图/00-microduck装配体爆炸图3.png" alt="microduck exploded view" width="360">
</div>

---

## Two Versions — Pick One

| | Original · XL330 · **v1.1** | Feetech · HD-1910 · **v2.1** |
|---|---|---|
| **Servos** | Dynamixel XL330-M288 | Feetech HD-1910-C001 |
| **Files** | 57 SolidWorks files, no suffix | 60 SolidWorks files + 11 STEP files, with `-FT` suffix |
| **Differences** | — | **Protruding servo horn**, 8 mating parts modified ([What changed](#what-changed-in-the-feetech-hd-1910-version)) |
| **Printing** | Export STLs part-by-part from [v1.1 SolidWorks source](https://github.com/fanhao375/microduck-replica-cad/releases/tag/v1.1) and slice; no ready-made print project for this version yet | [`3D Printing/` 3MF](打印/) is the 09-15 version, without v2.1 merged tire; see [Version Notes](#3d-printing) |
| **Physical build** | — | Assembled (pictured above) |
| **Download** | [`SolidWorks-XL330-v1.1.zip`](https://github.com/fanhao375/microduck-replica-cad/releases/download/v1.1/SolidWorks-XL330-v1.1.zip) 333 MB | [`SolidWorks-FT2026-09-25.zip`](https://github.com/fanhao375/microduck-replica-cad/releases/download/v2.1/SolidWorks-FT2026-09-25.zip) 343 MB |

Ankle, calf, and foot parts were synchronized to the same design on 2026-09-15 for both versions; the assembly manual and exploded component diagrams are shared between both.

---

## CAD Author: 机械行者Robo

**These 3D CAD models and assembly manuals were entirely modeled, organized, and written by 「机械行者Robo」.**

Assembly video tutorials have been published on Bilibili ([Episode List](#video-assembly-tutorial)). If you encounter assembly questions, commenting on these accounts gets the quickest response:

<table>
<tr>
<td align="center" width="33%">
  <a href="https://space.bilibili.com/312747174"><img src="assets/B站-机械行者Robo.jpg" alt="Bilibili: 机械行者Robo" width="200"></a><br>
  <b>Bilibili · 机械行者Robo</b><br>
  <sub>UID 312747174</sub>
</td>
<td align="center" width="33%">
  <a href="https://www.xiaohongshu.com/user/profile/5ad950114eacab046016f038"><img src="assets/小红书-机械行者Robo.jpg" alt="Xiaohongshu: 机械行者" width="200"></a><br>
  <b>Xiaohongshu (RED) · 机械行者</b><br>
  <sub>ID 270594280</sub>
</td>
<td align="center" width="33%">
  <a href="https://www.douyin.com/user/MS4wLjABAAAArLa_6yE3GE-AoRURoQnIHdbbI7yM-GHhzlgLZ-XbeYE"><img src="assets/抖音-机械行者Robo.jpg" alt="Douyin: 机械行者Robo" width="200"></a><br>
  <b>Douyin · 机械行者Robo</b><br>
  <sub>ID 1852366168 — "Robots for Everyone"</sub>
</td>
</tr>
</table>

> If you find these drawings useful, please give him a follow — modeling and organizing all these files took considerable effort, and he made everything available for free.

---

## Downloads

| Item | Location |
|---|---|
| **Feetech HD-1910 source files** (v2.1 · 60 SolidWorks files, ~358 MB extracted) | 👉 [**Download `SolidWorks-FT2026-09-25.zip`**](https://github.com/fanhao375/microduck-replica-cad/releases/download/v2.1/SolidWorks-FT2026-09-25.zip) |
| **Modified parts only in STEP** (v2.1 · 11 parts) | 👉 [**Download `STEP-changed-parts-FT-2026-09-30.zip`**](https://github.com/fanhao375/microduck-replica-cad/releases/download/v2.1/STEP-changed-parts-FT-2026-09-30.zip) — includes face part FT1 (adapted for original Radxa camera), openable without SolidWorks |
| **Original XL330 source files** (v1.1 · 57 SolidWorks files, 348 MB extracted) | 👉 [**Download `SolidWorks-XL330-v1.1.zip`**](https://github.com/fanhao375/microduck-replica-cad/releases/download/v1.1/SolidWorks-XL330-v1.1.zip) ([v1.0 legacy release](../../releases/tag/v1.0) still available) |
| **Assembly BOM** (curated by 机械行者Robo, 33 printed parts + 21 purchased components, with materials, quantities, unit prices; **includes Taobao/Tmall links as of 2026-09-29**) | [`BOM/装配BOM-机械行者Robo-2026-09-29-带采购链接.xlsx`](BOM/装配BOM-机械行者Robo-2026-09-29-带采购链接.xlsx), verified table below |
| **Assembly Installation Manual** (21-page PDF) | [`安装说明书/microduck装配安装说明书.pdf`](安装说明书/microduck装配安装说明书.pdf) |
| 📺 **Video Assembly Tutorial** (8 episodes planned, 6 released) | [Bilibili series "MicroDuck Assembly from Scratch"](https://space.bilibili.com/312747174/lists/9279084?type=season), see [Episode List](#video-assembly-tutorial) below |
| **Component Diagrams / Exploded Views** (23 images) | [`组件图/`](组件图/) |
| 🖨️ **3D Print Project File** (Bambu Studio `.3mf`, 4.9 MB, 2026-09-15 edition) | [`打印/microduck-飞特版-BambuStudio.3mf`](打印/microduck-飞特版-BambuStudio.3mf) — 5 plates, 52 objects; **does not contain v2.1 merged tire**, see material and slicing parameters in [3D Printing](#3d-printing) |
| 🖨️ **MakerWorld Print Portal** | [MakerWorld · microduck Feetech version](https://makerworld.com.cn/zh/models/2963569-microduck#profileId-3478428) — verify author's indicated versions and materials before printing; online updates unverified in this cycle |

> **Why source files are stored in Releases rather than Git**: SolidWorks files are in binary format. Storing them directly in Git cannot produce diffs or merges; they simply accumulate in repository history with every commit — 3 revisions would push repository size past 1 GB, and **Git history cannot easily be purged**.
> Storing archives as Release attachments does not bloat repository size, and updates only require publishing a new release. Cloning this repo remains fast at only a few megabytes.

---

## What Changed in the Feetech HD-1910 Version

The original robot uses Dynamixel XL330 servos; this project's main repository adopts Feetech HD-1910 (more affordable, 2.5× higher torque, and voltage rating matched without overvolting — see [Main Repo Actuator Selection](https://github.com/fanhao375/microduck-replica/blob/master/docs/执行器选型.md)).
**Both servos share similar overall dimensions, but their horns differ: HD-1910 features a convex (protruding) horn, while XL330 has a concave (recessed) horn.** All parts mating with the servo horn had to be updated:

| Modified Part | Reason |
|---|---|
| `left_upper_leg` / `right_upper_leg` (Left/right upper leg) | Horn mounting locations for hip pitch and knee |
| `leg` (Calf / lower leg) | Horn mounting locations for knee and ankle |
| `trunk_base` (Torso base) | Hip yaw servo mounting position |
| `yaw2roll` (Yaw to roll) | Hip yaw horn → hip roll servo |
| `bearing_roll` (Bearing roll) | Hip roll bearing seat |
| `01-upper_leg_rigidity_plate` (Upper leg reinforcement plate) | Modified together with the upper leg |
| `99-yaw_roll_motion` (Yaw/roll motion) | Head yaw/roll, `-F` and `-FT` variants |

**File naming**: All parts carry the `-FT` suffix (FT = Feetech). Parts that weren't modified also carry `-FT` for assembly reference consistency — 27 parts are identical in geometry to v1.0, just renamed.

**Additional files**: `HD-1910-c001-dan / -shuang` (single-horn / dual-horn servo models), `舵机比较.SLDASM` (side-by-side servo comparison assembly), and `飞特电机资料1/` (official STEP / DWG / specifications provided by Feetech).

⚠️ The assembly manual PDF and component diagrams **remain from v1.0**; assembly sequence and steps are identical, only the servo model differs.

---

## What Changed in Feetech v2.1 (2026-09-25)

- **`rim_轮辋` and `tire_轮胎` merged into `合体轮胎` (merged tire)**: Assembling the two separate parts was difficult; they were removed and merged into a single integrated "merged tire", printed in **TPU**.
- The complete SolidWorks set now has **60 files** (17 assemblies + 43 parts); modified STEP package expanded to **10 files** (added `合体轮胎.STEP`).

---

## Face Part Adapted for Original Radxa Camera (2026-09-30)

- **`face_part_面部零件` added a `-FT1` variant**: Updated the camera mounting hole spacing to directly fit the **original Radxa camera**.
- The modified STEP package now includes **`face_part_面部零件-FT1适配瑞莎原版摄像头 改了孔距.STEP`**, expanding from 10 to **11 files**.

---

## What Changed in Original XL330 v1.1 (2026-09-15)

When modifying the ankle, calf, and foot for the Feetech version, the original XL330 version was updated in tandem so both versions share the same design in this area:

```
Modified:   05_左小腿 · 06_左踝脚 · 14_右小腿 · 15_右踝脚 · 10_头部总成
            ankle_left (left ankle) · foot_left (left foot) · leg
Added:      deep groove ball bearings gb (bearing model)
Renamed:    00-microduck装配体 → 00-microduck装配体 XL330-288舵机版本
            ankle_right_脚踝右 → ankle_right脚踝右
```

46 parts are identical to v1.0.

---

## Assembly BOM

> The workbook has been updated to **2026-09-29**: rim + tire merged into **merged tire** (33 printed items), purchased components expanded to **21 items**, and **all purchased items now have direct Taobao / Tmall links** (the 2026-09-16 edition only had links for bearings and screws).

[`BOM/装配BOM-机械行者Robo-2026-09-29-带采购链接.xlsx`](BOM/装配BOM-机械行者Robo-2026-09-29-带采购链接.xlsx) was compiled by 机械行者Robo by subassembly. The 2026-09-29 edition completes the purchased parts list (Radxa Zero 3W, microSD card, Feetech URT-2 debug board, battery holder, ToF sensor, etc.) with verified purchase links. Electronic component specifications match verified hardware from the main repository (NP-F550 battery, 15 servos, 1 `imu_to_dxl` board). The table below reflects this list, with a few notes:

| In Workbook | Corrected Here | Basis |
|---|---|---|
| Merged tire / roller blades | Marked as **roller-skating variant, not used for walking** | Upstream `变体-轮滑/`; print only if building roller skates |
| Merged tire listed as PLA | Should be printed in **TPU** | v2.1 merged tire is a flexible TPU part, see [What Changed in Feetech v2.1](#what-changed-in-feetech-v21-2026-09-25) |

### I. 3D Printed Parts (33 items)

| # | Part | File | Material | Qty | Remarks |
|---|---|---|---|---|---|
| 1 | Head upper shell | `top_head_shell` | PLA | 1 | |
| 2 | Head lower shell | `bottom_head_shell` | PLA | 1 | |
| 3 | Face part | `face_part` | PLA | 1 | |
| 4 | Jaw | `jaw` | PLA | 1 | |
| 5 | Soft jaw | `jaw_soft` | **TPU** | 1 | Flexible part |
| 6 | Soft mouth top | `soft_mouth_top` | **TPU** | 1 | Flexible part |
| 7 | Eyes | `noenoeil` | PLA | 1 | |
| 8 | Neck | `neck` | PLA | 2 | Can be replaced with CNC aluminum for rigidity |
| 9 | Neck pitch | `neck_pitch` | PLA | 1 | |
| 10 | Torso base | `trunk_base` | PLA | 1 | Can be replaced with CNC aluminum for rigidity |
| 11 | Left shell | `left_shell` | PLA | 1 | |
| 12 | Right shell | `right_shell` | PLA | 1 | |
| 13 | Left hip | `hip_l` | PLA | 2 | |
| 14 | Yaw to roll | `yaw2roll` | PLA | 1 | |
| 15 | Yaw roll motion | `yaw_roll_motion` | PLA | 1 | |
| 16 | Leg (calf) | `leg` | PLA | 2 | |
| 17 | Left upper leg | `left_upper_leg` | PLA | 1 | |
| 18 | Right upper leg | `right_upper_leg` | PLA | 1 | |
| 19 | Upper leg rigidity plate | `upper_leg_rigidity_plate` | PLA | 2 | Can be replaced with CNC aluminum for rigidity |
| 20 | Left foot | `foot_left` | PLA | 1 | |
| 21 | Right foot | `foot_right` | PLA | 1 | |
| 22 | Left sole | `sole_left` | PLA | 1 | |
| 23 | Right sole | `sole_right` | PLA | 1 | |
| 24 | Left ankle | `ankle_left` | PLA | 1 | |
| 25 | Right ankle | `ankle_right` | PLA | 1 | |
| 26 | Left ankle V1 | `ankle_l_v1` | PLA | 1 | Alternative, pick either 24 or 26 |
| 27 | Right ankle V1 | `ankle_r_v1` | PLA | 1 | Alternative, pick either 25 or 27 |
| 28 | Merged tire | `合体轮胎` | **TPU** | 4 | **Roller-skating variant, not used for walking**; v2.1 merged rim + tire |
| 29 | Roller blades | `roller_blade` | PLA | 2 | **Roller-skating variant, not used for walking** |
| 30 | Motor support | `motor_support` | PLA | 1 | |
| 31 | Power support | `power_support` | PLA | 1 | |
| 32 | Banana PCB locker | `banana_pcb_locker` | PLA | 1 | |
| 33 | Bearing roll | `bearing_roll` | PLA | 2 | Can be replaced with CNC aluminum for rigidity |

### II. Purchased Components (21 items)

| # | Item | Qty | Unit Price (CNY) | Remarks / Purchase Links |
|---|---|---|---|---|
| 34 | Radxa Zero 3W SBC | 1 | ~309 | **Buy 1 GB or 2 GB non-eMMC SKU**, OS installs on #35 microSD card; use official channels only: [ALLNET China Taobao Store](https://allnetchina.taobao.com), Radxa Official Taobao / JD stores (corrected 2026-10-12; see [Main Repo Electronic Purchase Guide](https://github.com/fanhao375/microduck-replica/blob/master/docs/电控采购清单.md#该买哪个配置)). 309 CNY was the price paid by 机械行者Robo at ordering time; config of original link was unverified |
| 35 | 64GB MicroSD Card | 1 | ~60 | System drive for non-eMMC SBC, **required**; 32 GB is also sufficient; choose reputable brand A1/A2 cards |
| 36 | RPI Robot HAT PCB | 1 | — | Officially open-sourced, fabricate via JLCPCB; or [wire directly without HAT](https://github.com/fanhao375/microduck-replica/blob/master/docs/不打HAT.md) |
| 37 | imu_to_dxl PCB | 1 | — | Custom designed by main repo, [hardware/imu_to_dxl](https://github.com/fanhao375/microduck-replica/tree/master/hardware/imu_to_dxl) |
| 38 | Feetech HD-1910 Servos | 15 | — | Available via group buys in [main repo](https://github.com/fanhao375/microduck-replica); listed as **HD-1910-C001** |
| 39 | Feetech URT-2 Debug Board | 1 | ~45 | [Taobao 575365901461](https://item.taobao.com/item.htm?id=575365901461&skuId=5435424470243) |
| 40 | NP-F550 Battery | 1 | ~17 | 2S Li-ion; [Tmall 658975825526](https://detail.tmall.com/item.htm?id=658975825526&skuId=4925738602652) |
| 41 | Battery Mount / Sled | 1 | ~83 | [Tmall 714898043960](https://detail.tmall.com/item.htm?id=714898043960&skuId=5173334659309) |
| 42 | 2.5mm Banana Plug PCB Gold-Plated | 2 | ~1.6 | [Taobao 1066300439603](https://item.taobao.com/item.htm?id=1066300439603&skuId=6116801109787) |
| 43 | Banana PCB | 1 | — | Fabricate via JLCPCB |
| 44 | IMX219 Camera Module | 1 | ~46.8 | [Tmall 775872575316](https://detail.tmall.com/item.htm?id=775872575316) |
| 45 | VL53L8CX ToF Module | 1 | ~49.5 | [Taobao 737603917521](https://item.taobao.com/item.htm?id=737603917521&skuId=5090650052053) |
| 46 | Speaker | 1 | ~3.8 | Required only if using HAT audio; [Taobao 902489608878](https://item.taobao.com/item.htm?id=902489608878&skuId=5925223242747) |
| 47 | Bearings 10×15×3 mm | 3 | ~2.8 | [Taobao 670727787832](https://item.taobao.com/item.htm?id=670727787832) |
| 48 | Bearings 16×22×4 mm | 11 | ~3.5 | [Taobao 539024647147](https://item.taobao.com/item.htm?id=539024647147&skuId=5716548727712) |
| 49 | Bearings 6×12×3 mm | 4 | ~0.88 | For roller-skating variant only, not needed for walking; [Taobao 963037239628](https://item.taobao.com/item.htm?id=963037239628&skuId=6068333830994) |
| 50 | Screws M2×5 | 1 pack | ~3.05 | [Tmall 637524754721](https://detail.tmall.com/item.htm?id=637524754721&skuId=5802482233046) |
| 51 | Screws M2×6 | 1 pack | ~4.05 | Same vendor: [Tmall 637524754721](https://detail.tmall.com/item.htm?id=637524754721&skuId=5802482233047) |
| 52 | Screws M2.5×6 | 1 pack | ~3.93 | Same vendor: [Tmall 637524754721](https://detail.tmall.com/item.htm?id=637524754721&skuId=6180818899668) |
| 53 | Screws M2.5×8 | 1 pack | ~2.08 | Same vendor: [Tmall 637524754721](https://detail.tmall.com/item.htm?id=637524754721&skuId=4572694449141) |
| 54 | Loctite Threadlocker 243 | 1 | ~9 | [Taobao 1056442610986](https://item.taobao.com/item.htm?id=1056442610986&skuId=6099342537028) |

> Exact screw counts per type can be found in [Main Repo Fastener Derivation](https://github.com/fanhao375/microduck-replica/blob/master/docs/紧固件反推.md). Total BOM cost is **approximately 828 CNY** (excluding 15 servos, HAT PCB, and IMU PCB; prices reflect costs at time of original order by 机械行者Robo).

---

## Project Cost & Open-Source Initiative

> 🦆 **Everyone can build their own MicroDuck!**

**💰 Project Cost**: Aside from the 15 servos, HAT PCB, and IMU PCB, the rest of the hardware costs approximately **828 CNY**. Servos, HAT, and IMU boards can be sourced via community group-buys in the [GitHub Project](https://github.com/fanhao375/microduck-replica), or ordered directly from JLCPCB and component vendors.

Installation videos have started rolling out on Bilibili ([Video Assembly Tutorial](#video-assembly-tutorial)), with calibration and tuning guides to follow to help everyone assemble and debug their MicroDuck.

**🤖 Why Open Source?** We hope more people can access and learn embodied AI, robot control, and reinforcement learning at lower cost, getting hands-on from scratch. If this project helps you, a like or star ⭐ is the best encouragement ❤️!

> 🔗 GitHub: https://github.com/fanhao375/microduck-replica  
> 📕 Xiaohongshu: [机械行者](https://www.xiaohongshu.com/user/profile/5ad950114eacab046016f038) · 🎵 Douyin: [机械行者Robo](https://www.douyin.com/user/MS4wLjABAAAArLa_6yE3GE-AoRURoQnIHdbbI7yM-GHhzlgLZ-XbeYE) · Bilibili: [机械行者Robo](https://space.bilibili.com/312747174)

---

## 3D Printing

**[`打印/microduck-飞特版-BambuStudio.3mf`](打印/microduck-飞特版-BambuStudio.3mf)** — Bambu Studio project pre-arranged on build plates by 机械行者Robo, edition **2026-09-15**.

**Note: This is not the full v2.1 print package.** The plates still contain 4 individual rims and 4 tires, without the v2.1 merged tire. If you are building the newer roller-skating variant, please export `合体轮胎` (merged tire) from [v2.1 source files](https://github.com/fanhao375/microduck-replica-cad/releases/tag/v2.1) and slice it with TPU, avoiding duplicate printing of legacy rims/tires. Slicing settings:

| Parameter | Value |
|---|---|
| Printer | Bambu Lab **P2S**, 0.4 mm nozzle |
| Filament | PLA Basic |
| Layer Height | 0.2 mm |
| Plates | **5 plates**, 52 objects — objects from the 09-15 project, not the full v2.1 inventory |

<table>
<tr>
<td align="center"><img src="打印/盘1.png" width="180"><br><sub>Plate 1</sub></td>
<td align="center"><img src="打印/盘2.png" width="180"><br><sub>Plate 2</sub></td>
<td align="center"><img src="打印/盘3.png" width="180"><br><sub>Plate 3</sub></td>
<td align="center"><img src="打印/盘4.png" width="180"><br><sub>Plate 4</sub></td>
<td align="center"><img src="打印/盘5.png" width="180"><br><sub>Plate 5</sub></td>
</tr>
</table>

**How to use**: First verify your servo version, required parts, and materials. Open the project in Bambu Studio, review plate layouts, and slice. Flexible parts such as the soft jaw, soft mouth top, and tires must be printed with **TPU** according to the BOM rather than default PLA. When using other 3D printers, ensure your slicer supports `.3mf` import and tune print parameters for your machine.

Filaments, screws, and heat-set inserts purchasing info is in the [Main Repo Mechanical Purchase Guide](https://github.com/fanhao375/microduck-replica/blob/master/docs/机械采购清单.md).

---

## Component List (15 Subassemblies)

| # | Subassembly | English Name | Location / Function |
|---|---|---|---|
| 01 | Torso | Torso | Main chassis body, **assembly reference datum for all components**, carries legs, neck, and controller |
| 02 | Left Hip | Left Hip | Base hip pitch joint of left leg, forward/backward leg pitch |
| 03 | Left Hip Roll | Left Hip Roll | Left hip roll joint, lateral leg swing |
| 04 | Left Thigh | Left Thigh | Connects hip joint to lower leg |
| 05 | Left Calf | Left Calf | Connects thigh to ankle joint |
| 06 | Left Ankle & Foot | Left Ankle & Foot | Ankle joint and foot support / rotation |
| 07 | Neck Base | Neck Base | Rotating base connecting neck to torso (Yaw) |
| 08 | Neck Pitch | Neck Pitch | Neck pitch joint |
| 09 | Head Yaw / Roll | Head Yaw / Roll | Head horizontal yaw and roll joint |
| 10 | Head Assembly | Head Assembly | Complete head assembly, housing shell, camera, etc. |
| 11 | Right Hip | Right Hip | Mirror symmetric with 02 |
| 12 | Right Hip Roll | Right Hip Roll | Mirror symmetric with 03 |
| 13 | Right Thigh | Right Thigh | Mirror symmetric with 04 |
| 14 | Right Calf | Right Calf | Mirror symmetric with 05 |
| 15 | Right Ankle & Foot | Right Ankle & Foot | Mirror symmetric with 06 |

## Assembly Sequence

**Follow the sequential order from 01 → 15 for the recommended robot assembly workflow:**

```
1.  01           Torso          — Fix first as the overall reference datum
2.  02 → 06      Left Leg       Left Hip → Left Hip Roll → Left Thigh → Left Calf → Left Ankle & Foot
3.  07 → 10      Neck & Head    Neck Base → Neck Pitch → Head Yaw/Roll → Head Assembly
4.  11 → 15      Right Leg      Right Hip → Right Hip Roll → Right Thigh → Right Calf → Right Ankle & Foot
```

**For detailed step-by-step instructions, illustrations, and cautions for each step, see the** [Assembly Installation Manual PDF](安装说明书/microduck装配安装说明书.pdf).

## Video Assembly Tutorial

**[Bilibili series "MicroDuck Assembly from Scratch"](https://space.bilibili.com/312747174/lists/9279084?type=season)** — recorded by 机械行者Robo, walking through the parts list and assembling one component per episode. Note: the video builds subassemblies (legs, torso, neck, head) individually before final integration, which differs slightly from the strictly sequential order above. Compare both during assembly. 6 of 8 episodes released as of 2026-10-12:

| Ep | Content | Duration |
|---|---|---|
| [1](https://www.bilibili.com/video/BV1RoHX68EFV/) | Parts List: head, neck, left/right legs, feet, and servo hardware | 1:32 |
| [2](https://www.bilibili.com/video/BV1Xppb6tECr/) | Calf assembly | 2:21 |
| [3](https://www.bilibili.com/video/BV1ycpb6yEwB/) | Thigh assembly | 5:13 |
| [4](https://www.bilibili.com/video/BV1Kwpg6wE9G/) | Torso subassembly | 2:29 |
| [5](https://www.bilibili.com/video/BV1EEpg6nEkD/) | Neck assembly | 0:40 |
| [6](https://www.bilibili.com/video/BV1aKpE6hEzj/) | Head assembly | 5:50 |

---

## Component Diagrams

<table>
<tr>
<td align="center"><img src="组件图/01-躯干主体.png" width="200"><br><sub><b>01</b> Torso</sub></td>
<td align="center"><img src="组件图/02-左髋.png" width="200"><br><sub><b>02</b> Left Hip</sub></td>
<td align="center"><img src="组件图/03-左髋roll.png" width="200"><br><sub><b>03</b> Left Hip Roll</sub></td>
<td align="center"><img src="组件图/04-左大腿.png" width="200"><br><sub><b>04</b> Left Thigh</sub></td>
</tr>
<tr>
<td align="center"><img src="组件图/05-左小腿.png" width="200"><br><sub><b>05</b> Left Calf</sub></td>
<td align="center"><img src="组件图/06-左踝脚.png" width="200"><br><sub><b>06</b> Left Ankle & Foot</sub></td>
<td align="center"><img src="组件图/07-颈根.png" width="200"><br><sub><b>07</b> Neck Base</sub></td>
<td align="center"><img src="组件图/08-颈俯仰.png" width="200"><br><sub><b>08</b> Neck Pitch</sub></td>
</tr>
<tr>
<td align="center"><img src="组件图/09-头yawroll.png" width="200"><br><sub><b>09</b> Head Yaw/Roll</sub></td>
<td align="center"><img src="组件图/10-头部总成.png" width="200"><br><sub><b>10</b> Head Assembly</sub></td>
<td align="center"><img src="组件图/11-右髋.png" width="200"><br><sub><b>11</b> Right Hip</sub></td>
<td align="center"><img src="组件图/12-右髋.png" width="200"><br><sub><b>12</b> Right Hip Roll</sub></td>
</tr>
<tr>
<td align="center"><img src="组件图/13-右大腿.png" width="200"><br><sub><b>13</b> Right Thigh</sub></td>
<td align="center"><img src="组件图/14-右小腿.png" width="200"><br><sub><b>14</b> Right Calf</sub></td>
<td align="center"><img src="组件图/15-右踝脚.png" width="200"><br><sub><b>15</b> Right Ankle & Foot</sub></td>
<td align="center"><img src="组件图/10-头部总成爆炸2.png" width="200"><br><sub>Head Assembly (Exploded)</sub></td>
</tr>
</table>

<div align="center">
  <img src="组件图/零件明预览.png" alt="All parts overview" width="820"><br>
  <sub>All parts overview</sub>
</div>

---

## File Inventory

### Assemblies (16 `.SLDASM` files)

`00-microduck装配体` is the main assembly; the 15 below are subassemblies:

```
00-microduck装配体      70.3 MB      08_颈俯仰               0.3 MB
01_躯干主体             20.5 MB      09_头yaw-roll          0.7 MB
02_左髋yaw-roll         2.5 MB      10_头部总成             22.2 MB
03_左髋roll             3.8 MB      11_右髋yaw-roll         2.5 MB
04_左大腿               1.9 MB      12_右髋roll             3.8 MB
05_左小腿               1.9 MB      13_右大腿               2.0 MB
06_左踝脚               9.3 MB      14_右小腿               1.8 MB
07_颈根                 0.1 MB      15_右踝脚               9.3 MB
```

### Parts (40 `.SLDPRT` files)

| Category | Parts |
|---|---|
| **Torso / Shell** | `trunk_base_躯干底座` · `left_shell_左壳` · `right_shell_右壳` · `power_support_电源支架` · `banana_pcb_locker_香蕉形PCB锁扣` |
| **Legs** | `leg_腿部` · `left_upper_leg_左上腿` · `right_upper_leg_右上腿` · `hip_l_髋部左` · `yaw2roll_偏航转横滚` · `yaw_roll_motion_偏航横滚运动` · `01-upper_leg_rigidity_plate_上腿加固板` |
| **Ankles / Feet** | `ankle_left_脚踝左` · `ankle_right_脚踝右` · `foot_left_左脚` · `foot_right_右脚` · `sole_left_左脚底` · `sole_right_右脚底` |
| **Neck / Head** | `neck_颈部` · `neck_pitch_颈部俯仰` · `top_head_shell_头部上壳` · `bottom_head_shell_头部下壳` · `face_part_面部零件` · `jaw_下巴` · `jaw_soft_软下巴` · `soft_mouth_top_软嘴顶部` · `noenoeil_眼睛` |
| **Camera** | `m12_lens_holder_M12镜头座` · `lens_镜头` |
| **PCBs** | `3D_PCB1_2026-09-08` (imu_to_dxl, 2026-09-08 version) · `elec_rpi_robot_hat_pcb_树莓派机器人HAT电路板` · `pcb__raspberry_pi_zero_2_w_树莓派Zero2W电路板` |
| **Standard / Off-the-shelf** | `舵机xl330-288` · `xl330-m288-t1` · `xl330-m288-t2` · `轴承16×22×4` · `bearing_roll_轴承滚轮` · `M2铜柱` · `motor_support_电机支架` · `np_f970_NPF970电池` |

### Two Naming Caveats to Note

- **`np_f970_NPF970电池`** — The filename inherits upstream's `np_f970`, but the **actual battery used is NP-F550**.
  The bounding box measured from the upstream model is **70.8 × 38.6 × 20.6 mm**, exactly the size of an F550/F570; a real NP-F970 is ~60 mm thick and **will not fit physically, and its 300 g weight would consume one-third of the robot's entire weight budget**. Details in [Main Repo BOM Battery Errata](https://github.com/fanhao375/microduck-replica/blob/master/BOM.md).
- **`pcb__raspberry_pi_zero_2_w`** — Similarly a placeholder name from upstream; the **actual SBC is a Radxa Zero 3W** (RK3566), which shares the Pi Zero form factor. See [Main Repo Hardware Architecture Reverse Engineering](https://github.com/fanhao375/microduck-replica/blob/master/docs/硬件方案逆向.md).

---

## General Assembly Precautions (From the Manual)

- Check off all part quantities and specifications against the BOM before assembly; verify **M2 / M2.5** screws and fasteners are complete.
- **Servo joint parts: power on and center (neutral position) each servo before tightening screws**, preventing travel range offset.
- Tighten screws in a **diagonal cross pattern progressively** to avoid asymmetric stress and part deformation; do not overtighten into plastic threads.
- **Symmetric parts (hips / thighs / calves / ankles / feet) must be verified for Left vs. Right orientation** before assembling.
- Route and secure wiring neatly with adequate slack for joint motion; never pinch, clamp, or twist wires.
- After completing each moving joint, rotate it manually to verify there is no binding, interference, or friction.
- Check all electrical connections, insulation, and polarity before the first power-up.

**Recommended Tools**: Phillips / Hex screwdrivers · Tweezers · Threadlocker · Servo centering tester or controller.

---

## Disclaimer & License

> ⚠️ **This is a third-party replica project, not an official design.** It is not affiliated with or endorsed by Pollen Robotics.

These CAD models were reconstructed as editable SolidWorks parametric models based on the publicly released STL meshes in [`pollen-robotics/microduck_rl`](https://github.com/pollen-robotics/microduck_rl). The upstream 3D models are licensed under **CC BY-NC-SA**, so this repository's CAD files, as derivative works, are likewise distributed under **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)**:
**Attribution · Non-Commercial · Share-Alike**.

- **CAD models and manuals copyright belongs to 「机械行者Robo」**; retain attribution in any redistribution.
- Documentation text is likewise licensed under CC BY-NC-SA 4.0.
- Microduck is a commercial product of Pollen Robotics; this repository provides no official support.

**If you find any issues**, please open an [issue](../../issues) or leave a message on the author's accounts above.
