---
id: "01-site-measurements-and-coords"
title: "Lot 3152 — Site Measurements, Architectural Reconciliations & 2D/3D Coordinate System"
domain: "geometry-and-coordinates"
canonical_topics:
  - "Compass orientation and site boundaries"
  - "Architectural tape-measure reconciliations (50' width, 43.2' depth, 96.7'/108.7' lot depth)"
  - "Canonical 2D CAD coordinate system (wx East-West, wy North-South in feet)"
  - "4-Zone property spatial breakdown"
  - "Master 45-item reconciled measurement schedule"
  - "Interactive 2D CAD (cad_architectural_blueprint_3152.html) & 3D WebGL (model_3d_3152.html) architecture"
coordinates_covered: "wx = -1.0' to 115.0', wy = 0.0' to 50.0'"
keywords: ["wx", "wy", "coordinates", "measurements", "lot width", "lot depth", "footprint", "slab-on-grade", "garage projection", "porch", "driveway", "patio", "Zone 1", "Zone 2", "Zone 3", "Zone 4", "CAD", "3D model"]
related_files:
  - "docs/measurements.csv"
  - "cad_architectural_blueprint_3152.html"
  - "model_3d_3152.html"
---

# 01 · Site Measurements, Architectural Reconciliations & Coordinate System

> **Single Source of Truth for Geometry & Coordinates:** This file is the canonical reference for all lot dimensions, structural reconciliations, `(wx, wy)` coordinates, and the 45-item measurement schedule (also available in machine-readable CSV format at [`docs/measurements.csv`](./measurements.csv)).

---

## 1. Compass Orientation & Site Context

* **Property Identifier**: Lot 3152 (2-Story Single-Family Residence with attached 2-car garage; Jared & Melinda Carter).
* **Foundation Type**: Slab-on-grade construction (**no basement and zero window wells anywhere on the property**).
* **Primary Compass Orientation**:
  * **Facing the Front of the House from the Street**: Looking **West** (`wx = 108.7'` to `0.0'`).
  * **Looking Out the Front Door toward the Street**: Looking **East** (`wx = 0.0'` to `108.7'`).
  * **North Side of Property** *(Right side when looking at the front of the house; `wy = 0.0'` to `9.0'`)*: Narrow $9.0\text{ ft}$ wide corridor, continuous $43.2\text{ ft}$ stucco house/garage wall, exterior water spigot (`wx = 51.0'`), pink/orange wooden survey stakes along `wy = 0.0'`, **compacted road base utility/trailer pad** inside the gate (`wx = 30.0'–70.0'`), **white decorative rock** East of the gate (`wx = 70.0'–96.7'`), and planned **Double-Swing Vehicle Gate** (`wx = 70.0'`). **North Neighbor (`wy < 0.0'`): Completely empty bare dirt.**
  * **South Side of Property** *(Left side when looking at the front of the house; `wy = 41.0'` to `50.0'`)*: Narrow $9.0\text{ ft}$ wide corridor, $29.7\text{ ft}$ main house wall to front door plane (`wx = 59.7'`), covered front porch with stone-base column (`3152` address plaque at `wx = 65.7'`), electric and gas meters (`wx = 51.0'–54.5'`), **completely open $3'\times 3'$ AC condenser unit (`wx = 45.0'–48.0'` — no cover or shroud)**, **continuous $2.0\text{ ft}$ wide planting bed** down the entire South fence and continuing in the front yard all the way to the green utility box (`wx = 0.0'–96.7'`), **continuous $4.0'\text{+}$ wide grass strip** running under the gate into the front yard, and planned **Single-Swing Pedestrian ("Human") Gate** (`wx = 57.5'`). **South Neighbor (`wy > 50.0'`): White decorative rocks.**
  * **West Side of Property** *(Rear; `wx = 0.0'` to `30.0'`)*: Backyard, $21.0\text{ ft} \times 12.5\text{ ft}$ concrete patio (`wx = 17.5'–30.0', wy = 20.0'–41.0'`), and a $50.0\text{ ft}$ wide precast concrete perimeter wall (`wx = -1.0'–0.0'`, 5 panel bays at $10.0\text{ ft}$ on-center).
  * **East Side of Property** *(Front; `wx = 59.7'` to `108.7'`)*: Concrete driveway (`18.0' W × 23.5' L`), front porch walkway (`3.5' W`), SE front lawn (`555.0 sq ft`), NE white rock strip (`287.3 sq ft`), $4.0\text{ ft}$ city sidewalk, **white decorative rock $6.0\text{ ft}$ park strips** (`192.0 sq ft`), $2.0\text{ ft}$ curb/gutter, and residential street.

---

## 2. Key Architectural Reconciliations (From Field Measurements + Photos)

1. **North–South Width Reconciliation ($50.0\text{ ft}$ Lot Width)**:
   * **Foundation Blueprint Math**:
     $$\text{Lot Width} = 9.0\text{ ft (North Setback)} + 32.0\text{ ft (House Foundation)} + 9.0\text{ ft (South Setback)} = 50.0\text{ ft}$$
   * **Why Front Exterior Measurements Summed to $33.0\text{ ft}$ ($20.5\text{ ft}$ Garage + $12.5\text{ ft}$ Porch)**:
     * On the structural foundation, the garage is **$20.0\text{ ft}$ wide** ($wy = 9.0\text{ ft}$ to $29.0\text{ ft}$) and the front porch/entry is **$12.0\text{ ft}$ wide** ($wy = 29.0\text{ ft}$ to $41.0\text{ ft}$), totaling **$32.0\text{ ft}$**.
     * The decorative stone masonry veneer flares outward by $0.25\text{ ft}$ ($3\text{ in}$) on the North and South garage corners (making the exterior stone-to-stone garage width **$20.5\text{ ft}$**), and the stone base on the `3152` porch column flares $0.25\text{ ft}$ South (making the porch measurement across to the garage wall **$12.5\text{ ft}$**).

