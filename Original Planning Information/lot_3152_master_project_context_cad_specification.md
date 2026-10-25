# Lot 3152 — Master Architectural, Yard & CAD Project Context

This document contains the complete, reconciled architectural specifications, coordinate geometry, landscaping calculations, fencing/gate plans, raised garden bed designs, and CAD software architecture for **Lot 3152**. It is structured as a single source of truth to provide full context when continuing the project in Antigravity.

---

## 1. Compass Orientation & Site Context

* **Property Identifier**: Lot 3152 (2-Story Single-Family Residence with attached 2-car garage).
* **Primary Compass Orientation**:
  * **Facing the Front of the House from the Street**: Looking **West**.
  * **Looking Out the Front Door toward the Street**: Looking **East**.
  * **North Side of Property** *(Right side when looking at the front of the house)*: Continuous $43.2\text{ ft}$ stucco house/garage wall, exterior water spigot (hose bib), pink/orange wooden survey stakes along the property line, trash bin storage area, and planned **Double-Swing Vehicle Gate**.
  * **South Side of Property** *(Left side when looking at the front of the house)*: Covered front porch with stone-base column (`3152` address plaque), electric and gas meters, AC condenser unit, neighbor's white gravel border along the property line, and planned **Single-Swing Pedestrian ("Human") Gate**.
  * **West Side of Property** *(Rear)*: Backyard, $21.0\text{ ft} \times 12.5\text{ ft}$ concrete patio, and a $50.0\text{ ft}$ wide precast concrete perimeter wall (5 panel bays at $10.0\text{ ft}$ on-center).
  * **East Side of Property** *(Front)*: Concrete driveway, front yard landscaping beds, city sidewalk, park strip, curb/gutter, and residential street.

---

## 2. Key Architectural Reconciliations (From Field Measurements + Photos)

1. **North–South Width Reconciliation ($50.0\text{ ft}$ Lot Width)**:
   * **Foundation Blueprint Math**:
     $$\text{Lot Width} = 9.0\text{ ft (North Setback)} + 32.0\text{ ft (House Foundation)} + 9.0\text{ ft (South Setback)} = 50.0\text{ ft}$$
   * **Why Front Exterior Measurements Summed to $33.0\text{ ft}$ ($20.5\text{ ft}$ Garage + $12.5\text{ ft}$ Porch)**:
     * On the structural foundation, the garage is **$20.0\text{ ft}$ wide** ($Y = 9.0\text{ ft}$ to $29.0\text{ ft}$) and the front porch/entry is **$12.0\text{ ft}$ wide** ($Y = 29.0\text{ ft}$ to $41.0\text{ ft}$), totaling **$32.0\text{ ft}$**.
     * The decorative stone masonry veneer flares outward by $0.25\text{ ft}$ ($3\text{ in}$) on the North and South garage corners (making the exterior stone-to-stone garage width **$20.5\text{ ft}$**), and the stone base on the `3152` porch column flares $0.25\text{ ft}$ South (making the porch measurement across to the garage wall **$12.5\text{ ft}$**).

2. **East–West Depth Reconciliation ($43.2\text{ ft}$ Max House Depth)**:
   * **Continuous North Wall**: Measures **$43.2\text{ ft}$** from the NW rear corner ($X = 30.0\text{ ft}$) to the NE front garage corner ($X = 73.2\text{ ft}$).
   * **Why Split South/East Measurements Summed to $43.5\text{ ft}$ ($\approx 30.0\text{ ft}$ South Wall + $13.5\text{ ft}$ Garage Projection)**:
     * The main house structural depth along the South wall (from the SW rear corner to the Front Door wall plane) is **$29.7\text{ ft}$** (nominally $\approx 30.0\text{ ft}$).
     * The garage projects **$13.5\text{ ft}$** Eastward from the Front Door wall plane ($29.7\text{ ft} + 13.5\text{ ft} = 43.2\text{ ft}$ structural).
     * The front stone veneer adds **$0.3\text{ ft}$ ($3.5\text{ in}$)** on the front face of the garage ($X = 73.2\text{ ft}$ to $73.5\text{ ft}$), explaining the $43.5\text{ ft}$ tape total.

3. **Total Lot Depth Reconciliation ($96.7\text{ ft}$ to Sidewalk / $108.7\text{ ft}$ to Curb)**:
   * $\text{Backyard Depth } (30.0\text{ ft}) + \text{North House/Garage Wall } (43.2\text{ ft}) + \text{Driveway Length } (23.5\text{ ft}) = 96.7\text{ ft}$ from the inside face of the West precast wall to the West edge of the City Sidewalk.
   * Adding the $4.0\text{ ft}$ City Sidewalk + $6.0\text{ ft}$ Park Strip + $2.0\text{ ft}$ Curb & Gutter equals **$108.7\text{ ft}$** to the street line.

---

## 3. Canonical 2D CAD Coordinate System (`wx`, `wy` in Feet)

All programmatic drawings and calculations use a locked 1:1 coordinate system in **Feet**, where $1.0\text{ ft} = 12.0\text{ SVG vector units}$ ($1\text{ vector unit} = 1\text{ inch}$):

* **Origin $(0.0, 0.0)$**: Northwest corner of the unpaved backyard (inside East face of the West precast concrete wall at the North property line).

### East–West Axis (`wx`, increasing West $\rightarrow$ East)
* $wx = -1.0\text{ ft}$ to $0.0\text{ ft}$: West Rear Precast Concrete Wall ($1.0\text{ ft}$ thick; $1.5\text{ ft} \times 1.5\text{ ft}$ fluted columns at $wy = 0, 10, 20, 30, 40, 50\text{ ft}$).
* $wx = 0.0\text{ ft}$ to $17.5\text{ ft}$: Unpaved backyard dirt West of the patio ($17.5\text{ ft}$ deep).
* $wx = 17.5\text{ ft}$ to $30.0\text{ ft}$: Backyard Concrete Patio ($12.5\text{ ft}$ deep; N–S control joint at $wx = 23.75\text{ ft}$ dividing it into two $6.25\text{ ft}$ halves).
* $wx = 27.0\text{ ft}$ to $30.0\text{ ft}$: **Rear House Wall Poured Concrete Sidewalk** ($3.0\text{ ft}$ wide $\times 11.0\text{ ft}$ long $= 33.0\text{ sq ft}$ at $wy = 9.0\text{ ft}$ to $20.0\text{ ft}$), running directly against the rear house foundation (no basement and no window wells anywhere) to connect the Concrete Patio ($wy = 20.0\text{ ft}$) to the North Side Cement Pad ($wy = 9.0\text{ ft}$). **Where grass meets this rear sidewalk, the patio, the driveway, any sidewalk, or the North cement pad, there are NOT any pavers; where grass meets mulch, gravel, or the home, there ARE flush pavers.**
* $wx = 28.5\text{ ft}$ to $30.0\text{ ft}$: Rear Sliding Glass Door Concrete Step ($1.5\text{ ft}$ deep $\times 6.0\text{ ft}$ wide at $wy = 21.5\text{ ft}$ to $27.5\text{ ft}$).
* $wx = 30.0\text{ ft}$: Rear (West) House Structural Wall (slab-on-grade; no basement / no window wells).
* $wx = 45.0\text{ ft}$ to $48.0\text{ ft}$: AC Condenser Pad ($3.0\text{ ft} \times 3.0\text{ ft}$ on South wall at $wy = 41.0\text{ ft}$ to $44.0\text{ ft}$).
* $wx = 51.0\text{ ft}$: Exterior Hose Bib (Water Spigot) on North wall ($wy = 9.0\text{ ft}$; $21.0\text{ ft}$ East of NW corner).
* $wx = 51.0\text{ ft}$ to $54.5\text{ ft}$: Gas & Electric Meters on South wall ($wy = 41.0\text{ ft}$ to $42.1\text{ ft}$).
* $wx = 57.5\text{ ft}$: **Planned South Pedestrian ("Human") Gate Line** ($2.2\text{ ft}$ West of SE stucco corner onto flat stucco; $8.2\text{ ft}$ West of front porch pillar).
* $wx = 59.7\text{ ft}$: Front Door Wall Plane & SE Stucco House Corner.
* $wx = 59.7\text{ ft}$ to $65.7\text{ ft}$: Covered Front Porch Slab ($6.0\text{ ft}$ deep).
* $wx = 64.2\text{ ft}$ to $65.7\text{ ft}$: `3152` Front Porch Pillar with Stone Veneer Base ($wy = 39.5\text{ ft}$ to $41.25\text{ ft}$).
* $wx = 65.7\text{ ft}$ to $81.0\text{ ft}$: Front Porch Concrete Walkway Extension ($3.5\text{ ft}$ wide at $wy = 29.0\text{ ft}$ to $32.5\text{ ft}$).
* $wx = 70.0\text{ ft}$: **Planned North Double-Swing Vehicle Gate Line** ($3.2\text{ ft}$ West of NE garage face; $1.2\text{ ft}$ behind the $2.0\text{ ft}$ stone wrap and downspout).
* $wx = 71.2\text{ ft}$ to $73.2\text{ ft}$: NE Garage Corner Stone Wrap Return ($2.0\text{ ft}$ along North wall).
* $wx = 73.2\text{ ft}$: NE & SE Garage Structural Front Wall.
* $wx = 73.2\text{ ft}$ to $73.5\text{ ft}$: Front Garage Stone Masonry Veneer ($0.3\text{ ft}$ thick).
* $wx = 73.2\text{ ft}$ to $96.7\text{ ft}$: Concrete Driveway ($23.5\text{ ft}$ long; E–W control joints at $wx = 81.0\text{ ft}$ and $88.85\text{ ft}$).
* $wx = 96.7\text{ ft}$ to $100.7\text{ ft}$: City Sidewalk ($4.0\text{ ft}$ wide).
* $wx = 100.7\text{ ft}$ to $106.7\text{ ft}$: Landscaping Park Strip ($6.0\text{ ft}$ deep) & Flared Driveway Apron.
* $wx = 106.7\text{ ft}$ to $108.7\text{ ft}$: Concrete Curb & Gutter ($2.0\text{ ft}$ wide).
* $wx = 108.7\text{ ft}$ to $115.0\text{ ft}$: Residential Street (East).

### North–South Axis (`wy`, increasing North $\rightarrow$ South)
* $wy < 0.0\text{ ft}$: **North Neighbor Property — Completely Empty Bare Dirt** (zero landscaping outside Lot 3152's $9.0\text{ ft}$ North property line so the boundary is immediately visible).
* $wy = 0.0\text{ ft}$: North Property Line (marked by wooden survey stakes at $wx = 1.5\text{ ft}$ and $26.0\text{ ft}$).
* $wy = 0.0\text{ ft}$ to $9.0\text{ ft}$: **Narrow North Side Yard Setback ($9.0\text{ ft}$ wide)** — full poured concrete utility/trailer pad ($wx = 30.0\text{ ft}$ to $73.2\text{ ft}$).
* $wy = 9.0\text{ ft}$: North House/Garage Structural Wall.
* $wy = 9.0\text{ ft}$ to $20.0\text{ ft}$: Rear House Stucco Wall North of Patio ($11.0\text{ ft}$ wide, bordered by the $3.0\text{ ft}$ wide poured concrete sidewalk at $wx = 27.0\text{ ft}\text{–}30.0\text{ ft}$).
* $wy = 11.0\text{ ft}$ to $27.0\text{ ft}$: 2-Car Overhead Garage Door ($16.0\text{ ft}$ wide).
* $wy = 11.0\text{ ft}$ to $29.0\text{ ft}$: Main Concrete Driveway ($18.0\text{ ft}$ wide; N–S control joints at $wy = 17.0\text{ ft}$ and $23.0\text{ ft}$ creating three $6.0\text{ ft}$ wide lanes).
* $wy = 20.0\text{ ft}$ to $41.0\text{ ft}$: Backyard Concrete Patio ($21.0\text{ ft}$ wide; E–W control joint at $wy = 30.5\text{ ft}$ dividing it into two $10.5\text{ ft}$ halves), covered by the **locked-in `Option #1C` house-attached (ledger-mounted) 2-pillar solid-roof heavy-timber awning** (`2 outer West corner pillars` at $wx = 18.0\text{ ft}, wy = 20.5\text{ ft}$ and $wx = 18.0\text{ ft}, wy = 40.5\text{ ft}$; **`0 pillars against the home`** — attached directly to the house's 2nd-floor rim joist ledger at $wx = 30.0\text{ ft}$; **$100\%$ opaque $1\times 6$ Tongue-and-Groove cedar wood ceiling deck underneath + sleek matte-black standing-seam architectural metal roof & front rain gutter on top**) with **warm $2700\text{K}$ bistro string lights**, **L-shaped outdoor sectional furniture**, and a **long rectangular dual-purpose propane fire table**.
* $wy = 29.0\text{ ft}$: South Garage Structural Wall / North Edge of Front Porch.
* $wy = 29.0\text{ ft}$ to $32.5\text{ ft}$: South Porch Concrete Walkway Panel ($3.5\text{ ft}$ wide alongside driveway).
* $wy = 29.0\text{ ft}$ to $41.0\text{ ft}$: Covered Front Porch Structural Width ($12.0\text{ ft}$ foundation; $12.5\text{ ft}$ exterior with stone base).
* $wy = 41.0\text{ ft}$: South House Structural Wall (Patio South edge is flush with this wall at $wy = 41.0\text{ ft}$).
* $wy = 41.0\text{ ft}$ to $50.0\text{ ft}$: **Narrow South Side Yard Setback ($9.0\text{ ft}$ wide)** — features a $2.0\text{ ft}$ house wall/AC buffer + $6"$ paver ($wy = 41.0\text{ ft}\text{–}43.5\text{ ft}$), a **$4.0\text{ ft}$ wide continuous lawn strip wrapping all the way down the South side** ($wy = 43.5\text{ ft}\text{–}47.5\text{ ft}$), and a $2.0\text{ ft}$ Southern fence berry/shade bed + $6"$ paver ($wy = 47.5\text{ ft}\text{–}50.0\text{ ft}$).
* $wy = 50.0\text{ ft}$: South Property Line.
* $wy > 50.0\text{ ft}$: **South Neighbor Property — White Rocks** (existing white rock strip along $wy = 50.0\text{ ft}$ to $53.5\text{ ft}$, clearly contrasting with Lot 3152's dark mulch beds and fence line).

---

## 4. Fencing & Gate Decisions (Narrow $9.0\text{ ft}$ Side Yards, 50/50 Neighbor Fence Split, 100% Gate Ownership & `2026 South` $\rightarrow$ `2027 North` Schedule)

Both side yards are strictly **$9.0\text{ ft}$ wide**, and both side yard gates are intentionally set back from the front corners of the house so they attach to **flat stucco** and leave the **front stone masonry wraps and downspouts 100% visible from the street**. We **split the shared property-line vinyl fence costs 50/50 with our neighbors** ($57.5\text{ lin ft}$ South fence with our South neighbor; $70.0\text{ lin ft}$ North fence with our North neighbor), while **we pay 100% for our own gates and house-side returns** ($9.0\text{ lin ft}$ South pedestrian gate & fixed wing returns; $9.0\text{ lin ft}$ North double-swing vehicle gate). Installation is phased across **2026 (South fence & gate)** and **2027 (North fence & gate)**. Outside our $50.0\text{ ft}$ lot width, the **North neighbor's side ($wy < 0.0\text{ ft}$) is left completely empty (bare dirt)** and the **South neighbor's side ($wy > 50.0\text{ ft}$) is left as white rocks** so the property lines are unmistakable:

1. **North Side — Double-Swing Vehicle Gate ($wx = 70.0\text{ ft}$ — Installed in 2027 Phase 2)**:
   * **Setback**: Set back **$3.2\text{ ft}$ West** of the NE garage front face ($wx = 73.2\text{ ft}$), which places it **$1.2\text{ ft}$ West** of the $2.0\text{ ft}$ stone masonry wrap ($wx = 71.2\text{ ft}$) and corner downspout.
   * **Gate Spec (100% Our Cost in 2027)**: $9.0\text{ ft}$ total span across the narrow North side yard ($wy = 0.0\text{ ft}$ to $9.0\text{ ft}$), built as an **$8.0\text{ ft}$ to $8.5\text{ ft}$ clear opening Double-Swing Drive Gate** (two $4.0\text{ ft}$ leaves swinging inward/West into the side yard; $\$1,350$ Pro / $\$850$ DIY).
   * **North Fence Length (50% Neighbor Cost Split in 2027)**: **$70.0\text{ linear ft}$** along the North property line ($30.0\text{ ft}$ backyard + $40.0\text{ ft}$ North side yard; our 50% share is $\$1,590$ Pro / $\$990$ DIY of the $\$3,180$ Pro / $\$1,980$ DIY full run + 10 line post footings).

2. **South Side — Single-Swing Pedestrian ("Human") Gate ($wx = 57.5\text{ ft}$ — Installed in 2026 Phase 1)**:
   * **Locked-In Stucco Setback (`wx = 57.5'`)**: Set back **$2.2\text{ ft}$ West** of the SE stucco corner ($wx = 59.7\text{ ft}$) and **$8.2\text{ ft}$ West** of the front face of the `3152` porch column ($wx = 65.7\text{ ft}$). This lands cleanly on flat stucco just East of the gas/electric meters ($wx = 51.0\text{ ft}$ to $54.5\text{ ft}$), enclosing the meters behind the gate while exposing the entire porch column and siding return.
   * **Gate Spec (100% Our Cost in 2026)**: $9.0\text{ ft}$ total return span ($wy = 41.0\text{ ft}$ to $50.0\text{ ft}$), built with a **$4.0\text{ ft}$ Single-Swing Walk Gate** ($wy = 44.5\text{ ft}$ to $48.5\text{ ft}$, aligned with the $4.0\text{ ft}$ grass corridor South of the AC condenser) plus **$5.0\text{ ft}$ of fixed fence wing panels** ($3.5\text{ ft}$ house-side wing + $1.5\text{ ft}$ property-line wing; $\$725$ Pro / $\$425$ DIY + $\$215$ Pro / $\$160$ DIY footings/hardware).
   * **South Fence Length (50% Neighbor Cost Split in 2026)**: **$57.5\text{ linear ft}$** along the South property line ($30.0\text{ ft}$ backyard + $27.5\text{ ft}$ South side yard; our 50% share is $\$1,210$ Pro / $\$750$ DIY of the $\$2,420$ Pro / $\$1,500$ DIY full run).

3. **Total Fencing Linear Footage & Cost-Split Summary**:
   * **$145.5\text{ linear ft}$ Total**: **$127.5\text{ lin ft}$ shared property-line fencing** ($70.0\text{ ft}$ North in 2027 + $57.5\text{ ft}$ South in 2026, **split 50/50 with neighbors**) plus **$18.0\text{ lin ft}$ of private gate assemblies** ($9.0\text{ ft}$ South pedestrian gate & wing assembly in 2026 + $9.0\text{ ft}$ North vehicle gate assembly in 2027, **paid 100% by us**).

---

## 5. Raised Garden Bed Layout (5 Boxes @ $3.0\text{ ft}\text{ W} \times 6.0\text{ ft}\text{ L}$ = $90.0\text{ sq. ft.}$)

### Locked-In Master Plan (`FIVE_NORTH_85` — 5 North-to-South Boxes Along the North Fence)
* **Quantity & Dimensions**: **5 raised cedar garden boxes** (`N1`–`N5`), each **$3.0\text{ ft}$ wide (East–West) by $6.0\text{ ft}$ long (North–South)** ($18.0\text{ sq. ft.}$ each $= 90.0\text{ sq. ft.}$ total growing area).
* **North–South Orientation ($8.5\text{ ft}$ Total to Grass)**:
  * $1.0\text{ ft}$ clearance at the North white vinyl fence ($wy = 0.0\text{ ft}$ to $1.0\text{ ft}$).
  * $6.0\text{ ft}$ long planter box running **North-to-South** ($wy = 1.0\text{ ft}$ to $7.0\text{ ft}$).
  * $1.0\text{ ft}$ gravel clearance on the South side ($wy = 7.0\text{ ft}$ to $8.0\text{ ft}$) $= 8.0\text{ ft}$ gravel bed depth.
  * $6"$ ($0.5\text{ ft}$) flush paver mowing strip ($wy = 8.0\text{ ft}$ to $8.5\text{ ft}$) where the grass meets the garden gravel/mulch bed $= \mathbf{8.5\text{ ft}}$ **total from North fence to grass** (with **NO pavers** where grass meets the $3.0\text{ ft}$ rear concrete sidewalk, patio, or North side cement pad).
* **East–West Spacing ($wx = 4.0\text{ ft}$ to $27.0\text{ ft}$)**:
  * Placed in a single row along the North backyard fence between the $4.0\text{ ft}$ West bed ($wx = 4.0\text{ ft}$) and the $3.0\text{ ft}$ Rear House Concrete Sidewalk ($wx = 27.0\text{ ft}$):
  * `N1`: $wx = 5.0\text{ ft}\text{–}8.0\text{ ft}$, `N2`: $wx = 9.75\text{ ft}\text{–}12.75\text{ ft}$, `N3`: $wx = 14.5\text{ ft}\text{–}17.5\text{ ft}$, `N4`: $wx = 19.25\text{ ft}\text{–}22.25\text{ ft}$, `N5`: $wx = 24.0\text{ ft}\text{–}27.0\text{ ft}$ (with $1.75\text{ ft}$ gravel walking paths between boxes).

---

## 6. Master 45-Item Reconciled Measurement Schedule

| # | Zone / Category | Measurement Name | User Rough Input | Numeric Value | Unit | Reconciled Exact Spec | CAD Coordinates ($X=\text{E/W}, Y=\text{N/S}$) | Planning & Visual Notes |
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
| 13 | Backyard | Back Patio Width (North–South) & Attached 2-Pillar Solid-Roof Awning | 21 ft | `21.0` | ft | 21.0 ft (2 Outer Corner Pillars, 0 House Pillars) | `X: 17.5..30.0 \| Y: 20.0..41.0 (Pillars: X=18.0, Y=20.5 & 40.5)` | Spans $Y=20.0'$ to $Y=41.0'$ (flush with SW house corner). Covered by **locked-in `Option #1C` house-attached solid-roof dark-espresso timber awning** (ledger-mounted at $X=30.0'$ with **strictly 2 pillars on the outer West corners** at $X=18.0', Y=20.5'\text{ \& }40.5'$ and **0 pillars against the home**; solid $1\times 6$ T&G cedar ceiling + matte-black standing-seam metal roof & gutter) + bistro lights, L-sectional & rectangular propane fire table. |
| 14 | Backyard | Back Patio Depth (East–West) | 12.5 ft | `12.5` | ft | 12.5 ft | `X: 17.5..30.0 \| Y: 20.0..41.0` | Extends West from $X=30.0'$ (house ledger) to $X=17.5'$ (outer West slab edge). Divided by center control joint into two $6.25'$ deep halves. |
| 15 | Backyard | Patio Control Joint Quadrants (4x) | Derived | `65.63` | sq.ft. | 10.5 ft W $\times$ 6.25 ft D | `4 Slabs @ 10.5' W x 6.25' D` | Each of the 4 poured concrete patio quadrants measures $10.5'\text{ N–S} \times 6.25'\text{ E–W}$ ($65.625\text{ sq.ft.}$ each). |
| 16 | Backyard | Patio-to-West Wall Dirt Clearance | Derived | `17.5` | ft | 17.5 ft | `X: 0.0..17.5 \| Y: 20.0..41.0` | Unpaved dirt depth West of the concrete patio to the rear precast wall ($30.0' - 12.5' = 17.5'$). |
| 17 | Backyard | Rear House Wall North of Patio | Derived | `11.0` | ft | 11.0 ft | `X: 30.0 \| Y: 9.0..20.0` | Rear house wall section under North window between NW corner ($Y=9.0'$) and Patio ($Y=20.0'$), bordered by $3.0'$ concrete sidewalk. |
| 18 | Backyard | Total Backyard Width North of Patio | Derived | `20.0` | ft | 20.0 ft | `X: 0.0..30.0 \| Y: 0.0..20.0` | Full width from North edge of patio ($Y=20.0'$) to North property line ($Y=0.0'$): $11.0'\text{ wall} + 9.0'\text{ setback}$. |
| 19 | Backyard | Unpaved Width South of Patio | Derived | `9.0` | ft | 9.0 ft | `X: 0.0..30.0 \| Y: 41.0..50.0` | Patio South edge is flush with SW house corner ($Y=41.0'$), leaving $9.0'$ to South lot line ($Y=50.0'$). |
| 20 | Backyard | Rear Sliding Glass Door & Step | Derived | `6.0` | ft | 6.0 ft W $\times$ 1.5 ft D | `X: 28.5..30.0 \| Y: 21.5..27.5` | Concrete step centered under the $6.0'$ wide sliding patio door ($Y=21.5'$ to $27.5'$, $1.5'$ South of N patio edge). |
| 21 | Backyard | West Precast Concrete Wall Bays (5x) & `5+4` Hybrid Trees | 5 Panels ($10'$ O.C.) | `10.0` | ft O.C. | 5 Bays @ 10.0' O.C. (`5+4` Designer Hybrid) | `X: -1.0..0.0 \| Y: 0,10,20,30,40,50` | 5 panels across the $50.0'$ rear wall with $1.5' \times 1.5'$ fluted columns; frames the **`5+4` Designer Hybrid** (5 leafy pillars centered at $Y=5',15',25',35',45'$ + 4 column junipers at $Y=10',20',30',40'$). |
| 22 | North Side | North Side Yard Setback Width | ~9 ft | `9.0` | ft | 9.0 ft (Narrow Corridor) | `X: 0.0..96.7 \| Y: 0.0..9.0` | Narrow $9.0'$ wide corridor from North house/garage wall ($Y=9.0'$) to North lot line ($Y=0.0'$). North neighbor ($Y<0'$) = empty bare dirt. |
| 23 | North Side | North Wall Hose Bib (Spigot) Offset | Derived | `21.0` | ft | 21.0 ft E of NW Corner | `X: 51.0 \| Y: 9.0` | Exterior water spigot at $X=51.0', Y=9.0'$ ($21.0'$ East of NW back corner / $22.2'$ West of NE garage corner). |
| 24 | North Side | NE Garage Corner Stone Wrap Return | Derived | `2.0` | ft | 2.0 ft W $\times$ 0.25 ft N | `X: 71.2..73.2 \| Y: 8.75..9.0` | Front stone veneer wraps $2.0'$ back along North garage wall ($X=71.2'$ to $73.2'$) with downspout at corner. |
| 25 | South Side | South Side Yard Setback Width | ~9 ft | `9.0` | ft | 9.0 ft (Narrow Corridor) | `X: 0.0..96.7 \| Y: 41.0..50.0` | Narrow $9.0'$ wide corridor from South house wall ($Y=41.0'$) to South property line ($Y=50.0'$), with $4.0'\text{+}$ grass wrap. South neighbor ($Y>50'$) = white rocks. |
| 26 | South Side | South Side Length (SW Corner to Porch) | Derived | `35.7` | ft | 35.7 ft (36.0' nom.) | `X: 30.0..65.7 \| Y: 41.0..50.0` | $29.7'\text{ South stucco wall} + 6.0'\text{ covered front porch}$ to front face of `3152` pillar ($X=30.0'$ to $65.7'$). |
| 27 | South Side | AC Condenser Pad & South Grass Corridor | Derived | `4.0` | ft grass | 3.0'$\times$3.0' Pad (4.0'+ Grass Wrap) | `Pad X: 45.0..48.0 \| Y: 41.0..44.0` | AC unit at $X=45.0'\text{–}48.0', Y=41.0'\text{–}44.0'$ with cedar screen leaves a $4.0'\text{+}$ wide lawn strip ($Y=43.5'\text{–}47.5'$) + $2.0'$ South bed. |
| 28 | Driveway | Main Driveway Width (+Walkway) | Derived | `18.0` | ft | 18.0 ft (+3.5' walk = 21.5') | `X: 73.2..96.7 \| Y: 11.0..29.0 (+3.5' walk)` | Three $6.0'$ wide main panels across ($Y=11.0'$ to $29.0'$) plus a $3.5'$ South porch walkway panel ($Y=29.0'$ to $32.5'$). |
| 29 | Driveway | Driveway Length (Garage to Sidewalk) | Derived | `23.5` | ft | 23.5 ft | `X: 73.2..96.7 \| Y: 11.0..29.0` | Divided into 3 equal concrete slab sections ($\approx 7.83'$ each) from $X=73.2'$ (garage) to $X=96.7'$ (city sidewalk). |
| 30 | Driveway | NE Front Strip (North of Driveway) | Derived | `11.0` | ft | 11.0 ft W $\times$ 23.5 ft D | `X: 73.2..96.7 \| Y: 0.0..11.0` | $9.0'\text{ North side yard} + 2.0'\text{ garage stone offset}$ North of driveway edge ($Y=0.0'$ to $11.0'$). Borders North neighbor bare dirt ($Y<0'$). |
| 31 | Driveway | SE Front Yard Depth along South Line | Derived | `37.0` | ft | 37.0 ft (Walk to SE Corner) | `X: 59.7..96.7 \| Y: 29.0..50.0` | From City Sidewalk ($X=96.7'$) Westward to SE stucco corner ($X=59.7'$); $31.0'$ from sidewalk to `3152` porch front. |
| 32 | Driveway | City Sidewalk, Park Strip & Curb | Derived | `12.0` | ft | 4.0' Walk + 6.0' Strip + 2.0' Curb | `Walk X: 96.7..100.7 \| Strip: 100.7..106.7` | $4.0'$ concrete city sidewalk ($X=96.7'\text{–}100.7'$) $+ 6.0'$ park strip ($X=100.7'\text{–}106.7'$) $+ 2.0'$ curb & gutter. |
| 33 | Area & Fence | Backyard Unpaved Area | Calculated | `1237.5` | sq.ft. | 1,237.5 sq. ft. | `X: 0.0..30.0 \| Y: 0.0..50.0 (less Patio)` | Total Backyard ($50.0' \times 30.0' = 1,500\text{ sq.ft.}$) minus Concrete Patio ($21.0' \times 12.5' = 262.5\text{ sq.ft.}$). |
| 34 | Area & Fence | Backyard Concrete Patio & Attached 2-Pillar Solid-Roof Awning | Calculated | `262.5` | sq.ft. | 262.5 sq. ft. (Attached 2-Pillar Solid-Roof Awning) | `X: 17.5..30.0 \| Y: 20.0..41.0 (Pillars: X=18.0, Y=20.5 & 40.5)` | $21.0'\text{ N–S width} \times 12.5'\text{ E–W depth} = 262.5\text{ sq.ft.}$ (four $65.625\text{ sq.ft.}$ slabs; **locked-in `Option #1C` house-attached solid-roof dark-espresso timber awning with 2 outer West corner pillars & 0 house pillars, solid $1\times 6$ T&G cedar ceiling + matte-black standing-seam metal roof & gutter** + bistro lights + L-sectional + rectangular propane fire table). |
| 35 | Area & Fence | North & South Side Yard Areas | Calculated | `658.8` | sq.ft. | 388.8 sq.ft. (N Cement) / 270.0 sq.ft. (S) | `388.8 N. Side + 270.0 S. Side (607.5 gated)` | North Side: $9.0' \times 43.2' = 388.8\text{ sq.ft.}$ full poured concrete. South Side: $9.0' \times 30.0' = 270.0\text{ sq.ft.}$ with $4.0'\text{+}$ grass wrap. |
| 36 | Area & Fence | North Side Double Vehicle Gate & Setback (2027) | Set back behind stone | `9.0` | ft | 9.0' Span (8.0'–8.5' Double Gate @ 100% Ours) @ 3.2' Setback | `X: 70.0 (3.2' W of NE Corner) \| Y: 0.0..9.0` | **2027 Phase 2:** Set back $3.2'$ West of NE garage face ($1.2'$ behind $2.0'$ stone wrap & downspout) onto flat stucco at $X=70.0'$ (**100% our gate cost**). Leaves $70.0'$ North fence (**split 50/50 with North neighbor**). |
| 37 | Area & Fence | South Side Pedestrian ("Human") Gate & Setback (2026) | Set back on stucco | `4.0` | ft | 4.0' Walk Gate + 5.0' Wing (@ 100% Ours) @ 2.2' Setback | `X: 57.5 (2.2' W of SE Corner) \| Y: 41.0..50.0` | **2026 Phase 1:** Set back $2.2'$ West of SE stucco corner ($8.2'$ West of `3152` porch stone pillar) onto flat stucco at $X=57.5'$, East of gas meter (**100% our gate cost**). Leaves $57.5'$ South fence (**split 50/50 with South neighbor**). |
| 38 | Area & Fence | Total Side Fence & Gate Linear Footage | Calculated | `145.5` | lin.ft. | 57.5' S (2026, 50% Split) + 70.0' N (2027, 50% Split) + 18.0' Gates (100% Ours) | `57.5' S + 9.0' S Gate (2026) \| 70.0' N + 9.0' N Gate (2027)` | $145.5\text{ linear ft}$ total: **2026 Phase 1** = $57.5'$ South fence (50% neighbor split) $+ 9.0'$ S walk gate & wing (100% ours); **2027 Phase 2** = $70.0'$ North fence (50% neighbor split) $+ 9.0'$ N vehicle gate (100% ours). |
| 39 | Backyard | Northern Fence Planters (5 $\times$ 3.0' W $\times$ 6.0' L N–S) | 5 Planters (8.5' to Grass) | `90.0` | sq.ft. | 90.0 sq.ft. Growing Area (5 Boxes @ 3'W $\times$ 6'L) | `X: 4.0..27.0 \| Y: 0.0..8.5 (Planters Y=1.0..7.0)` | 5 N–S boxes ($3.0'\text{ W} \times 6.0'\text{ L}$) along North Fence ($X=5.0'\text{–}27.0'$): $1.0'$ N space $+ 6.0'$ box $+ 1.0'$ S space $+ 6"$ paver where grass meets gravel ($= 8.5'$ to grass; no pavers against concrete sidewalk/pad). |
| 40 | Backyard | Rear House Wall Poured Concrete Sidewalk | Patio to N. Cement Pad | `33.0` | sq.ft. | 3.0 ft W $\times$ 11.0 ft L Poured Concrete Walk | `Walk X: 27.0..30.0 \| Y: 9.0..20.0` | $3.0'$ wide poured concrete sidewalk right against the $11.0'$ rear house wall connecting the Concrete Patio ($Y=20.0'$) to the North Side Cement Pad ($Y=9.0'$). Grass meets the sidewalk, patio, and cement pad directly with NO pavers. |
| 41 | South Side | Gas & Electric Meters Location (South Wall) | Derived from Photos | `8.0` | ft | 6.0 ft – 10.0 ft W of SE Corner | `X: 51.0..54.5 \| Y: 41.0..42.1` | Mounted on South stucco wall at $X=51.0'\text{–}54.5', Y=41.0'$. Setting South pedestrian gate at $X=57.5'$ encloses meters inside the gate. |
| 42 | Area & Fence | SE Front Yard Unpaved Bed Area & 45° Chamfered Pavers | Calculated | `555.0` | sq.ft. | 555.0 sq. ft. (Prominent 45° Paver Corners) | `X: 59.7..96.7 \| Y: 29.0..50.0` | $17.5'$ wide along porch walkway widening to $21.0'$ East of walkway $\times 27.0'\text{–}37.0'$ deep; $6"$ flush pavers with prominent $45^\circ$ chamfered corners installed where grass meets mulch, gravel, or the home (NO pavers where grass meets driveway or sidewalks). |
| 43 | Area & Fence | NE Front Yard Unpaved Strip Area | Calculated | `258.5` | sq.ft. | 258.5 sq. ft. | `X: 73.2..96.7 \| Y: 0.0..11.0` | $11.0'$ wide ($9.0'$ North setback $+ 2.0'$ garage stone wing offset) $\times 23.5'$ deep to City Sidewalk. |
| 44 | Backyard | Western Wall Bed (`5+4` Designer Hybrid) | `5+4` Designer Hybrid | `200.0` | sq.ft. | 4.0' D $\times$ 50.0' L Bed (`5+4` Designer Hybrid) | `X: 0.0..4.5 \| Y: 0.0..50.0 (S1-S5 @ 5..45, J1-J4 @ 10..40)` | $4.0'$ deep mulch bed $+ 6"$ paver where grass meets mulch ($4.5'$ to grass): **Locked-In `5+4` Hybrid** = $5\times$ leafy columnar pillars (`'Standing Ovation'` Serviceberry, `'Crimson Spire'` Oak, or `'Parkland Pillar'` Birch at $Y=5,15,25,35,45$) + $4\times$ column junipers (`$20` / `'Taylor'` at $Y=10,20,30,40$) + $10\text{-spot}$ under-story of *Catmint / Russian Sage*, *Coneflower* & *Karl Foerster* Grasses. |
| 45 | Area & Fence | Total Unpaved Yard Area (Full Lot & Enclosed) | Calculated | `2709.8` | sq.ft. | 2,709.8 sq. ft. Total (1,845.0 sq.ft. Inside Gates) | `1,845.0 sq.ft. Enclosed + 864.8 sq.ft. Front` | $1,237.5\text{ sq.ft.}$ Backyard $+ 360.0\text{ sq.ft.}$ N. Side (inside gate) $+ 247.5\text{ sq.ft.}$ S. Side (inside gate) $+ 864.8\text{ sq.ft.}$ Front Yard. |

---

## 7. Interactive CAD Blueprint Architecture (`cad_architectural_blueprint_3152.html`)

When editing or extending `cad_architectural_blueprint_3152.html` in Antigravity, note the following architectural patterns:

1. **Single-File Zero-Dependency Architecture**:
   * All HTML, Tailwind CSS, SVG rendering, AABB collision detection, and TSV/CSV export logic reside in `cad_architectural_blueprint_3152.html`.
2. **Projection & Orientation Engine (`project(wx, wy)` & `unproject(sx, sy)`)**:
   * Supports 3 upright viewing orientations via `STATE.orientation`:
     * `'WEST_UP'` *(Default Front View)*: West at top, East at bottom, South on left, North on right.
     * `'NORTH_UP'` *(Standard Compass CAD)*: North at top, South at bottom, West on left, East on right.
     * `'EAST_UP'` *(Door View)*: East at top, West at bottom, North on left, South on right.
   * Exterior padding constants (`PAD_WEST_FT = 29`, `PAD_EAST_FT = 27`, `PAD_NORTH_FT = 28`, `PAD_SOUTH_FT = 28`) reserve margin space outside the lot lines for concentric exterior dimension tracks (`WORLD_SPAN_WX = 171`, `WORLD_SPAN_WY = 106`).
3. **Concentric Exterior Dimension Tracks + `CADCollisionEngine`**:
   * Exterior dimension lines are organized into 3 concentric tracks outside the lot boundary (Track 1 at $\approx 6.5\text{ ft}$, Track 2 at $\approx 13.5\text{ ft}$, Track 3 at $\approx 20.0\text{ ft}$) with dashed witness lines (`wx1, wy1, wx2, wy2`) connecting to structural corners.
   * `CADCollisionEngine` performs screen-space Axis-Aligned Bounding Box (AABB) collision resolution across every label pill and draws angled dogleg leader lines (`renderDoglegLeader`) whenever a callout is displaced.
4. **Interactive Tools & Locked-In Layers**:
   * **Point-to-Point Tape Measure**: Magnetic snapping to `KEY_SNAP_POINTS` (within $0.9\text{ ft}$) or $0.25\text{ ft}$ ($3\text{ in}$) grid increments, calculating direct Euclidean distance, architectural feet-inches, $\Delta\text{E/W}$, $\Delta\text{N/S}$, and bounding area.
   * **Layer Toggles**: Includes dedicated toggles for `primaryDims`, `secondaryDims`, `zones`, `utilities`, `southFence` & `southGate` (`57.5'` S in 2026 Phase 1), `northFence` & `northGate` (`70.0'` N in 2027 Phase 2), `garden` (`5 N–S boxes @ 3'W × 6'L`), `paverEdging` (flush Home Depot **Pavestone Holland Concrete Paver** edging [`7.87" × 3.94" × 2.36"` 60mm or `7.75" × 4" × 1.75"` 45mm in `Charcoal Blend #21703` or `Sierra Blend #21777`] **installed where grass meets mulch, gravel, or the home; NO pavers where grass meets the driveway, patio, sidewalk, or cement pad** + **prominent $45^\circ$ chamfered corners** + $3.0\text{ ft}$ rear concrete sidewalk + $4.0'\text{+}$ South grass wrap + **`5+4` Designer Hybrid** [5 Leafy Pillars + 4 Column Junipers + 10-spot under-story]), and `grid`.

---

## 8. All 4 Property Zones — Complete Spatial Breakdown

### Zone 1: Backyard & Concrete Patio ($1,500.0\text{ sq ft}$ Total — $wx = 0.0\text{ ft}$ to $30.0\text{ ft}$, $wy = 0.0\text{ ft}$ to $50.0\text{ ft}$)
* **Overall Footprint:** $50.0\text{ ft}$ wide $\times 30.0\text{ ft}$ deep rear yard backed by a 5-panel precast concrete privacy wall ($10.0\text{ ft}$ center-to-center fluted columns). The home is slab-on-grade with **no basement and no window wells anywhere**.
* **Existing Concrete Patio + Locked-In `Option #1C` House-Attached 2-Pillar Solid-Roof Timber Awning, Bistro Lights, L-Shaped Furniture & Propane Fire Table:** $21.0\text{ ft}$ N–S $\times 12.5\text{ ft}$ E–W $= 262.5\text{ sq ft}$ (four $10.5\text{ ft} \times 6.25\text{ ft}$ control-joint quadrants; South edge flush with SW house corner at $wy = 41.0\text{ ft}$). Features the **locked-in `Option #1C` house-attached (ledger-mounted) dark-espresso stained heavy-timber awning** with **strictly TWO $6\times 6$ / $8\times 8$ timber pillars on the outer West corners of the patio (`P1`: $wx = 18.0\text{ ft}, wy = 20.5\text{ ft}$ and `P2`: $wx = 18.0\text{ ft}, wy = 40.5\text{ ft}$) and ZERO pillars against the home** (attached directly to the 2nd-floor rim joist ledger at $wx = 30.0\text{ ft}$ above the sliding glass door and living room window). Outfitted with a clear-span $21.0\text{ ft}$ Glulam / steel-reinforced West header beam, $45^\circ$ corner knee braces, matte-black `Simpson Outdoor Accents` steel post bases/brackets, East–West $2\times 8$ rafters (`18" O.C.`), a **$100\%$ opaque $1\times 6$ Tongue-and-Groove cedar wood ceiling deck underneath**, a **sleek matte-black standing-seam architectural metal roof & front rain gutter on top** (zero translucent plastic), **warm $2700\text{K}$ bistro string lights**, **L-shaped outdoor sectional furniture**, and a **long rectangular dual-purpose propane fire table** (tabletop + linear propane fire pit).
* **$3.0\text{ ft}$ Rear House Concrete Sidewalk ($33.0\text{ sq ft}$):** Runs directly against the $11.0\text{ ft}$ rear house wall ($wx = 27.0\text{ ft}\text{–}30.0\text{ ft}$, $wy = 9.0\text{ ft}\text{–}20.0\text{ ft}$) connecting the North edge of the Concrete Patio ($wy = 20.0\text{ ft}$) directly to the $9.0\text{ ft}$ North Side Cement Pad ($wy = 9.0\text{ ft}$). Where grass meets the patio, rear sidewalk, or cement pad, **there are NOT any pavers**.
* **$4.0\text{ ft}$ Western Back Wall Bed ($wx = 0.0\text{ ft}\text{–}4.0\text{ ft}, wy = 0.0\text{ ft}\text{–}50.0\text{ ft}$; $+6"$ Paver $= 4.5\text{ ft}$ to Grass):**
  * **Locked-In Layout (`HYBRID_5_PLUS_4` — The `5 + 4` Alternating Designer Hybrid, $\approx \$280\text{–}\$380$ Tree Cost):**
    * **5× Leafy Columnar Pillars (`S1`–`S5` centered in the 5 panels at $wy = 5.0', 15.0', 25.0', 35.0', 45.0'$, $wx = 2.0'$):** **#1 Pick:** **`'Standing Ovation'` Serviceberry** (*Amelanchier alnifolia 'Obelisk'*, $15'\text{ H} \times 4.0'\text{ W}$, Utah-native upright shrub/tree at $\approx \$40\text{–}\$65$ in `#2`/`#5` pots, white spring blooms, lush round emerald summer leaves, sweet June berries, fiery red-orange fall color); **#2 Pick:** **`'Crimson Spire'` Columnar Oak** (*Quercus robur $\times$ alba 'Crimschmidt'*, $20'\text{–}25'\text{ H} \times 5'\text{–}6'\text{ W}$, $\approx \$65\text{–}\$95$, holds marcescent copper winter leaves to screen the City Works antennas); **#3 Pick:** **`'Parkland Pillar'` Birch** (*Betula platyphylla 'Jefpark'*, $20'\text{–}25'\text{ H} \times 5'\text{–}6'\text{ W}$, fast $2.5'\text{/yr}$ shimmering emerald-green foliage). *(Avoid `'Lucas'` European Hornbeam, whose $12'\text{–}15'$ wide upper canopy projects $6'\text{–}8'$ over the $13.0'$ grass strip and creates a claustrophobic canyon effect).*
    * **4× Upright Evergreen Junipers (`J1`–`J4` aligned in front of the 4 interior fluted concrete columns at $wy = 10.0', 20.0', 30.0', 40.0'$, $wx = 1.75'$):** Uses **4× `$20` Home Depot Upright Green Junipers** ($\approx \$80$ total) or **4× `'Taylor'` Eastern Red Cedar Junipers** (*Juniperus virginiana 'Taylor'*, $18'\text{–}25'\text{ H} \times 3.0'\text{–}3.5'\text{ W}$) to hide the vertical concrete column seams with 365-day evergreen structure.
    * **Under-Story Planting Beneath & Between the Trees (10 Interval Spots at $wx = 2.95'$, $wy = 2.3', 7.6', 12.4', 17.6', 22.4', 27.6', 32.4', 37.6', 42.4', 47.4'$):** Alternating ribbon of **5× Purple Pollinator Perennials** (**`'Walker's Low'` or `'Cat's Pajamas'` Catmint**, **`'Little Spire'` Russian Sage**, or **`'Hidcote'` English Lavender** + **5× `'PowWow Wild Berry'` / `'Cheyenne Spirit'` Coneflower**) and **5× `'Karl Foerster'` Feather Reed Grasses** ($3'\text{–}5'\text{ H}$ vertical golden plumes, sterile non-spreading seeds, heavy-clay tolerant).
    * **Soil, Offset & Drip Instructions:** Plant tree trunks at $wx = 1.75'\text{–}2.0'$ ($21"\text{–}24"$ off the precast wall), elevate root flares $1"\text{–}2"$ above grade in a $2\times$ wide hole backfilled with $80\%$ native clay + $20\%$ compost/bark fines, irrigate via a dedicated $1/2"$ poly drip line with $2\text{ GPH}$ emitters, and top with $3"$ dark shredded bark mulch.
* **Additional Backyard Features:** **5 raised $3.0\text{ ft}\text{ W} \times 6.0\text{ ft}\text{ L}$ N–S cedar garden boxes** along the North fence ($8.5\text{ ft}$ total to grass), **$2.0\text{ ft}$ Southern Fence Bed** (raspberries, snap peas, alpine strawberries, hardy kiwi & shade plants), **$4.0'\text{+}$ wide South side lawn wrap** continuing all the way down the South side corridor, and straight flush **Home Depot Pavestone Holland Paver** mow strip with **prominent $45^\circ$ chamfered corners** installed everywhere grass meets mulch, gravel, or the home (and no pavers where grass meets patio, sidewalk, or cement pad).

### Zone 2: Narrow $9.0\text{ ft}$ North & South Side Yards ($658.8\text{ sq ft}$ Raw / $607.5\text{ sq ft}$ Enclosed Inside Gates) + Neighbor Boundary Contrast
* **North Side Yard (Garage Side, $wy = 0.0\text{ ft}\text{–}9.0\text{ ft}$ — Fenced & Gated in 2027 Phase 2):** Narrow $9.0\text{ ft}$ W $\times 43.2\text{ ft}$ D corridor ($388.8\text{ sq ft}$ raw; **$360.0\text{ sq ft}$ enclosed** behind the $8.5\text{ ft}$ Double-Swing Vehicle Gate at $wx = 70.0\text{ ft}$ [100% our gate cost in 2027], set back $3.2\text{ ft}$ from NE corner behind the $2.0\text{ ft}$ stone wrap; $70.0\text{ lin ft}$ North property-line fence split 50/50 with our North neighbor in 2027). Completely finished as a **poured concrete (cement) pad** connected to the backyard patio via the $3.0\text{ ft}$ rear-wall concrete sidewalk (with **no pavers** where grass meets the cement pad or rear sidewalk). Includes exterior water spigot ($wx = 51.0\text{ ft}$). **North Neighbor ($wy < 0.0\text{ ft}$): Left completely empty (simply bare dirt).**
* **South Side Yard (Porch Side, $wy = 41.0\text{ ft}\text{–}50.0\text{ ft}$ — Fenced & Gated in 2026 Phase 1):** Narrow $9.0\text{ ft}$ W $\times 29.7\text{ ft}$ D corridor ($270.0\text{ sq ft}$ raw; **$247.5\text{ sq ft}$ enclosed** behind the $4.0\text{ ft}$ Single-Swing Pedestrian Gate + $5.0\text{ ft}$ fixed wing at $wx = 57.5\text{ ft}$ [100% our gate cost in 2026], set back $2.2\text{ ft}$ from SE stucco corner; $57.5\text{ lin ft}$ South property-line fence split 50/50 with our South neighbor in 2026). Features the **$2.0\text{ ft}$ Southern fence mulch bed** ($+6"$ paver), a **$4.0\text{ ft}\text{+}$ wide continuous strip of green grass wrapping all the way down the South side**, and a **$2.0\text{ ft}$ house wall gravel/mulch buffer + horizontal cedar AC screen** ($+6"$ paver). **South Neighbor ($wy > 50.0\text{ ft}$): Left as white rocks.**
* **South Utilities & Clearances:** Gas and electric meters at $wx = 51.0\text{ ft}\text{–}54.5\text{ ft}$ (enclosed inside gate) and $3\text{ ft} \times 3\text{ ft}$ AC condenser pad at $wx = 45.0\text{ ft}\text{–}48.0\text{ ft}$.

### Zone 3: Front Yard, Driveway & Covered Porch ($813.5\text{ sq ft}$ Unpaved — $wx = 59.7\text{ ft}$ to $96.7\text{ ft}$)
* **SE Front Yard Lawn & Bed Area (South of Driveway):** $555.0\text{ sq ft}$ ($17.5\text{ ft}$ wide along porch walkway widening to $21.0\text{ ft}$ near sidewalk $\times 27.0\text{ ft}\text{–}37.0\text{ ft}$ deep). **Where the grass meets mulch, gravel, or the home** (along the $2.0\text{ ft}$ front-of-porch bed, $2.0\text{ ft}$ South property line bed, and 3-sided utility box screen bed), it is bordered by flush **Home Depot Pavestone Holland Paver** edging with **prominent $45^\circ$ chamfered corners**; **where the grass meets the driveway, porch sidewalk/walkway, or city sidewalk, there are NOT any pavers**.
* **Green Utility Transformer Box:** $3.4\text{ ft} \times 3.0\text{ ft}$ PacifiCorp box tucked in the SE corner along the sidewalk ($wx = 93.0\text{ ft}\text{–}96.4\text{ ft}, wy = 45.5\text{ ft}\text{–}48.5\text{ ft}$) — screened on 3 sides with a $2.0\text{ ft}$ planting bed and $45^\circ$ chamfered Pavestone Holland paver edging while keeping front sidewalk access clear.
* **NE Front Strip (North of Driveway):** $11.0\text{ ft}$ W $\times 23.5\text{ ft}$ D $= 258.5\text{ sq ft}$ leading to the North double vehicle gate, staying strictly within $wy = 0.0\text{ ft}$ against the North neighbor's bare dirt ($wy < 0.0\text{ ft}$).
* **Concrete Driveway & Covered Porch:** $18.0\text{ ft}$ driveway + $3.5\text{ ft}$ walkway panel ($21.5\text{ ft} \times 23.5\text{ ft} = 505.3\text{ sq ft}$) + $6.0\text{ ft}$ D $\times 11.5\text{ ft}$ W covered porch with `3152` stone pillar.

### Zone 4: $6.0\text{ ft}$ Street Park Strips, Sidewalk & Curb ($12.0\text{ ft}$ Street Zone — $wx = 96.7\text{ ft}$ to $108.7\text{ ft}$)
* **City Concrete Sidewalk:** $4.0\text{ ft}$ wide ($wx = 96.7\text{ ft}$ to $100.7\text{ ft}$) running the full $50.0\text{ ft}$ N–S width.
* **South Park Strip (Left of Driveway Flare):** $6.0\text{ ft}$ deep $\times \approx 21.0\text{ ft}$ long ($\approx 126\text{ sq ft}$) along the SE front lawn frontage ($wx = 100.7\text{ ft}\text{–}106.7\text{ ft}, wy = 29.0\text{ ft}\text{–}50.0\text{ ft}$).
* **North Park Strip (Right of Driveway Flare):** $6.0\text{ ft}$ deep $\times \approx 11.0\text{ ft}$ long ($\approx 66\text{ sq ft}$) North of the driveway apron ($wx = 100.7\text{ ft}\text{–}106.7\text{ ft}, wy = 0.0\text{ ft}\text{–}11.0\text{ ft}$), ending cleanly at $wy = 0.0\text{ ft}$ next to the North neighbor's bare dirt.
* **Street Curb & Gutter:** $2.0\text{ ft}$ wide ($wx = 106.7\text{ ft}$ to $108.7\text{ ft}$) with sloped driveway approach flares. Planned for water-wise rock/boulder & drip-irrigated ornamental grass/perennial park strip design.

---

## 9. Complete 30-Photo Site Walkaround Inventory (`photos_current_backyard/`)

All 30 original Pixel Motion Photos (`.MP.jpg`) and web thumbnails (`photos_current_backyard/thumbs/`) from the October 2026 site survey:

| # | Filename | Zone | Lighting | Full Spatial & Engineering Description |
| :--- | :--- | :--- | :--- | :--- |
| 1 | `PXL_20261022_162032048.MP.jpg` | Front Yard & Park Strip | Daylight | Full Front Elevation, $21.5\text{ ft}$ Driveway, Sidewalk & $6\text{ ft}$ Park Strip (Looking West) |
| 2 | `PXL_20261022_162046640.MP.jpg` | Front Yard & Park Strip | Daylight | $6.0\text{ ft}$ South Park Strip, Sidewalk & SE Front Yard (Looking North-West from Street Curb) |
| 3 | `PXL_20261022_162056602.MP.jpg` | Front Yard & Utility Box | Daylight | SE Front Yard Bed/Lawn Area ($555\text{ sq ft}$), Green Utility Transformer Box & Covered Porch |
| 4 | `PXL_20261022_162020319.MP.jpg` | Front Garage & Driveway | Daylight | $20.5\text{ ft}$ Garage Frontage, Stone Masonry Veneer Corners & Driveway Apron |
| 5 | `PXL_20261022_162017040.MP.jpg` | NE Front Strip & Park Strip | Daylight | NE Front Strip ($11.0\text{ ft} \times 23.5\text{ ft} = 258.5\text{ sq ft}$), Pink Survey Stakes & North Park Strip |
| 6 | `PXL_20261022_162250066.MP.jpg` | NE Corner & Park Strip | Daylight | Looking South-East Across Driveway, Sidewalk & $6.0\text{ ft}$ Park Strip from NE Garage Corner |
| 7 | `PXL_20261022_004632253.MP.jpg` | Front Yard & Park Strip | Dusk | Dusk Front Elevation — 2-Car Garage, Driveway & $6.0\text{ ft}$ Park Strip |
| 8 | `PXL_20261022_004640801.MP.jpg` | Front Yard & Park Strip | Dusk | Dusk Wide Street View — Curb, $6.0\text{ ft}$ Park Strips, $4.0\text{ ft}$ City Sidewalk & Front Yard |
| 9 | `PXL_20261022_004655951.MP.jpg` | SE Front Yard & Utility Box | Dusk | Dusk View of SE Front Yard ($555\text{ sq ft}$), Green Transformer Box & South Neighbor Gravel Border |
| 10 | `PXL_20261022_162209617.MP.jpg` | North Side Yard ($9'\times 43.2'$) | Daylight | Narrow $9.0\text{ ft}$ North Side Yard Corridor Looking East from NW Backyard (Shows $9.0\text{ ft}$ Width & Pink Survey Stakes) |
| 11 | `PXL_20261022_162233919.MP.jpg` | North Side Yard ($9'\times 43.2'$) | Daylight | North Continuous $43.2\text{ ft}$ Stucco Wall & Exterior Water Spigot ($X = 51.0\text{ ft}$) Looking East |
| 12 | `PXL_20261022_162243180.MP.jpg` | North Vehicle Gate Zone | Daylight | North Double-Swing Vehicle Gate Location ($X = 70.0\text{ ft}$, $3.2\text{ ft}$ Behind NE Garage Corner & $2.0\text{ ft}$ Stone Return) |
| 13 | `PXL_20261022_162132591.MP.jpg` | NW Corner & North Side Entry | Daylight | Looking North Along Rear Patio Edge Toward NW House Corner & North Side Yard Turnaround |
| 14 | `PXL_20261022_162230541.MP.jpg` | NW Garden Bed & Gate Zone | Daylight | NW Backyard & North Property Line Stakes (Planned 5-Box N–S Raised Cedar Garden Bed Zone) |
| 15 | `PXL_20261022_162104480.MP.jpg` | South Gate Setback Zone | Daylight | South Entry & `3152` Stone Pillar — Shows SE Stucco Corner & Gas/Electric Meters Behind Planned Gate |
| 16 | `PXL_20261022_162115166.MP.jpg` | South Side Yard ($9'\times 29.7'$) | Daylight | Narrow $9.0\text{ ft}$ South Side Corridor — Looking West Past Meters & $3'\times 3'$ AC Pad |
| 17 | `PXL_20261022_004709213.MP.jpg` | South Side Utilities | Dusk | Close-Up of South Stucco Wall Gas/Electric Meters ($X = 51'\text{–}54.5'$) & AC Condenser Pad ($X = 45'\text{–}48'$) |
| 18 | `PXL_20261022_162150878.MP.jpg` | Backyard & $21'\times 12.5'$ Patio | Daylight | Rear House Elevation Straight-On ($32.0\text{ ft}$ Foundation Width) & $21.0\text{ ft} \times 12.5\text{ ft}$ Concrete Patio |
| 19 | `PXL_20261022_162141898.MP.jpg` | Backyard & Patio | Daylight | Rear House Facade & Patio Looking North-East from SW Backyard Corner |
| 20 | `PXL_20261022_162158316.MP.jpg` | Rear Wall North of Patio | Daylight | $11.0\text{ ft}$ Bare Rear Wall North of Patio (Planned $3.0'\times 11.0'$ Poured Concrete Sidewalk Zone; No Basement/Window Well) |
| 21 | `PXL_20261022_162206648.MP.jpg` | NW Backyard ($20'$ Unpaved) | Daylight | $20.0\text{ ft}$ Unpaved Width North of Patio Looking South-East |
| 22 | `PXL_20261022_162120308.MP.jpg` | Backyard ($17.5'$ Dirt to Wall) | Daylight | Looking North-West Across Backyard & 5-Panel Precast Concrete Privacy Wall |
| 23 | `PXL_20261022_162126370.MP.jpg` | Concrete Patio ($262.5\text{ sq ft}$) | Daylight | Four $10.5\text{ ft} \times 6.25\text{ ft}$ Concrete Patio Quadrants Looking North |
| 24 | `PXL_20261022_162216594.MP.jpg` | Full $50.0'$ Backyard Width | Daylight | Full $50.0\text{ ft}$ N–S Backyard Span Looking South Along $17.5\text{ ft}$ Dirt Strip Between Patio & Wall |
| 25 | `PXL_20261022_162226769.MP.jpg` | West Precast Wall ($50.0'$) | Daylight | 5-Bay Precast Concrete West Wall ($10.0\text{ ft}$ Center-to-Center Columns) Looking South |
| 26 | `PXL_20261022_004719182.MP.jpg` | Backyard & Patio (Dusk) | Dusk | Dusk Backyard & Patio View with Melinda — Looking North-West Toward Precast Wall |
| 27 | `PXL_20261022_004857161.MP.jpg` | Rear House & Patio (Dusk) | Dusk | Dusk View Looking East from SW Corner Across Patio & Rear Sliding Glass Door |
| 28 | `PXL_20261022_004913415.MP.jpg` | Rear House & NW Corner (Dusk) | Dusk | Dusk View Looking South-East from NW Corner Showing $11.0'$ Rear Wall & Patio |
| 29 | `PXL_20261022_004925322.MP.jpg` | West Precast Wall (Dusk) | Dusk | Dusk View of $50.0\text{ ft}$ West Precast Privacy Wall Looking South-West |
| 30 | `PXL_20261022_004940478.MP.jpg` | Patio Quadrants (Dusk) | Dusk | Dusk View of $21.0\text{ ft} \times 12.5\text{ ft}$ Concrete Patio & West Precast Wall |

---

## 10. Minimalist Website Architecture (`index.html`)

* **Design Mandate:** The public website (`index.html`) is intentionally stripped of heavy text, paragraphs, and data tables so that it serves strictly as an **ultra-minimalist visual demonstration** of what we want.
* **Separation of Concerns:**
  * **Website (`index.html`):** Visual-only showcase featuring concise target spec pills, the interactive 2D CAD layout, the 12 CAD-reconciled target AI concept renders (with 1:1 Before/After site photo toggle), and the filterable 30-photo current-yard grid with minimal word count.
  * **Markdown Documentation (`README.md` & `Original Planning Information/*.md`):** Houses all comprehensive architectural reconciliations, the 45-row measurement schedule, the 6-decision engineering rationale, plant schedules, and photo descriptions.