2. **East–West Depth Reconciliation ($43.2\text{ ft}$ Max House Depth)**:
   * **Continuous North Wall**: Measures **$43.2\text{ ft}$** from the NW rear corner ($wx = 30.0\text{ ft}$) to the NE front garage corner ($wx = 73.2\text{ ft}$).
   * **Why Split South/East Measurements Summed to $43.5\text{ ft}$ ($\approx 30.0\text{ ft}$ South Wall + $13.5\text{ ft}$ Garage Projection)**:
     * The main house structural depth along the South wall (from the SW rear corner to the Front Door wall plane) is **$29.7\text{ ft}$** (nominally $\approx 30.0\text{ ft}$).
     * The garage projects **$13.5\text{ ft}$** Eastward from the Front Door wall plane ($29.7\text{ ft} + 13.5\text{ ft} = 43.2\text{ ft}$ structural).
     * The front stone veneer adds **$0.3\text{ ft}$ ($3.5\text{ in}$)** on the front face of the garage ($wx = 73.2\text{ ft}$ to $73.5\text{ ft}$), explaining the $43.5\text{ ft}$ tape total.

3. **Total Lot Depth Reconciliation ($96.7\text{ ft}$ to Sidewalk / $108.7\text{ ft}$ to Curb)**:
   * $\text{Backyard Depth } (30.0\text{ ft}) + \text{North House/Garage Wall } (43.2\text{ ft}) + \text{Driveway Length } (23.5\text{ ft}) = 96.7\text{ ft}$ from the inside face of the West precast wall to the West edge of the City Sidewalk.
   * Adding the $4.0\text{ ft}$ City Sidewalk + $6.0\text{ ft}$ Park Strip + $2.0\text{ ft}$ Curb & Gutter equals **$108.7\text{ ft}$** to the street line.

---

## 3. Canonical 2D CAD Coordinate System (`wx`, `wy` in Feet)

All programmatic drawings and calculations use a locked 1:1 coordinate system in **Feet**, where $1.0\text{ ft} = 12.0\text{ SVG vector units}$ ($1\text{ vector unit} = 1\text{ inch}$):

* **Origin $(0.0, 0.0)$**: Northwest corner of the unpaved backyard (inside East face of the West precast concrete wall at the North property line).

### East–West Axis (`wx`, increasing West $\rightarrow$ East)
* $wx = -1.0\text{ ft}$ to $0.0\text{ ft}$: West Rear Precast Concrete Wall ($1.0\text{ ft}$ thick; $1.5\text{ ft} \times 1.5\text{ ft}$ fluted columns at $wy = 0, 10, 20, 30, 40, 50\text{ ft}$).
* $wx = 0.0\text{ ft}$ to $4.0\text{ ft}$: Western Back Wall Mulch Bed ($+6"$ flush paver at $wx = 4.0'\text{–}4.5' = 4.5\text{ ft}$ to grass; `S1`–`S5` trees at $wx = 2.0'$, `J1`–`J4` junipers at $wx = 1.75'$, 10-spot under-story at $wx = 2.95'$).
* $wx = 0.0\text{ ft}$ to $17.5\text{ ft}$: Unpaved backyard depth West of the patio ($17.5\text{ ft}$ total; $13.0\text{ ft}$ open lawn between $wx = 4.5'$ paver and $wx = 17.5'$ patio).
* $wx = 17.5\text{ ft}$ to $30.0\text{ ft}$: Backyard Concrete Patio ($12.5\text{ ft}$ deep; N–S control joint at $wx = 23.75\text{ ft}$ dividing it into two $6.25\text{ ft}$ halves; Awning outer West corner pillars `P1` & `P2` at $wx = 18.0'$; Lighted ceiling fans `F1` & `F2` at $wx = 23.75'$).
* $wx = 27.0\text{ ft}$ to $30.0\text{ ft}$: **Rear House Wall Compacted Road Base Sidewalk/Path** ($3.0\text{ ft}$ wide $\times 11.0\text{ ft}$ long $= 33.0\text{ sq ft}$ at $wy = 9.0\text{ ft}$ to $20.0\text{ ft}$; bordered on the West at $wx = 26.5'\text{–}27.0'$ by a $6"$ flush Holland paver mow strip).
* $wx = 28.5\text{ ft}$ to $30.0\text{ ft}$: Rear Sliding Glass Door Concrete Step ($1.5\text{ ft}$ deep $\times 6.0\text{ ft}$ wide at $wy = 21.5\text{ ft}$ to $27.5\text{ ft}$).
* $wx = 30.0\text{ ft}$: Rear (West) House Structural Wall & 2nd-Floor Awning Ledger Line.
* $wx = 45.0\text{ ft}$ to $48.0\text{ ft}$: **Completely Open AC Condenser Pad** ($3.0\text{ ft} \times 3.0\text{ ft}$ on South wall at $wy = 41.0\text{ ft}$ to $44.0\text{ ft}$ — **no cover or shroud**).
* $wx = 51.0\text{ ft}$: Exterior Hose Bib (Water Spigot) & Irrigation Point of Connection (`1" Febco 765 PVB` at $wx = 51.0', wy = 8.6'$; Manifold `M1` at $wx = 51.0', wy = 7.8'$).
* $wx = 51.0\text{ ft}$ to $54.5\text{ ft}$: Gas & Electric Meters on South wall ($wy = 41.0\text{ ft}$ to $42.1\text{ ft}$).
* $wx = 57.5\text{ ft}$: **South Pedestrian ("Human") Gate Line** ($2.2\text{ ft}$ West of SE stucco corner onto flat stucco; $8.2\text{ ft}$ West of front porch pillar). Both the $4.0'\text{+}$ grass strip ($wy = 43.5'\text{–}47.5'$) and $2.0\text{ ft}$ South bed ($wy = 48.0'\text{–}50.0'$) continue right under the gate.
* $wx = 59.7\text{ ft}$: Front Door Wall Plane & SE Stucco House Corner.
* $wx = 59.7\text{ ft}$ to $65.7\text{ ft}$: Covered Front Porch Slab ($6.0\text{ ft}$ deep).
* $wx = 64.2\text{ ft}$ to $65.7\text{ ft}$: `3152` Front Porch Pillar with Stone Veneer Base ($wy = 39.5\text{ ft}$ to $41.25\text{ ft}$).
* $wx = 65.2\text{ ft}$ to $67.2\text{ ft}$: Front Porch Foundation Hyacinth Bed ($2.0\text{ ft}$ deep $\times 12.0\text{ ft}$ long at $wy = 31.0'\text{–}43.0'$).
* $wx = 65.7\text{ ft}$ to $81.0\text{ ft}$: Front Porch Concrete Walkway Extension ($3.5\text{ ft}$ wide at $wy = 29.0\text{ ft}$ to $32.5\text{ ft}$).
* $wx = 70.0\text{ ft}$: **North Double-Swing Vehicle Gate Line** ($3.2\text{ ft}$ West of NE garage face; $1.2\text{ ft}$ behind the $2.0\text{ ft}$ stone wrap). Exact boundary between the **North Side Compacted Road Base Pad** ($wx = 30.0'\text{–}70.0'$) and **Front/Side White Decorative Rock** ($wx = 70.0'\text{–}96.7'$).
* $wx = 71.2\text{ ft}$ to $73.2\text{ ft}$: NE Garage Corner Stone Wrap Return ($2.0\text{ ft}$ along North wall).
* $wx = 73.2\text{ ft}$: NE & SE Garage Structural Front Wall ($wx = 73.2'\text{–}73.5'$ stone veneer).
* $wx = 73.2\text{ ft}$ to $96.7\text{ ft}$: Concrete Driveway ($23.5\text{ ft}$ long; E–W control joints at $wx = 81.0\text{ ft}$ and $88.85\text{ ft}$).
* $wx = 83.0\text{ ft}, wy = 39.5\text{ ft}$: **Front Yard Specimen Tree — Norwegian Sunset® Maple** centered in the SE Front Lawn inside a $6.0\text{ ft}$ diameter ($3.0\text{ ft}$ radius) mulched root-flare ring ($wx = 80.0'\text{–}86.0', wy = 36.5'\text{–}42.5'$) bordered by an octagonal $45^\circ$ Holland paver mow strip.
* $wx = 93.0\text{ ft}$ to $96.4\text{ ft}$: Green PacifiCorp Utility Transformer Box ($wy = 45.5'\text{–}48.5'$).
* $wx = 96.7\text{ ft}$ to $100.7\text{ ft}$: City Sidewalk ($4.0\text{ ft}$ wide).
* $wx = 100.7\text{ ft}$ to $106.7\text{ ft}$: **White Decorative Rock Landscaping Park Strips ($6.0\text{ ft}$ deep)** & Flared Driveway Apron.
* $wx = 106.7\text{ ft}$ to $108.7\text{ ft}$: Concrete Curb & Gutter ($2.0\text{ ft}$ wide).
* $wx = 108.7\text{ ft}$ to $115.0\text{ ft}$: Residential Street (East).

### North–South Axis (`wy`, increasing North $\rightarrow$ South)
* $wy < 0.0\text{ ft}$: **North Neighbor Property — Completely Empty Bare Dirt**.
* $wy = 0.0\text{ ft}$: North Property Line ($70.0\text{ lin ft}$ North white vinyl fence from $wx = 0.0'\text{–}70.0'$).
* $wy = 0.0\text{ ft}$ to $8.5\text{ ft}$ (Backyard, $wx = 4.0'\text{–}27.0'$): **Northern Backyard Raised Garden Bed Zone** ($1.0'$ N road base gap + $6.0'$ N–S cedar box [$wy = 1.0'\text{–}7.0'$] + $1.0'$ S road base gap + $6"$ flush paver [$wy = 8.0'\text{–}8.5'$]).
* $wy = 0.0\text{ ft}$ to $9.0\text{ ft}$ (North Side Yard): **Narrow North Side Yard Setback ($9.0\text{ ft}$ wide)** — compacted road base pad inside gate ($wx = 30.0'\text{–}70.0' = 360.0\text{ sq ft}$), white decorative rock East of gate ($wx = 70.0'\text{–}96.7'$).
* $wy = 9.0\text{ ft}$: North House/Garage Structural Wall.
* $wy = 9.0\text{ ft}$ to $20.0\text{ ft}$: Rear House Stucco Wall North of Patio ($11.0\text{ ft}$ wide, bordered by $3.0'\text{ W}$ compacted road base path at $wx = 27.0'\text{–}30.0'$).
* $wy = 11.0\text{ ft}$ to $27.0\text{ ft}$: 2-Car Overhead Garage Door ($16.0\text{ ft}$ wide).
* $wy = 11.0\text{ ft}$ to $29.0\text{ ft}$: Main Concrete Driveway ($18.0\text{ ft}$ wide; N–S control joints at $wy = 17.0\text{ ft}$ and $23.0\text{ ft}$).
* $wy = 20.0\text{ ft}$ to $41.0\text{ ft}$: Backyard Concrete Patio ($21.0\text{ ft}$ wide; E–W control joint at $wy = 30.5\text{ ft}$; North entry/grill zone $wy = 20.0'\text{–}29.5'$, South lounge/fire-table zone $wy = 29.5'\text{–}41.0'$).
* $wy = 29.0\text{ ft}$: South Garage Structural Wall / North Edge of Front Porch.
* $wy = 29.0\text{ ft}$ to $32.5\text{ ft}$: South Porch Concrete Walkway Panel ($3.5\text{ ft}$ wide alongside driveway).
* $wy = 29.0\text{ ft}$ to $41.0\text{ ft}$: Covered Front Porch Structural Width ($12.0\text{ ft}$ foundation; $12.5\text{ ft}$ exterior with stone base; hanging porch swing at $wy = 35.8'\text{–}40.0'$).
* $wy = 41.0\text{ ft}$: South House Structural Wall (Patio South edge is flush with this wall).
* $wy = 41.0\text{ ft}$ to $50.0\text{ ft}$: **Narrow South Side Yard Setback ($9.0\text{ ft}$ wide)** — $2.0\text{ ft}$ house wall/open-AC buffer + $6"$ paver ($wy = 41.0'\text{–}43.5'$), $4.0'\text{+}$ continuous lawn strip ($wy = 43.5'\text{–}47.5'$), and continuous $2.0\text{ ft}$ South planting bed + $6"$ paver ($wy = 47.5'\text{–}50.0'$).
* $wy = 50.0\text{ ft}$: South Property Line ($57.5\text{ lin ft}$ South white vinyl fence from $wx = 0.0'\text{–}57.5'$).
* $wy > 50.0\text{ ft}$: **South Neighbor Property — White Decorative Rocks**.

---

## 4. All 4 Property Zones — Spatial Summary Table

| Property Zone | Reconciled Dimensions | Coordinates (`wx`, `wy`) | Area / Key Breakdown |
| :--- | :--- | :--- | :--- |
| **Total Lot Footprint** | `50.0' W (N–S) × 96.7' D` to Sidewalk (`108.7'` to Curb) | `wx = 0.0'–96.7'` (`108.7'`), `wy = 0.0'–50.0'` | `4,835.0 sq ft` to Sidewalk (`5,435.0 sq ft` to Curb; `~0.11 acres`) — Slab-on-grade |
| **Zone 1: Backyard & Patio** | `50.0' W × 30.0' D` | `wx = 0.0'–30.0'`, `wy = 0.0'–50.0'` | `1,500.0 sq ft` total: `262.5 sq ft` patio (`21'×12.5'`) + `1,237.5 sq ft` unpaved (`679.0 sq ft` main lawn + `200.0 sq ft` W. bed + `90.0 sq ft` 5 cedar boxes + `94.0 sq ft` garden road-base paths + `33.0 sq ft` rear path + S. bed/pavers) |
| **Zone 2A: North Side Yard** | `9.0' W × 43.2' D` (`40.0'` inside gate) | `wx = 30.0'–73.2'`, `wy = 0.0'–9.0'` | `388.8 sq ft` raw: **`360.0 sq ft` Compacted Road Base Pad** inside `wx = 70.0'` gate + **`28.8 sq ft` White Decorative Rock** East of gate (`wx = 70.0'–73.2'`) |
| **Zone 2B: South Side Yard** | `9.0' W × 29.7' D` (`27.5'` inside gate) | `wx = 30.0'–59.7'`, `wy = 41.0'–50.0'` | `270.0 sq ft` raw (`247.5 sq ft` inside `wx = 57.5'` gate): `2.0'` S. bed (`+6"` paver) + `4.0'+` continuous grass under gate (`110.0 sq ft`) + `2.0'` house/open-AC buffer (`+6"` paver) |
| **Zone 3: Front Yard & Drive** | `50.0' W × 23.5'–37.0' D` | `wx = 59.7'–96.7'`, `wy = 0.0'–50.0'` | `505.3 sq ft` driveway & walk (`21.5'×23.5'`) + `555.0 sq ft` SE front lawn + `24.0 sq ft` porch Hyacinth bed + `78.4 sq ft` S. front bed to green box + **`258.5 sq ft` NE White Rock Strip** (`11.0'×23.5'`) |
| **Zone 4: Street Park Strips, Walk & Curb** | `50.0' W × 12.0' D` | `wx = 96.7'–108.7'`, `wy = 0.0'–50.0'` | `4.0'` City Sidewalk (`wx = 96.7'–100.7'`) + **`192.0 sq ft` White Decorative Rock Park Strips** (`6.0' D` at `wx = 100.7'–106.7'`: `~126 sq ft` South strip + `~66 sq ft` North strip) + `2.0'` Curb/Gutter |

---

## 5. Master 45-Item Reconciled Measurement Schedule

| # | Zone / Category | Measurement Name | User Rough Input | Numeric Value | Unit | Reconciled Exact Spec | CAD Coordinates ($X=\text{wx}, Y=\text{wy}$) | Planning & Visual Notes |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Footprint | Total Lot Width (North–South) | ~50 ft | `50.0` | ft | 50.0 ft | `X: 0.0..96.7 \| Y: 0.0..50.0` | Matches 5 precast wall panels across West back wall ($10.0\text{ ft}$ O.C.) and $9.0'\text{ N} + 32.0'\text{ House} + 9.0'\text{ S}$. North neighbor ($Y<0'$) = bare dirt; South neighbor ($Y>50'$) = white rocks. |
| 2 | Footprint | Main House Foundation Width (N–S) | ~32 ft | `32.0` | ft | 32.0 ft | `X: 30.0..59.7 \| Y: 9.0..41.0` | Exact structural foundation width between North ($Y=9.0'$) and South ($Y=41.0'$) side yards (slab-on-grade; no basement). |
| 3 | Footprint | Max House Depth — North Wall (E–W) | 43.2 ft | `43.2` | ft | 43.2 ft | `X: 30.0..73.2 \| Y: 9.0` | Continuous stucco wall from NW back corner ($X=30.0'$) to NE garage corner ($X=73.2'$); no window wells. |
| 4 | Footprint | Main House Depth — South Wall to Door | ~30 ft | `29.7` | ft | 29.7 ft (30.0' nom.) | `X: 30.0..59.7 \| Y: 41.0` | From SW back corner ($X=30.0'$) to SE stucco corner / Front Door plane ($X=59.7'$). Plus $13.5'$ garage = $43.2'$. |
| 5 | Footprint | Total Lot Depth (Rear Wall to Sidewalk) | Derived | `96.7` | ft | 96.7 ft (108.7' to Curb) | `X: 0.0..96.7 (108.7 to Curb)` | $30.0'\text{ Backyard} + 43.2'\text{ North Wall} + 23.5'\text{ Driveway} = 96.7'$ to Sidewalk ($+12.0'\text{ Walk/Strip/Curb} = 108.7'$). |
| 6 | Front | Garage Front Exterior Width (N–S) | 20.5 ft | `20.5` | ft | 20.5 ft (20.0' fdn) | `X: 73.2..73.5 \| Y: 8.75..29.25` | $20.0'\text{ foundation}$ ($Y=9.0'$ to $29.0'$) $+ 0.25'$ ($3\text{ in}$) stone flare on North and South corners $= 20.5'$. |
| 7 | Front | 2-Car Garage Door Width & Wing Walls | Derived | `16.0` | ft | 16.0 ft door (+2.25' wings) | `X: 73.2 \| Y: 11.0..27.0` | Standard $16.0'$ wide overhead garage door centered between two $2.25'$ wide stone-clad wing walls. |
| 8 | Front | Garage Forward Projection from Door | 13.5 ft | `13.5` | ft | 13.5 ft (13.8' w/ stone) | `X: 59.7..73.2 \| Y: 29.0` | Distance from Front Door wall plane ($X=59.7'$) Eastward to front of garage ($X=73.2' + 0.3'\text{ stone}$). |
| 9 | Front | Front Porch Width (North–South) | 12.5 ft | `12.5` | ft | 12.0 ft fdn (12.5' w/ stone) | `X: 59.7..65.7 \| Y: 29.0..41.25` | $12.0'\text{ structural span}$ ($Y=29.0'$ to $41.0'$); stone base on `3152` pillar flares $0.25'$ South for $12.5'$ exterior span. |
| 10 | Front | Covered Front Porch Depth (E–W) | Derived | `6.0` | ft | 6.0 ft | `X: 59.7..65.7 \| Y: 29.0..41.0` | From Front Door wall ($X=59.7'$) Eastward to front edge of `3152` porch pillar ($X=65.7'$). |
| 11 | Front | Porch Pillar to Garage Front Offset | Derived | `7.5` | ft | 7.5 ft | `X: 65.7..73.2 \| Y: 29.0` | Distance the garage extends East past the front face of the `3152` porch pillar ($13.5' - 6.0' = 7.5'$). |
| 12 | Backyard | Backyard Total Depth (House to Wall) | ~30 ft | `30.0` | ft | 30.0 ft | `X: 0.0..30.0 \| Y: 0.0..50.0` | From rear (West) house wall ($X=30.0'$) to inside face of precast concrete perimeter wall ($X=0.0'$). |
| 13 | Backyard | Back Patio Width (N–S), Open 2-Pillar Awning & 2× $52"$ Lighted Fans | 21 ft | `21.0` | ft | 21.0 ft (2 Outer Corner Pillars, 0 House Pillars, Open Sides, 2× $52"$ Fans) | `X: 17.5..30.0 \| Y: 20.0..41.0 (Pillars: X=18.0, Y=20.5 & 40.5; Fans: X=23.75, Y=25.5 & 35.5)` | Spans $Y=20.0'$ to $Y=41.0'$ (flush with SW house corner). Covered by `Option #1C` house-attached solid-roof dark-espresso timber awning + 2× $52"$ outdoor ceiling fans with built-in dimmable warm LED lights (`F1` & `F2`). |
| 14 | Backyard | Back Patio Depth (East–West) | 12.5 ft | `12.5` | ft | 12.5 ft | `X: 17.5..30.0 \| Y: 20.0..41.0` | Extends West from $X=30.0'$ (house ledger) to $X=17.5'$ (outer West slab edge). Divided by center control joint into two $6.25'$ deep halves. |
| 15 | Backyard | Patio Control Joint Quadrants (4x) | Derived | `65.63` | sq.ft. | 10.5 ft W $\times$ 6.25 ft D | `4 Slabs @ 10.5' W x 6.25' D` | Each of the 4 poured concrete patio quadrants measures $10.5'\text{ N–S} \times 6.25'\text{ E–W}$ ($65.625\text{ sq.ft.}$ each). |
| 16 | Backyard | Patio-to-West Wall Dirt Clearance | Derived | `17.5` | ft | 17.5 ft | `X: 0.0..17.5 \| Y: 20.0..41.0` | Unpaved depth West of the concrete patio to the rear precast wall ($30.0' - 12.5' = 17.5'$). |
| 17 | Backyard | Rear House Wall North of Patio | Derived | `11.0` | ft | 11.0 ft | `X: 30.0 \| Y: 9.0..20.0` | Rear house wall section under North window between NW corner ($Y=9.0'$) and Patio ($Y=20.0'$), bordered by $3.0'$ compacted road base path. |
| 18 | Backyard | Total Backyard Width North of Patio | Derived | `20.0` | ft | 20.0 ft | `X: 0.0..30.0 \| Y: 0.0..20.0` | Full width from North edge of patio ($Y=20.0'$) to North property line ($Y=0.0'$): $11.0'\text{ wall} + 9.0'\text{ setback}$. |
| 19 | Backyard | Unpaved Width South of Patio | Derived | `9.0` | ft | 9.0 ft | `X: 0.0..30.0 \| Y: 41.0..50.0` | Patio South edge is flush with SW house corner ($Y=41.0'$), leaving $9.0'$ to South lot line ($Y=50.0'$). |
| 20 | Backyard | Rear Sliding Glass Door & Step | Derived | `6.0` | ft | 6.0 ft W $\times$ 1.5 ft D | `X: 28.5..30.0 \| Y: 21.5..27.5` | Concrete step centered under the $6.0'$ wide sliding patio door ($Y=21.5'$ to $27.5'$, $1.5'$ South of N patio edge). |
| 21 | Backyard | West Precast Concrete Wall Bays (5x) & `5+4` Hybrid Trees | 5 Panels ($10'$ O.C.) | `10.0` | ft O.C. | 5 Bays @ 10.0' O.C. (`5+4` Designer Hybrid) | `X: -1.0..0.0 \| Y: 0,10,20,30,40,50` | 5 panels across the $50.0'$ rear wall with $1.5' \times 1.5'$ fluted columns; frames the `5+4` Designer Hybrid (`S1`–`S5` at $Y=5,15,25,35,45$ + `J1`–`J4` at $Y=10,20,30,40$). |
| 22 | North Side | North Side Yard Setback Width | ~9 ft | `9.0` | ft | 9.0 ft (Narrow Corridor) | `X: 0.0..96.7 \| Y: 0.0..9.0` | Narrow $9.0'$ wide corridor from North house/garage wall ($Y=9.0'$) to North lot line ($Y=0.0'$). Compacted road base inside $X=70.0'$ gate; white decorative rock East of gate ($X=70.0'\text{–}96.7'$). |
| 23 | North Side | North Wall Hose Bib (Spigot) Offset | Derived | `21.0` | ft | 21.0 ft E of NW Corner | `X: 51.0 \| Y: 9.0` | Exterior water spigot at $X=51.0', Y=9.0'$ ($21.0'$ East of NW back corner / $22.2'$ West of NE garage corner). |
| 24 | North Side | NE Garage Corner Stone Wrap Return | Derived | `2.0` | ft | 2.0 ft W $\times$ 0.25 ft N | `X: 71.2..73.2 \| Y: 8.75..9.0` | Front stone veneer wraps $2.0'$ back along North garage wall ($X=71.2'$ to $73.2'$) with downspout at corner. |
| 25 | South Side | South Side Yard Setback Width & Continuous $2.0'$ South Bed | ~9 ft | `9.0` | ft | 9.0 ft (4.0'+ Grass Under Gate + 2.0' Bed to Green Box) | `X: 0.0..96.7 \| Y: 41.0..50.0` | Narrow $9.0'$ wide corridor: $4.0'\text{+}$ grass continues under the $X=57.5'$ gate into the front yard, and the $2.0'$ South planting bed ($Y=48.0'\text{–}50.0'$) continues down the entire South fence and in the front yard to the green box. |
| 26 | South Side | South Side Length (SW Corner to Porch) | Derived | `35.7` | ft | 35.7 ft (36.0' nom.) | `X: 30.0..65.7 \| Y: 41.0..50.0` | $29.7'\text{ South stucco wall} + 6.0'\text{ covered front porch}$ to front face of `3152` pillar ($X=30.0'$ to $65.7'$). |
| 27 | South Side | Open AC Condenser Pad & Continuous South Grass Corridor | Derived | `4.0` | ft grass | 3.0'$\times$3.0' Open AC Pad (No Cover/Shroud; 4.0'+ Grass Under Gate) | `Pad X: 45.0..48.0 \| Y: 41.0..44.0` | Completely open AC unit at $X=45.0'\text{–}48.0', Y=41.0'\text{–}44.0'$ (no cover or shroud) leaves a $4.0'\text{+}$ wide lawn strip ($Y=43.5'\text{–}47.5'$) continuing under the gate. |
| 28 | Driveway | Main Driveway Width (+Walkway) | Derived | `18.0` | ft | 18.0 ft (+3.5' walk = 21.5') | `X: 73.2..96.7 \| Y: 11.0..29.0 (+3.5' walk)` | Three $6.0'$ wide main panels across ($Y=11.0'$ to $29.0'$) plus a $3.5'$ South porch walkway panel ($Y=29.0'$ to $32.5'$). |
| 29 | Driveway | Driveway Length (Garage to Sidewalk) | Derived | `23.5` | ft | 23.5 ft | `X: 73.2..96.7 \| Y: 11.0..29.0` | Divided into 3 equal concrete slab sections ($\approx 7.83'$ each) from $X=73.2'$ (garage) to $X=96.7'$ (city sidewalk). |
| 30 | Driveway | NE Front & Side Strip (White Decorative Rock Stopping at North Fence) | Derived | `11.0` | ft | 11.0 ft W $\times$ 23.5 ft D + 9.0' $\times$ 3.2' to Gate (White Rock) | `X: 70.0..96.7 \| Y: 0.0..11.0 (White Rock to Fence)` | $11.0'\times 23.5'$ NE strip North of driveway ($X=73.2'\text{–}96.7', Y=0.0'\text{–}11.0'$) plus $9.0'\times 3.2'$ approach up to the North gate ($X=70.0'\text{–}73.2', Y=0.0'\text{–}9.0'$) finished in white decorative rock. |
| 31 | Driveway | SE Front Yard Depth along South Line | Derived | `37.0` | ft | 37.0 ft (Walk to SE Corner; 2.0' South Bed to Green Box) | `X: 59.7..96.7 \| Y: 29.0..50.0` | From City Sidewalk ($X=96.7'$) Westward to SE stucco corner ($X=59.7'$); continuous $2.0'$ South planting bed ($Y=48.0'\text{–}50.0'$) runs to the green utility box ($X=93.0'\text{–}96.4'$). |
| 32 | Driveway | City Sidewalk, White Decorative Rock Park Strips & Curb | Derived | `12.0` | ft | 4.0' Walk + 6.0' White Rock Park Strips + 2.0' Curb | `Walk X: 96.7..100.7 \| White Rock Strip: 100.7..106.7` | $4.0'$ concrete city sidewalk ($X=96.7'\text{–}100.7'$) $+ 6.0'$ park strips finished in white decorative rock ($X=100.7'\text{–}106.7'$) $+ 2.0'$ curb & gutter. |
| 33 | Area & Fence | Backyard Unpaved Area | Calculated | `1237.5` | sq.ft. | 1,237.5 sq. ft. | `X: 0.0..30.0 \| Y: 0.0..50.0 (less Patio)` | Total Backyard ($50.0' \times 30.0' = 1,500\text{ sq.ft.}$) minus Concrete Patio ($21.0' \times 12.5' = 262.5\text{ sq.ft.}$). |
| 34 | Area & Fence | Backyard Concrete Patio, Open 2-Pillar Awning & 2× $52"$ Lighted Fans | Calculated | `262.5` | sq.ft. | 262.5 sq. ft. (Open 2-Pillar Solid-Roof Awning + 2× $52"$ Lighted Fans) | `X: 17.5..30.0 \| Y: 20.0..41.0 (Pillars: X=18.0, Y=20.5 & 40.5; Fans: X=23.75, Y=25.5 & 35.5)` | $21.0'\text{ N–S width} \times 12.5'\text{ E–W depth} = 262.5\text{ sq.ft.}$ (four $65.625\text{ sq.ft.}$ slabs; `Option #1C` solid-roof timber awning + 2× $52"$ lighted ceiling fans + bistro lights + L-sectional + propane fire table). |
| 35 | Area & Fence | North & South Side Yard Areas | Calculated | `658.8` | sq.ft. | 360.0 sq.ft. N. Road Base (inside gate) + 28.8 sq.ft. White Rock / 270.0 sq.ft. (S) | `388.8 N. Side (360 Road Base + 28.8 White Rock) + 270.0 S. Side` | North Side: $9.0'\times 40.0' = 360.0\text{ sq.ft.}$ compacted road base pad inside gate $+ 9.0'\times 3.2' = 28.8\text{ sq.ft.}$ white rock outside gate. South Side: $9.0'\times 30.0' = 270.0\text{ sq.ft.}$ ($247.5\text{ sq.ft.}$ enclosed). |
| 36 | Area & Fence | North Side Double Vehicle Gate & Setback (2027) | Set back behind stone | `9.0` | ft | 9.0' Span (8.0'–8.5' Double Gate @ 100% Ours) @ 3.2' Setback | `X: 70.0 (3.2' W of NE Corner) \| Y: 0.0..9.0` | **2027 Phase 2:** Set back $3.2'$ West of NE garage face ($1.2'$ behind $2.0'$ stone wrap & downspout) onto flat stucco at $X=70.0'$ (100% our gate cost). Leaves $70.0'$ North fence (split 50/50 with North neighbor). |
| 37 | Area & Fence | South Side Pedestrian ("Human") Gate & Setback (2026) | Set back on stucco | `4.0` | ft | 4.0' Walk Gate + 5.0' Wing (@ 100% Ours) @ 2.2' Setback | `X: 57.5 (2.2' W of SE Corner) \| Y: 41.0..50.0` | **2026 Phase 1:** Set back $2.2'$ West of SE stucco corner ($8.2'$ West of `3152` porch stone pillar) onto flat stucco at $X=57.5'$, East of gas meter (100% our gate cost). Leaves $57.5'$ South fence (split 50/50 with South neighbor). |
| 38 | Area & Fence | Total Side Fence & Gate Linear Footage | Calculated | `145.5` | lin.ft. | 57.5' S (2026, 50% Split) + 70.0' N (2027, 50% Split) + 18.0' Gates (100% Ours) | `57.5' S + 9.0' S Gate (2026) \| 70.0' N + 9.0' N Gate (2027)` | $145.5\text{ linear ft}$ total: **2026 Phase 1** = $57.5'$ South fence (50% neighbor split) $+ 9.0'$ S walk gate & wing (100% ours); **2027 Phase 2** = $70.0'$ North fence (50% neighbor split) $+ 9.0'$ N vehicle gate (100% ours). |
| 39 | Backyard | Northern Fence Planters (5 $\times$ 3.0' W $\times$ 6.0' L N–S in Road Base) | 5 Planters (8.5' to Grass) | `90.0` | sq.ft. | 90.0 sq.ft. Growing Area (5 Boxes @ 3'W $\times$ 6'L in Compacted Road Base) | `X: 4.0..27.0 \| Y: 0.0..8.5 (Planters Y=1.0..7.0)` | 5 N–S boxes ($3.0'\text{ W} \times 6.0'\text{ L}$) along North Fence ($X=5.0'\text{–}27.0'$) surrounded by compacted road base ($94\text{ sq.ft.}$ net paths): $1.0'$ N space $+ 6.0'$ box $+ 1.0'$ S space $+ 6"$ paver ($= 8.5'$ to grass). |
| 40 | Backyard | Rear House Wall Compacted Road Base Sidewalk/Path | Patio to N. Road Base Pad | `33.0` | sq.ft. | 3.0 ft W $\times$ 11.0 ft L Compacted Road Base Walk | `Walk X: 27.0..30.0 \| Y: 9.0..20.0` | $3.0'$ wide compacted road base sidewalk/path right against the $11.0'$ rear house wall connecting the Concrete Patio ($Y=20.0'$) to the North Side Compacted Road Base Pad ($Y=9.0'$), bordered at $X=26.5'\text{–}27.0'$ by a $6"$ flush Holland paver strip. |
| 41 | South Side | Gas & Electric Meters Location (South Wall) | Derived from Photos | `8.0` | ft | 6.0 ft – 10.0 ft W of SE Corner | `X: 51.0..54.5 \| Y: 41.0..42.1` | Mounted on South stucco wall at $X=51.0'\text{–}54.5', Y=41.0'$. Setting South pedestrian gate at $X=57.5'$ encloses meters inside the gate. |
| 42 | Area & Fence | SE Front Yard Lawn (Continuous Under Gate), Melinda's Hyacinths & Norwegian Sunset® Maple (`wx=83.0', wy=39.5'`) | Calculated | `555.0` | sq.ft. | 555.0 sq. ft. (Grass Under Gate + Hyacinths + Norwegian Sunset Maple + 45° Pavers) | `X: 57.5..96.7 \| Y: 29.0..50.0 (Maple: X=83.0, Y=39.5)` | Grass continues seamlessly under the South gate ($X=57.5'$) into the SE front lawn; Melinda's jewel-toned fragrant spring Hyacinths fill the $2.0'$ porch-front bed & $2.0'$ South bed; Norwegian Sunset® Maple centered at ($X=83.0', Y=39.5'$) inside a $6.0'$ octagonal paver mulch ring. |
| 43 | Area & Fence | NE Front & Side White Decorative Rock Strip (Up to North Fence) | Calculated | `287.3` | sq.ft. | 258.5 sq. ft. NE Strip + 28.8 sq. ft. Gate Approach (White Decorative Rock) | `X: 70.0..96.7 \| Y: 0.0..11.0 (Stops at X=70.0' Fence)` | Finished in white decorative rock from the City Sidewalk ($X=96.7'$) up to the North side yard fence/gate ($X=70.0'$) and in both $6.0'$ park strips ($X=100.7'\text{–}106.7'$) to match our South neighbors. |
| 44 | Backyard | Western Wall Bed (`5+4` Designer Hybrid w/ `'Standing Ovation'` Blossoms) | `5+4` Designer Hybrid | `200.0` | sq.ft. | 4.0' D $\times$ 50.0' L Bed (`5+4` Designer Hybrid) | `X: 0.0..4.5 \| Y: 0.0..50.0 (S1-S5 @ 5..45, J1-J4 @ 10..40)` | $4.0'$ deep mulch bed $+ 6"$ paver ($4.5'$ to grass): `5+4` Hybrid = $5\times$ `'Standing Ovation'` Serviceberry pillars ($Y=5,15,25,35,45$) + $4\times$ column junipers ($Y=10,20,30,40$) + 10-spot under-story ($X=2.95'$). |
| 45 | Area & Fence | Total Unpaved Yard Area (Full Lot & Enclosed) | Calculated | `2709.8` | sq.ft. | 2,709.8 sq. ft. Total (1,845.0 sq.ft. Inside Gates) | `1,845.0 sq.ft. Enclosed + 864.8 sq.ft. Front` | $1,237.5\text{ sq.ft.}$ Backyard $+ 360.0\text{ sq.ft.}$ N. Side Road Base (inside gate) $+ 247.5\text{ sq.ft.}$ S. Side (inside gate) $+ 864.8\text{ sq.ft.}$ Front Yard (plus $192\text{ sq.ft.}$ white rock park strips). |

---

## 6. Interactive Web & CAD Software Architecture (`index.html`, `cad_architectural_blueprint_3152.html`, `model_3d_3152.html`)

1. **Minimalist Visual Hub ([`index.html`](../index.html))**:
   * Intentionally stripped of heavy prose so it serves strictly as an **ultra-minimalist visual demonstration** with embedded iframes for the 3D Model and 2D CAD Designer, the 13 concept render cards (with 1:1 Before/After site photo toggle), interactive 5-year budget mode switcher (`Hybrid`, `DIY`, `Pro`), and 30-photo site survey grid.
2. **2D CAD Architectural Blueprint ([`cad_architectural_blueprint_3152.html`](../cad_architectural_blueprint_3152.html))**:
   * **Single-File Zero-Dependency SVG Engine + 4-Season Switcher (`Spring`, `Summer`, `Fall`, `Winter`)**: Synchronized with `model_3d_3152.html` and `index.html` via `postMessage`.
   * **Projection & Orientation Engine (`project(wx, wy)` & `unproject(sx, sy)`)**: Supports `'WEST_UP'` *(Default Front View)*, `'NORTH_UP'` *(Standard Compass CAD)*, and `'EAST_UP'` *(Door View)* with exterior padding (`PAD_WEST_FT = 29`, `PAD_EAST_FT = 27`, `PAD_NORTH_FT = 28`, `PAD_SOUTH_FT = 28`) for 3 concentric exterior dimension tracks (`Track 1` at $\approx 6.5'$, `Track 2` at $\approx 13.5'$, `Track 3` at $\approx 20.0'$).
   * **`CADCollisionEngine`**: Performs screen-space AABB collision resolution across every label pill and draws angled dogleg leader lines (`renderDoglegLeader`) whenever a callout is displaced.
   * **Point-to-Point Tape Measure & Phase Layer Toggles**: Magnetic snapping to `KEY_SNAP_POINTS` (within $0.9'$) or $0.25'$ ($3"$) grid increments, plus individual toggles organized under Build Phases 1–5 (`2026–2030`).
3. **1:1 3D WebGL Digital Twin ([`model_3d_3152.html`](../model_3d_3152.html))**:
   * Built in Three.js with high-DPI procedural PBR bump/roughness textures, 4-Season foliage/blossom/snow geometry, Daylight / Sunset / Night `2700K` lighting modes, 5-Hydrozone 3D sprinkler spray arc visualization, 9 camera presets, Orbit & WASD First-Person Walk modes, interactive swinging gates, and 20 layer toggles.
