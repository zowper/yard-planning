# Master Landscape Design Specification & Context Document

## 1. Project Overview & Core Objectives
This document serves as the complete architectural, botanical, and visual specification for a residential front and backyard landscaping redesign. It is formatted as a structured knowledge base for AI workflows, 3D rendering engines, and contractor estimation.

* **Primary Aesthetic Goal:** Eliminate the rigid "bowling alley" perimeter effect of builder-grade 90-degree corners while unifying wood, stone, and metal finishes across the property—using **clean, straight geometric runs with 45-degree chamfered corners (NO curvy / S-curve edging)**.
* **Locked-In Lawn Edging & Corner Specification (Jared & Melinda — Home Depot Pavestone Holland Paver):**
  * **No Curvy Edging:** All turf perimeters use straight geometric runs rather than wavy S-curves ($\approx 195\text{ linear ft}$ total across Lot 3152: $120\text{ lin ft}$ Backyard + $75\text{ lin ft}$ Front Yard).
  * **Exact Home Depot Paver to Buy (`Pavestone Holland Concrete Paver`):** Listed on Home Depot's website by exact metric mold size ($200\text{ mm} \times 100\text{ mm}$) rather than nominal "4×8":
    * **Standard 60 mm (Most Stocked in Utah):** **`7.87 in. L × 3.94 in. W × 2.36 in. H`** ($\approx \$0.68\text{–}\$0.78/\text{brick}$ in-store; $480\text{ pcs/pallet}$). Extra thickness resists shifting or tipping in Utah freeze-thaw soil.
    * **Thin 45 mm (#1 Budget Pick if In Stock Locally):** **`7.75 in. L × 4 in. W × 1.75 in. H`** (or `7.87" × 3.94" × 1.77"`, $\approx \$0.58\text{–}\$0.68/\text{brick}$; $672\text{ pcs/pallet}$). Requires only a $1.75\text{"}$ deep trench.
    * **Built-In Mower Advantages:** Features side spacer bars for automatic joint alignment and a micro-chamfered top edge so mower wheels and blades never catch on a sharp lip. *(Skip `7.63" × 3.63" × 2.25"` structural masonry concrete bricks in the building materials aisle, which lack spacer nubs/chamfers and spall in wet winter turf).*
  * **Exact Color SKUs to Buy:**
    * **Top Modern High-Contrast Pick:** **`Charcoal` / `Charcoal Blend` (Model `#21703` / HD SKU `204701612`)** or **`Antique Grey` (Model `#21778-AGR` / SKU `301595154`)** — blends seamlessly into dark brown/black mulch while creating a razor-sharp architectural frame against bright green turf and matching the black window trim/gutters and dark espresso wood stain.
    * **Top Warm Stone Match:** **`Sierra Blend` (Model `#21777` / SKU `204701614`)** or **`Old Town Blend` (Model `#15699` / `#22099`)** — mixes charcoal/pewter grey with warm taupe/tan variegation that ties directly into the `3152` front porch stacked stone wainscot and the rear tan/grey precast wall while hiding Utah dust and hard-water spots. *(Avoid `Red`, `Red Charcoal`, and `San Diego Terracotta`).*
  * **Layout & Shopping Count for Lot 3152 ($\approx 195\text{ lin ft} + 5\%$ for $45^\circ$ miter cuts):**
    * **Single Lengthwise Ribbon (`3.94"` / `~4"` wide strip):** $1.53\text{ bricks/ft} = \mathbf{315\text{ pavers}}$ (**$\approx \$220\text{–}\$245$ total**).
    * **Crosswise Soldier Course or Staggered Double Row (`7.87"` / `~8"` wide strip):** $3.05\text{ bricks/ft} = \mathbf{625\text{ pavers}}$ (**$\approx \$430\text{–}\$485$ total**).
  * **45-Degree Chamfered Paver Corners:** Every $90^\circ$ turf corner is replaced by a **$45^\circ$ angled paver corner** ($\approx 2.0\text{ ft} \times 2.0\text{ ft}$ diagonal transition cut with $22.5^\circ$ miter joints) so the lawn mower can pivot continuously around corners in a single pass without backing up or scalping.
  * **House-to-Grass & Concrete Transitions (No Basement / No Window Wells):** The home is slab-on-grade with **no basement and no window wells anywhere**. Along the $11.0\text{ ft}$ rear house wall (`wy = 9.0' to 20.0'`), a **$3.0\text{ ft}$ wide poured concrete sidewalk** (`wx = 27.0' to 30.0'`) directly connects the $21.0' \times 12.5'$ concrete patio to the $9.0\text{ ft}$ wide North side cement pad. Where grass meets flat poured concrete (Patio, $3.0'\text{ Rear Sidewalk}$, Porch Walkway, Driveway, City Sidewalk), the concrete slab itself serves as the flush mower edge (no redundant pavers against flat concrete). Along the South stucco house wall (`wy = 41.0'`), a **$2.0\text{ ft}$ straight rock/mulch Foundation Drip Buffer** (`wy = 41.0' to 43.0'`) + $6"$ flush paver separates the stucco wall, meters, and AC screen from the $4.0\text{ ft}\text{+}$ wide South side lawn corridor (`wy = 43.5' to 47.5'`).
* **User Preference (Primary Design Track):** **Track B — "Maximum-Grass / Zero-Footprint Design"** (updated with straight flush Pavestone Holland paver edging and $45^\circ$ chamfered corners). The homeowner strongly prefers preserving $90\%$ to $95\%$ of the existing open turf area for recreation and easy mowing.
* **Secondary Reference Track (Archived):** **Track A — "Lush S-Curve & Gravel Pad Design"** (superseded by straight flush paver edging with $45^\circ$ corners).
* **Minimalist Website Presentation Rule (`index.html`):** The live website (`index.html`) must remain an **ultra-minimalist visual demonstration** of what we want—containing almost no prose or long text blocks—while all detailed descriptions, decision trade-offs, and measurement tables live in the repository's Markdown files.

---

## 2. Baseline Site Inventory (Existing Conditions)

### View 1: Backyard — House Facade, Pergola & Lawn
* **House Exterior:** Two-story contemporary stucco facade in cool light grey with white window trim and black fascia/gutters.
* **Patio & Structure:** Poured grey concrete slab patio attached to the house, covered by a dark espresso-stained timber pergola outfitted with warm overhead bistro string lights.
* **Existing Furnishings:** L-shaped grey-washed wood and grey-cushioned outdoor sectional with a small matching coffee table; small foundation planting strip along the left side of the sliding glass door.
* **Perimeter & Fencing:** 6-foot white vinyl privacy fence along the left (South) and right (North) perimeters, with a white vinyl walk-through gate on the right side near the house.
* **Garden Zone:** Three natural cedar raised garden boxes positioned along the right-hand white vinyl fence.
* **Lawn:** Large, uninterrupted rectangular expanse of green turf meeting the fence posts and patio slab at 90-degree angles.

### View 2: Backyard — Back Wall, Privacy Trees & Patio Corner
* **Back Perimeter Wall:** Tall, tan/grey stone-textured precast concrete privacy wall with pilasters/columns running along the rear boundary.
* **Existing Planting Bed:** Narrow, straight mulch strip running parallel to the back concrete wall containing a uniform "soldier row" of nine columnar arborvitae (*Thuja*) evergreens.
* **Garden Zone:** Three dark-stained raised planter boxes situated in the back-right corner against the white vinyl side fence.
* **Patio Foreground:** Corner of the poured concrete patio slab with four lightweight black metal/mesh patio chairs and a small square metal side table.

### View 3: Front Yard — Curb Appeal, Driveway & Entryway
* **House Exterior:** Two-story modern craftsman facade (Address: `3152` mounted vertically on the left front porch column). Features grey horizontal lap siding, white staggered shake shingles on the upper right gable with black shutters, black asphalt shingle roof, and stacked grey/brown stone wainscoting across the lower porch and garage front.
* **Hardscape:** Two-car garage on the right with a wide poured concrete driveway leading to the public concrete sidewalk.
* **Lawn & Foundation Beds:** Rectangular front turf panel bordered by a concrete curb along the left mulch bed and foundation bed. Low, sparse builder-grade shrubs (under $2\text{ ft}$ tall) line the foundation bed, which wraps all the way to the driveway edge (blocking direct pedestrian access from the driveway to the porch).
* **Utility Hardware:** Prominent green metal utility transformer box sitting directly in the front-left mulch bed next to the public sidewalk.
* **Side Gates & Property Line:** White vinyl double gate on the left sitting nearly flush with the front porch corner; white vinyl fence on the right set back behind the garage; narrow strip of white gravel along the far-left property line adjacent to the neighbor's driveway.

---

## 3. Track B: "Maximum-Grass / Zero-Footprint" Specification (USER PREFERRED)

This track preserves almost $100\%$ of the original turf square footage while solving visual flatness and functional bottlenecks through vertical enhancements and mower-friendly flush installations.

### 3.1 Backyard Upgrades (Views 1 & 2)
1. **Zero-Footprint Fence Accent Panels (Left Fence):**
   * Mount 3 horizontal-slat cedar accent panels (stained dark espresso to match the pergola) directly onto the white vinyl fence posts.
   * Interleave narrow, flat black powder-coated metal trellises between the wood panels to support tight vertical climbing vines (e.g., Clematis) planted at the base without widening the bed into the grass.
2. **Back-Left Corner "Pocket Bed":**
   * Carve out a compact $4 \times 4\text{ ft}$ triangular pocket bed in the far back-left fence corner.
   * Plant a single multi-stem ornamental focal tree (Serviceberry or Flame Amur Maple) to break the horizon line and screen the neighboring two-story house while sacrificing almost zero usable lawn.
3. **Enhanced Narrow Back-Wall Bed (View 2):**
   * **Keep the original narrow, straight bed footprint** along the rear stone wall so lawn depth is completely preserved.
   * Break up the monotonous row of 9 arborvitae by alternating clusters of 2 to 3 evergreens with narrow, upright ornamental grasses (Karl Foerster Feather Reed Grass) and compact purple Russian Sage or Catmint tucked strictly inside the existing narrow strip.
4. **Mower-Friendly Straight Flush Paver Edging (Home Depot Pavestone Holland Paver) + 45° Chamfered Corners:**
   * Install a continuous flat concrete paver mowing strip using **Home Depot Pavestone Holland Pavers (`7.87" L × 3.94" W × 2.36" H` or `7.75" × 4" × 1.75"`)** in **`Charcoal Blend` (`#21703`)** or **`Sierra Blend` (`#21777`)** **completely flush with the soil/turf level** along all straight perimeter beds ($\approx 120\text{ lin ft}$ Backyard + $75\text{ lin ft}$ Front Yard), with **$45^\circ$ chamfered paver corners** ($\approx 2.0\text{ ft} \times 2.0\text{ ft}$ diagonal transitions using $22.5^\circ$ miter cuts) at every turf corner. Lawnmower wheels ride directly on the flat paver strip and pivot cleanly around corners in a single pass.
5. **Soil-Flush Flagstone Steppers to Garden Boxes:**
   * Omit the wide gravel pad in the lawn. Allow green grass to grow right up to the dark espresso-stained raised garden beds.
   * Sink large, flat natural flagstone steppers ($18 \times 24\text{ in}$) **completely flush with the soil level** from the corner of the concrete patio to the garden beds and side gate. Provides dry footing while allowing mower blades to pass safely overhead.
6. **Patio-Contained Living & Vertical Color:**
   * Keep all leisure upgrades strictly on the existing concrete slab.
   * Add a large, weather-resistant charcoal/taupe patterned outdoor area rug under the seating zone.
   * Replace the small coffee/side table with a rectangular dark espresso/black metal propane fire table with glass wind guard and lava rock/fire glass.
   * Upgrade View 2 lightweight black chairs to deep-seated, dark-framed outdoor armchairs with thick weather-resistant grey cushions.
   * Hang lush flowering baskets from black wrought-iron brackets mounted to the $6 \times 6\text{ in}$ pergola posts to bring color to eye level without using ground space.

### 3.2 Front Yard Upgrades (View 3 — Maximum-Grass Adaptation)
1. **Driveway "Step-Out" Ribbon & Flush Bed Steppers:**
   * Instead of cutting a walkway through the middle of the front grass, preserve the single unbroken rectangle of turf.
   * Install an $18\text{ to }24\text{ in}$ wide paver or flagstone step-out ribbon flush against the left edge of the driveway, leading into large soil-flush flagstone steppers tucked tightly along the front border of the existing foundation mulch bed to reach the front porch.
2. **In-Bed Focal Tree Placement:**
   * Rather than placing a tree ring inside the lawn, plant the sculptural ornamental focal tree (Japanese Maple or Eastern Redbud) **inside the existing left mulch bed** just behind the utility transformer box. This bridges the vertical scale of the two-story facade while leaving $100\%$ of the grass open.
3. **Tight U-Shaped Utility Box Screen:**
   * Plant a dense U-shaped screen of upright ornamental grasses ($3\text{ to }4\text{ ft}$ tall) and compact evergreens tightly around the back and sides of the green utility box inside the existing mulch bed (leaving the front service panel accessible from the sidewalk).
4. **Lawn Striping:**
   * Utilize a turf roller striping pattern (alternating light/dark mowing lanes) to turn the open lawn into an intentional visual centerpiece.

---

## 4. Track A: "Lush S-Curve & Hardscape Expansion" Specification (Alternative)

For comparison or hybrid adaptation, Track A prioritizes deep botanical layering and dedicated non-turf zones over maximum lawn area.

### 4.1 Backyard Upgrades (Views 1 & 2)
* **Sweeping S-Curve Perimeter Beds:** Expand the left fence line and back wall beds $3\text{ to }5\text{ ft}$ into the yard in flowing S-curves to eliminate all 90-degree turf corners.
* **Raised Stamped Concrete Curbing:** Frame all beds and gravel zones with continuous 6-inch raised stamped/textured grey concrete curbing.
* **Dedicated Crushed Gravel Garden Pad:** Excavate the turf around the right-side raised garden boxes and install a compacted crushed granite/grey gravel pad bordered by concrete curbing, with large flagstone steppers inlaid inside the gravel path from the patio to the back gate.
* **Multi-Tiered Perennial Borders:** Layer medium shrubs, purple Russian sage, lavender, ornamental grasses, and flowering perennials in front of the back wall arborvitae and along the left vinyl fence.

### 4.2 Front Yard Upgrades (View 3)
* **Curving Mid-Lawn Flagstone Walkway:** Install a $4\text{ ft}$ wide mortared or turf-jointed flagstone walkway curving from the mid-driveway through the lawn to the front porch landing.
* **Lawn Specimen Tree Ring:** Plant a Japanese Maple in a dedicated circular curbed mulch ring positioned in the front-left lawn panel.
* **Recessed Left Fence Gate:** Shift the left double vinyl gate back $3\text{ to }4\text{ ft}$ behind the front porch corner to expose the stone wainscot return.

---

## 5. Material, Finish & Lighting Palette

| Element | Specification / Material | Color / Finish | Location |
| :--- | :--- | :--- | :--- |
| **Carpentry Stain** | Semi-transparent exterior wood stain | Dark Espresso / Deep Walnut | Pergola, raised garden boxes, fence accent panels |
| **Stepping Stones** | Natural cleft sandstone / Arizona buff flagstone | Warm grey, tan, and buff tones ($2\text{ in}$ thick) | Patio-to-garden path & front entry path |
| **Edging (Track B — Locked)** | **Home Depot Pavestone Holland Concrete Paver** (`7.87" L × 3.94" W × 2.36" H` 60mm or `7.75" × 4" × 1.75"` 45mm) + **prominent $45^\circ$ chamfered corners** | **`Charcoal Blend` (`#21703`)** / **`Antique Grey` (`#21778-AGR`)** or **`Sierra Blend` (`#21777`)** / **`Old Town Blend` (`#15699`)** (soil-flush) | All grass-to-bed perimeters ($\approx 195\text{ lin ft}$: `315 pcs` single row or `625 pcs` double/crosswise) with prominent $2.0'\times 2.0'$ $45^\circ$ diagonal mower turns |
| **Edging (Track A)** | Extruded concrete landscape curbing | Stamped stone texture, mid-grey ($6\text{ in}$ raised) | All S-curve beds and gravel borders |
| **Patio Awning & Lighting** | Dark-espresso stained timber awning / pergola + $2700\text{K}$ commercial bistro string lights | Deep Espresso / Walnut timber + warm $2700\text{K}$ Edison bulbs | Spanning the entire $21.0\text{ ft} \times 12.5\text{ ft}$ ($262.5\text{ sq ft}$) rear concrete patio |
| **Patio Seating & Fire Table** | **L-Shaped Outdoor Patio Sectional Furniture** + **Long Rectangular Dual-Purpose Propane Fire Table** | Weather-resistant charcoal/taupe cushions + dark bronze/espresso aluminum rectangular table ($50,000\text{ BTU}$ linear burner + wide dining/tabletop perimeter) | Under the timber awning & bistro lights on the $21.0'\times 12.5'$ concrete patio |
| **Neighbor Boundary Contrast** | **North Neighbor (`wy < 0.0'`): Empty Bare Dirt** \| **South Neighbor (`wy > 50.0'`): White Rocks** | Raw graded dirt on North neighbor side; white decorative rock strip on South neighbor side | Marks the exact $50.0\text{ ft}$ N–S property lines and narrow $9.0\text{ ft}$ side yards across all views |
| **Outdoor Rug** | Polypropylene all-weather flatweave | Charcoal, warm grey, and cream geometric/medallion | Under L-shaped patio sectional & rectangular fire table |
| **Fence Accents** | Western Red Cedar $1 \times 4\text{ in}$ horizontal slats + steel trellises | Espresso wood stain + matte black powder-coated steel | South white vinyl fence & AC condenser privacy screen |
| **Low-Voltage Lighting** | $12\text{V}$ LED landscape system ($2700\text{K}$ warm white) | Matte black / bronze fixtures | 10 West wall Juniper uplights, garden path lights & front tree/column grazing |

---

## 6. Recommended Plant Schedule (Including $4.0\text{ ft}$ Western Wall Bed with 10 Junipers — 2 Per Panel)

All plants selected for structural contrast, low maintenance, reflected-heat resilience, and cold-hardy performance:

1. **Western Wall Bed ($4.0\text{ ft}$ Deep $+ 6\text{"}$ Paver $= 4.5\text{ ft}$ to Grass; $wx = 0.0\text{ ft}\text{–}4.0\text{ ft}, wy = 0.0\text{ ft}\text{–}50.0\text{ ft}$):**
   * **Locked-In Master Layout — `10 Upright Lush Green Juniper Trees Evenly Spaced 2 Per 10.0 ft Panel (@ 5.0 ft On-Center)` (`J1`–`J10` at $wy = 2.5', 7.5', 12.5', 17.5', 22.5', 27.5', 32.5', 37.5', 42.5', 47.5'$, $wx = 1.85'$):**
     * **Why 10 Trees (`2 per Panel`) Solves All 4 Goals (City Works Screening + Afternoon Shade + Zero Claustrophobia + Symmetry):** Placing **10 narrow upright green junipers (`2 inside each 10.0 ft panel` at $2.5'$ and $7.5'$ of each bay = $5.0\text{ ft}$ O.C.)** across the 5 panels of the $50.0\text{ ft}$ West precast wall keeps every $10\text{ ft}$ precast panel $100\%$ symmetrical, leaves all 6 concrete columns completely exposed, keeps **$40\%\text{–}50\%$ of the lower stone wall open** so the $30\text{ ft}$ backyard never feels claustrophobic, and rises **$12\text{ to }19\text{ ft}$ above the $6\text{ ft}$ concrete wall** ($18\text{–}25\text{ ft}$ total height) to block the neighboring **City Works buildings and antennas** while casting deep afternoon shade across the lawn and patio.
     * **Exact Cultivars to Buy for Lush, Rich GREEN Color (Skip the Dusty Blue-Grey Varieties):**
       * **#1 Best Pick — `'Taylor'` Juniper (*Juniperus virginiana 'Taylor'*):** Known as the *"Cold-Hardy Italian Cypress."* Features **rich, vibrant, semi-glossy emerald-forest GREEN foliage** with a soft, feathery, lush fill (Melinda's exact preference), grows fast ($1.5\text{–}2.5\text{ ft/yr}$) to **$18\text{–}25\text{ ft}$ tall** (blocking the City Works roofline and antennas), and naturally holds a tight **$3.0\text{ to }3.5\text{ ft}$ narrow column** without splaying in winter snow.
       * **#2 Best Home Depot In-Store Pick — `'Spartan'` Chinese Juniper (*Juniperus chinensis 'Spartan'*):** Widely stocked at Home Depot in budget `1–2 gal` (`~$20–$28`) and `5 gal` pots. Features **ultra-dense, deep Kelly/emerald-green foliage** from top to bottom and grows fast to **$15\text{–}20\text{ ft}$ tall**. *(Because 'Spartan' wants to widen to $4.5\text{–}5\text{ ft}$ at the base if left untouched, simply give it a quick 15-minute light shearing once a year in late spring to keep each column a tight, formal **$3.0\text{–}3.2\text{ ft}$ wide** inside the $4.0\text{ ft}$ bed).*
       * **Why to Skip `'Skyrocket'`, `'Blue Arrow'`, `'Moonglow'` & `'Wichita Blue'`:** Those cultivars are **silver-blue / dusty grey-blue** rather than lush green, and *'Blue Arrow'* stops at $12\text{–}14\text{ ft}$ (too short to fully block the high City Works antennas).
   * **Companion Inter-Planting for the 10-Juniper (`2 per Panel`) Layout:**
     * *Center of Each of the 5 Panels ($wy = 5.0', 15.0', 25.0', 35.0', 45.0'$ — Framed Between Each Pair of Junipers):* **1× 'Little Spire' Russian Sage** (*Perovskia*, $wx = 1.75'$) or **'Hidcote' English Lavender** paired with **1× Front Coneflower** (*Echinacea*, $wx = 3.05'$) or **'Cat's Pajamas' Catmint** — creating a purple & coral-gold focal centerpiece inside every $10\text{ ft}$ wall bay.
     * *In Front of the 4 Interior Precast Wall Columns ($wy = 10.0', 20.0', 30.0', 40.0'$, $wx = 2.25'$):* **4× 'Karl Foerster' Feather Reed Grass** (*Calamagrostis x acutiflora*, $1.5\text{–}2\text{ ft}$ W $\times 4\text{–}5\text{ ft}$ H) — vertical golden plumes that soften the concrete column joints without hiding the recessed stone panels.
2. **Canopy / Ornamental Focal Trees ($12\text{ to }20\text{ ft}$ mature height):**
   * *Backyard Corner / Accent:* Autumn Brilliance Serviceberry (*Amelanchier x grandiflora*) — multi-stem form, white spring blossoms, orange/red fall foliage.
   * *Front Yard Focal Point:* Emperor I Japanese Maple (*Acer palmatum 'Wolff'*) or Prairiefire Crabapple — deep burgundy/red foliage to contrast the grey siding and stone wainscot.
3. **Southern Fence Berry, Pea, Kiwi & Shade Bed ($2.0\text{ ft}$ Deep $+ 6\text{"}$ Paver $= 2.5\text{ ft}$ to Grass; $wy = 48.0\text{ ft}\text{–}50.0\text{ ft}$):**
   * Trellised Heritage/Caroline Raspberries, Sugar Snap Peas, Hardy Kiwi (*Actinidia arguta* 'Issai'), and Alpine Strawberries groundcover in the sunny Backyard section ($wx = 4.0\text{ ft}\text{–}30.0\text{ ft}$), transitioning to Hostas, Ferns, and Astilbe in the shaded South Side Yard corridor ($wx = 30.0\text{ ft}\text{–}57.5\text{ ft}$).
4. **Utility Box Screening (Front Yard):**
   * Blonde Ambition Blue Grama Grass or Karl Foerster Feather Reed Grass arranged in a 3-sided U-shape inside the $2.0\text{ ft}$ buffer bed around the green transformer box.

---

## 7. Ready-to-Use AI Generation / Editing Prompts

Use these structured prompts inside Antigravity or image generation pipelines to render consistent visual iterations of the property.

### 7.1 Track B Prompts (Maximum-Grass / Flush Design)

* **View 1 Prompt (Backyard — House, Awning, Bistro Lights, L-Sectional, Fire Table & 5 Planters):**
  > *"Edit this backyard photo to show the 21'x12.5' concrete patio covered by a dark-espresso stained timber awning/pergola strung with warm 2700K bistro string lights, sheltering L-shaped outdoor sectional furniture on an outdoor rug and a long rectangular dual-purpose propane fire pit table. Along the left (North) white vinyl fence, show 5 raised cedar garden boxes (3' wide x 6' long) running North-to-South in an 8.0' crushed grey gravel bed, with a 3.0' poured concrete sidewalk right against the rear house wall connecting the patio to the narrow 9.0' North side cement pad (no window well), and leave the North neighbor's lot outside the left fence as empty bare dirt. Along the right (South) white vinyl fence, show a 2.0' dark-mulched berry trellis bed with 4.0'+ wide green grass wrapping all the way down the narrow 9.0' South side corridor and white rocks on the South neighbor's side outside the fence. Border all beds with a straight 6-inch flush grey concrete paver mowing strip featuring prominent 45-degree chamfered paver corners."*

* **View 2 Prompt (Backyard — 10 Junipers Along West Wall, Chamfered Pavers & Patio):**
  > *"Edit this backyard photo to show a straight 4.0' dark-mulched bed along the 50.0' West precast concrete wall planted with 10 upright green columnar Juniper trees ('Taylor' or 'Spartan' Juniper) evenly spaced two per 10-foot wall panel (5.0' on-center), framed with purple Russian sage, coneflower, and Karl Foerster grasses at the columns. Border the bed with a straight 6-inch flush grey concrete paver mowing strip featuring a prominent 45-degree diagonal chamfered paver corner where it meets the single row of 5 North-to-South 3'x6' raised cedar garden boxes along the North fence. On the foreground patio under the timber awning and warm bistro string lights, show L-shaped patio furniture and a long rectangular propane fire table."*

* **View 3 Prompt (Front Yard — SE Lawn, Prominent 45° Chamfered Pavers & Neighbor Boundaries):**
  > *"Edit this front yard photo to frame the SE green front lawn with straight 2.0' dark-mulched planting beds along the driveway, walkway, front of the 3152 porch (with a red Japanese Maple), South property line, and a 3-sided Karl Foerster grass screen around the green utility box. Border the entire lawn perimeter with a continuous straight 6-inch flush grey concrete paver mowing strip featuring prominent, unmistakable 45-degree diagonal chamfered paver corners at every turn. Leave the North neighbor's lot outside the narrow 9.0' North double vehicle gate as empty bare dirt, and show white rocks on the South neighbor's side outside the narrow 9.0' South walk gate."*

### 7.2 Track A Prompts (Lush S-Curve & Gravel Pad Design — Archived Reference)

* **View 1 Prompt (Backyard — S-Curve & Gravel Pad):**
  > *"Edit this backyard photo to add sweeping S-curve garden beds bordered by 6-inch raised grey concrete curbing along the left white vinyl fence, planted with trellised purple clematis, Russian sage, ornamental grasses, and a focal tree in the back-left corner with warm uplighting. On the right side, stain the raised garden beds dark espresso and place them on a dedicated crushed grey gravel pad bordered by S-curved concrete curbing, with large flagstone stepping stones inlaid in the gravel leading from the patio to the back gate. Under the pergola, add a patterned outdoor rug and a rectangular propane fire table."*

* **View 2 Prompt (Backyard — S-Curve Back Wall):**
  > *"Edit this backyard photo to widen the back wall mulch bed into a flowing S-curve bordered by 6-inch concrete curbing, layering purple Russian sage, ornamental grasses, and colorful perennials in front of the existing row of arborvitae trees with warm landscape lighting. Connect the concrete patio to the back-right dark-stained garden beds with a curving crushed gravel pathway inlaid with large flagstone stepping stones. Upgrade the patio furniture to cushioned dark armchairs on an outdoor rug around a rectangular propane fire table."*

* **View 3 Prompt (Front Yard — Mid-Lawn Walkway):**
  > *"Edit this front yard photo to add a curving 4-foot wide natural flagstone walkway leading from the concrete driveway through the grass to the front porch. Plant a Japanese Maple tree in a curbed mulch ring in the middle-left lawn, camouflage the green utility box near the sidewalk with dense ornamental grasses, and fill the curbed foundation beds with purple lavender and layered evergreens."*

---

## 8. Whole-Yard Decision Matrix & Engineering Rationale (6 Key Decisions)

### Decision 1: Straight Flush Paver Mow Strip (Home Depot Pavestone Holland Paver) + Prominent 45° Chamfered Corners & House Wall Transition
* **Locked-In Lawn Perimeter & Paver Selection Rules:**
  * **Zero Curvy / S-Curve Edging:** All lawn borders use clean, straight geometric runs ($\approx 195\text{ linear ft}$ total: $120\text{ lin ft}$ Backyard + $75\text{ lin ft}$ Front Yard).
  * **Selected Home Depot Paver (`Pavestone Holland Concrete Paver`):** Listed on `homedepot.com` by exact metric mold size ($200\text{ mm} \times 100\text{ mm}$) as **`7.87 in. L × 3.94 in. W × 2.36 in. H (60 mm)`** ($\approx \$0.68\text{–}\$0.78/\text{brick}$) or **`7.75 in. L × 4 in. W × 1.75 in. H (45 mm)`** ($\approx \$0.58\text{–}\$0.68/\text{brick}$). Includes built-in side spacer nubs and micro-chamfered top edges so mower wheels roll smoothly without catching.
  * **Selected Colors:** **`Charcoal` / `Charcoal Blend` (`#21703` / SKU `204701612`)** or **`Antique Grey` (`#21778-AGR` / SKU `301595154`)** for high-contrast framing between dark mulch and green turf; or **`Sierra Blend` (`#21777` / SKU `204701614`)** / **`Old Town Blend` (`#15699` / `#22099`)** to tie into the `3152` front stone wainscot and rear precast wall.
  * **Quantity & Layout Options (`~195 lin ft` + $5\%$ waste):** **Single Lengthwise Ribbon (`3.94"` wide)** = **`315 bricks` (~$220–$245)**; or **Crosswise / Staggered Double Row (`7.87"` wide)** = **`625 bricks` (~$430–$485)**.
  * **Prominent 45° Chamfered Paver Corners Everywhere:** Every $90^\circ$ turf corner is replaced by a **clearly visible, prominent $45^\circ$ diagonal chamfered paver corner** ($\approx 2.0\text{ ft} \times 2.0\text{ ft}$ to $2.5\text{ ft} \times 2.5\text{ ft}$ diagonal transition with $22.5^\circ$ miter cuts, with the mulch/gravel bed filling the triangle behind the bevel) so the lawnmower pivots smoothly at $45^\circ$ in one pass without backing up or scalping corners.
  * **Where Grass Meets Flat Concrete (Patio, Rear Concrete Sidewalk, Porch Walkway, Driveway, City Sidewalk):** *No extra pavers needed*—the flat poured concrete slab already acts as a built-in flush mower strip, avoiding a redundant "double-concrete" seam.
* **Recommended Option — $3.0\text{ ft}$ Rear House Concrete Sidewalk (Patio to North Cement Pad) + $2.0\text{ ft}$ South Wall Buffer:**
  * **Seamless Concrete Connection on the $11.0\text{ ft}$ Rear Wall ($X = 27.0\text{ ft}\text{–}30.0\text{ ft}, Y = 9.0\text{ ft}\text{–}20.0\text{ ft}$):** Because the home has **no basement and no window wells anywhere**, a **$3.0\text{ ft}$ wide poured concrete sidewalk** ($33.0\text{ sq ft}$) runs directly against the rear house foundation wall from the North edge of the $21.0'\times 12.5'$ concrete patio ($Y = 20.0'$) straight to the $9.0'\times 43.2'$ North side cement pad ($Y = 9.0'$).
  * **Built-In Flush Mow Edge:** The backyard lawn meets the $3.0\text{ ft}$ concrete sidewalk directly at $X = 27.0\text{ ft}$, giving mower wheels a wide concrete runway without scraping the stucco.
  * **South Wall $2.0\text{ ft}$ Utility/AC Buffer ($Y = 41.0\text{ ft}\text{–}43.0\text{ ft}$):** Separates the South stucco wall, gas/electric meters, and AC condenser from the $4.0'\text{+}$ wide South side lawn corridor.

### Decision 2: Northern Backyard Raised Garden Bed Layout (5 Cedar Boxes @ $3.0\text{ ft}\text{ W} \times 6.0\text{ ft}\text{ L} = 90\text{ sq ft}$)
* **Locked-In Master Plan — 5 North-to-South Boxes Along the North Fence (`N1`–`N5`):**
  * **Box Dimensions & Orientation:** Exactly **5 raised cedar garden boxes**, each **$3.0\text{ ft}$ wide (East–West) by $6.0\text{ ft}$ long (North–South)** ($90.0\text{ sq ft}$ total growing area), oriented **North-to-South** (long $6.0\text{ ft}$ sides extending perpendicular out from the North white vinyl fence in a single row).
  * **Setbacks & $8.5\text{ ft}$ Total Depth to Grass:** $1.0\text{ ft}$ clearance at the North fence ($Y = 0.0'\text{–}1.0'$) + $6.0\text{ ft}$ N–S box length ($Y = 1.0'\text{–}7.0'$) + $1.0\text{ ft}$ South gravel clearance ($Y = 7.0'\text{–}8.0'$) + $6"$ ($0.5'$) flush paver mowing strip ($Y = 8.0'\text{–}8.5'$) = **$8.5\text{ ft}$ total from North fence to grass**.
  * **East–West Spacing ($X = 4.0'\text{–}27.0'$):** Evenly spaced between the $4.0\text{ ft}$ West juniper bed ($X = 4.0'$) and the $3.0\text{ ft}$ Rear House Concrete Sidewalk ($X = 27.0'$): `N1` ($5.0'\text{–}8.0'$), `N2` ($9.75'\text{–}12.75'$), `N3` ($14.5'\text{–}17.5'$), `N4` ($19.25'\text{–}22.25'$), and `N5` ($24.0'\text{–}27.0'$).

### Decision 3: Patio Awning & Bistro Lights + L-Shaped Patio Furniture + Rectangular Propane Fire Table ($21.0\text{ ft} \times 12.5\text{ ft}$ Existing Patio)
* **Locked-In Master Plan (Melinda & Jared's Patio Lounge):**
  * **Timber Awning / Pergola & Warm Bistro String Lights:** Every view of the $21.0\text{ ft} \times 12.5\text{ ft}$ ($262.5\text{ sq ft}$) concrete patio features a **dark-espresso stained timber awning/pergola** outfitted with **warm $2700\text{K}$ commercial overhead bistro string lights**.
  * **L-Shaped Patio Furniture + Dual-Purpose Rectangular Propane Fire Table:** Positioned on an all-weather outdoor area rug under the awning is an **L-shaped outdoor sectional sofa** paired with a **long rectangular propane fire table** ($50,000\text{ BTU}$ linear burner with a wide functional tabletop perimeter and flush burner lid so it acts as both a dining/coffee table and a long propane fire pit). Preserves $100\%$ of the lawn ($0\text{ sq ft}$ grass lost).

### Decision 4: Narrow $9.0\text{ ft}$ Side-Yard White Vinyl Fence Setbacks, Gate Positions & Neighbor Property Line Contrast
* **Option A (Recommended) — Relative Stucco Setback (`N: X = 70.0' | S: X = 57.5'`) + Clear Neighbor Property Line Contrast:**
  * **Both Side Yards Are Narrow ($9.0\text{ ft}$ Wide):** The North side yard ($Y = 0.0'\text{–}9.0'$) and South side yard ($Y = 41.0'\text{–}50.0'$) are each strictly **$9.0\text{ ft}$ wide** from the stucco house wall to the side property line fence.
  * **Neighbor Property Line Contrast (North = Empty Bare Dirt | South = White Rocks):**
    * **North Neighbor (`wy < 0.0'`):** Left completely empty (**simply bare dirt**) outside our $9.0\text{ ft}$ North property line (`wy = 0.0'`) across both the side yard and front street park strip.
    * **South Neighbor (`wy > 50.0'`):** Left as **white rocks** outside our $9.0\text{ ft}$ South property line (`wy = 50.0'`). This makes the exact $50.0\text{ ft}$ lot boundaries unmistakably clear in every view.
  * **North Side (Garage):** $8.0\text{–}8.5\text{ ft}$ Double-Swing Vehicle Gate at $X = 70.0\text{ ft}$ ($3.2\text{ ft}$ behind NE garage face, cleanly behind the $2.0\text{ ft}$ stone masonry wrap and downspout). Encloses $360.0\text{ sq ft}$.
  * **South Side (Porch):** $4.0\text{ ft}$ Single-Swing Pedestrian Gate (+ $5.0\text{ ft}$ fixed vinyl wings across the $9.0\text{ ft}$ span) at $X = 57.5\text{ ft}$ ($2.2\text{ ft}$ behind SE stucco corner / $8.2\text{ ft}$ behind `3152` porch pillar). Encloses the gas and electric meters ($X = 51.0\text{ ft}\text{–}54.5\text{ ft}$) behind the gate while framing the front stone pillar. Encloses $247.5\text{ sq ft}$.

### Decision 5: North Side Full Cement Pad + Rear Concrete Sidewalk & South Side $4.0'\text{+}$ Grass Wrap Corridor
* **Locked-In Master Plan:**
  * **North Side Yard ($9.0\text{ ft}\text{ W} \times 43.2\text{ ft}\text{ L} = 388.8\text{ sq ft}$) + Rear House Sidewalk ($3.0\text{ ft}\text{ W} \times 11.0\text{ ft}\text{ L} = 33.0\text{ sq ft}$):** Full $4\text{-inch}$ poured concrete utility/trailer pad down the narrow $9.0\text{ ft}$ North side yard, connected directly to the backyard concrete patio via the **$3.0\text{ ft}$ wide poured concrete sidewalk** right against the $11.0\text{ ft}$ rear house wall.
  * **South Side Yard ($9.0\text{ ft}\text{ W} \times 29.7\text{ ft}\text{ L}$) with $4.0'\text{+}$ Grass Wrap:** Inside the narrow $9.0\text{ ft}$ South side corridor, the backyard lawn **wraps at least $4.0\text{ ft}$ wide ($Y = 43.5'\text{–}47.5'$) all the way down the South side** between the straight $2.0\text{ ft}$ Southern fence berry/shade bed ($+6"$ flush paver) on the South and the $2.0\text{ ft}$ house wall buffer + horizontal cedar AC screen ($+6"$ flush paver) on the North, so it looks like continuous green grass going down the entire South side.

### Decision 6: Front Yard ($813.5\text{ sq ft}$), Utility Box Camouflage & $6.0\text{ ft}$ Park Strips
* **Option A (Recommended) — Open Front Lawn + 3-Sided Utility Box Grass Screen + Water-Wise $6\text{ ft}$ Park Strips:**
  * **SE Front Lawn ($555.0\text{ sq ft}$):** Continuous lush turf with straight $6\text{-inch}$ flush paver edging and **prominent $45^\circ$ chamfered paver corners**; focal specimen tree (*Japanese Maple* or *Little Gem Magnolia*) planted inside the foundation bed corner with lavender and boxwoods.
  * **Green Utility Transformer Box ($X = 93.0\text{ ft}\text{–}96.4\text{ ft}, Y = 45.5\text{ ft}\text{–}48.5\text{ ft}$):** Tucked in the SE corner near the sidewalk and South property line; screened on 3 sides with upright *Karl Foerster* feather reed grasses inside a $2.0\text{ ft}$ buffer bed with $6\text{-inch}$ $45^\circ$ chamfered pavers (leaving the East service face accessible from the sidewalk).
  * **NE Front Strip ($258.5\text{ sq ft}$):** Concrete approach pad to the $8.5\text{ ft}$ North vehicle gate + narrow river-rock/grass strip staying strictly inside $wy = 0.0\text{ ft}$ (contrasting against the North neighbor's bare dirt at $wy < 0.0\text{ ft}$).
  * **$6.0\text{ ft}$ Park Strips (South $21\text{ ft}$ / $\approx 126\text{ sq ft}$ & North $11\text{ ft}$ / $\approx 66\text{ sq ft}$):** Drip-irrigated decorative cobble/gravel with accent boulders and drought-hardy perennials/ornamental grasses.

---

## 9. Complete 12-Angle CAD-Reconciled Concept Render Inventory (`photos_backyard_ideas/`)

All 12 concept renderings in `photos_backyard_ideas/` are generated directly from the October 2026 site walkaround photos (`photos_current_backyard/`) and reconciled 1:1 against the Master CAD Blueprint (`cad_architectural_blueprint_3152.html`):

| # | Render File Path | Property Zone & Camera Angle | Base Site Photo (`photos_current_backyard/`) | Reconciled CAD Specification Shown |
| :--- | :--- | :--- | :--- | :--- |
| 1 | `photos_backyard_ideas/render_backyard_pergola_north_planters.jpg` | **Backyard (Looking East)** | `PXL_20261022_004857161.MP.jpg` | $21.0'\times 12.5'$ concrete patio with **dark-espresso timber awning/pergola, warm bistro string lights, L-shaped patio sectional & long rectangular propane fire table**; **Left (North):** **5 N–S raised cedar planters ($3'\text{ W}\times 6'\text{ L}$)** in $8.0'$ gravel bed + $6"$ flush pavers with **prominent $45^\circ$ chamfered corners**, **$3.0'$ poured concrete sidewalk right against the rear house wall** (no window well) connecting to the narrow **$9.0'$ North side cement pad**, and **empty bare dirt on the North neighbor's side**; **Right (South):** $2.0'$ dark-mulched berry trellis bed, **$4.0'\text{+}$ wide green grass wrapping down the $9.0'$ South side**, and **white rocks on the South neighbor's side**. |
| 2 | `photos_backyard_ideas/render_backyard_west_juniper_bed_patio.jpg` | **Backyard (Looking NW from Patio)** | `PXL_20261022_004940478.MP.jpg` | $4.0'$ deep Western precast wall bed ($+6"$ flush pavers = $4.5'$ to grass) planted with **10 upright green columnar Juniper trees (`'Taylor'` / `'Spartan'`) evenly spaced 2 per $10.0'$ wall panel (@ $5.0'$ O.C.)**, purple *Russian Sage*, coral *Coneflower*, and *Karl Foerster* grasses with $2700\text{K}$ uplights; **single row of 5 N–S North fence planters ($3'\text{ W}\times 6'\text{ L}$)**; **prominent $45^\circ$ chamfered paver corners**; and **timber awning + bistro lights + L-shaped patio furniture + rectangular propane fire table** on the foreground patio. |
| 3 | `photos_backyard_ideas/render_backyard_nw_five_planters_sidewalk.jpg` | **Backyard (Looking SE from NW Corner)** | `PXL_20261022_004913415.MP.jpg` | View along the North white vinyl fence showing all **5 N–S raised cedar planters ($3.0'\text{ W} \times 6.0'\text{ L}$ running North-to-South)** with straight $6"$ flush pavers and **prominent $45^\circ$ chamfered corner**; **empty bare dirt on the North neighbor's side**; **$3.0'\times 11.0'$ poured concrete sidewalk right against the rear house wall** (no window well); **patio awning + bistro lights + L-shaped sectional + rectangular propane fire table**; and **$4.0'\text{+}$ wide grass wrapping down the South side**. |
| 4 | `photos_backyard_ideas/render_backyard_south_berry_west_juniper_panoramic.jpg` | **Backyard (Looking SW Panoramic)** | `PXL_20261022_004925322.MP.jpg` | Panoramic SW view showing **10 upright green Juniper trees (2 per $10.0'$ panel)** along the $50.0'$ West precast wall on the right; **$2.0'$ deep Southern white vinyl fence berry/pea/kiwi bed**; **prominent $45^\circ$ chamfered paver corners**; **lush green grass wrapping $4.0'\text{+}$ wide down the $9.0'$ South side corridor**; and the **patio awning, bistro lights, L-shaped sectional & rectangular propane fire table** on the left. |
| 5 | `photos_backyard_ideas/render_backyard_full_50ft_span_ten_junipers.jpg` | **Backyard Full $50.0'$ Span (Looking South from NW Corner)** | `PXL_20261022_162216594.MP.jpg` | **NEW ANGLE:** Full $50.0'$ N–S backyard span from the NW corner showing all 5 panels of the West precast wall on the right with **10 upright green Juniper trees evenly spaced 2 per panel**, **prominent $45^\circ$ diagonal chamfered paver corners** in the foreground and background, the **$3.0'$ rear concrete sidewalk** on the left leading to the **patio awning, bistro lights, L-shaped sectional & rectangular propane fire table**, and **$4.0'\text{+}$ South grass wrap**. |
| 6 | `photos_backyard_ideas/render_backyard_sw_corner_patio_awning_south_corridor.jpg` | **Backyard & Patio Lounge (Looking NE from SW Corner)** | `PXL_20261022_162141898.MP.jpg` | **NEW ANGLE:** Looking NE from the SW backyard corner directly into the **$21.0'\times 12.5'$ patio with dark-espresso timber awning, glowing bistro string lights, L-shaped sectional sofa & long rectangular propane fire table**; **$3.0'$ rear concrete sidewalk + 5 N–S garden boxes + empty bare dirt North neighbor** on the left; and **narrow $9.0'$ South side corridor with $4.0'\text{+}$ grass wrap, $45^\circ$ chamfered pavers, AC screen & white rocks South neighbor** on the right. |
| 7 | `photos_backyard_ideas/render_north_side_cement_pad_corridor.jpg` | **North Side Yard (Looking East from NW Corner)** | `PXL_20261022_162209617.MP.jpg` | **Narrow $9.0'\times 43.2'$ poured concrete (cement) North side yard utility/trailer pad** ($388.8\text{ sq ft}$ total / $360.0\text{ sq ft}$ inside gate) with saw-cut control joints, $70.0'$ North white vinyl fence on the left (with **empty bare dirt on the North neighbor's side**), $8.5'$ double-swing vehicle gate (`wx = 70.0'`) & trash bins at the East end, exterior hose bib (`wx = 51.0'`), clean stucco wall with **no window wells**, and the **$3.0'$ rear-wall concrete sidewalk** turning right around the NW corner. |
| 8 | `photos_backyard_ideas/render_north_vehicle_gate_ne_strip.jpg` | **North Vehicle Gate & NE Strip (Looking West)** | `PXL_20261022_162017040.MP.jpg` | **$8.5'$ wide double-swing white vinyl vehicle gate** spanning the **narrow $9.0'$ North side yard** at `wx = 70.0'` (**set back $3.2'$ West of NE garage face / $1.2'$ behind the $2.0'$ decorative stone wrap**), poured concrete driveway apron connection, water-wise river rock/boulder/grass landscaping strictly inside Lot 3152's $9.0'$ boundary (`wy = 0.0'`), and **completely empty bare dirt on the North neighbor's lot (`wy < 0.0'`)** to the right. |
| 9 | `photos_backyard_ideas/render_south_side_flagstone_ac_screen.jpg` | **South Side Yard Corridor (Looking West)** | `PXL_20261022_004709213.MP.jpg` | **Narrow $9.0'$ wide South side corridor** showing **lush green grass wrapping at least $4.0'$ wide all the way down the South side** (`wy = 43.5'–47.5'`), bordered by straight $6"$ flush pavers with **prominent $45^\circ$ chamfered corners**, **$2.0'$ Southern fence shade/berry/kiwi bed** on the left, **horizontal dark-espresso cedar slat AC screen** on the right, and **2 juniper trees per panel** along the West precast wall in the background. |
| 10 | `photos_backyard_ideas/render_south_gate_porch_entry.jpg` | **South Pedestrian Gate & `3152` Porch (Looking West)** | `PXL_20261022_162104480.MP.jpg` | **Narrow $9.0'$ white vinyl fence return** ($4.0'$ single-swing walk gate + $2.5'$ fixed vinyl wings) set back **$2.2'$ West of the SE stucco corner (`wx = 57.5'`, $8.2'$ behind the `3152` stone column)**, with **white rocks on the South neighbor's side (`wy > 50.0'`)** on the far left, green grass wrapping through the gate, and a **prominent $45^\circ$ chamfered paver corner** on the front-of-porch mulch bed. |
| 11 | `photos_backyard_ideas/render_front_se_lawn_chamfered_beds.jpg` | **SE Front Yard & Utility Box Screen (Looking NW)** | `PXL_20261022_004655951.MP.jpg` | $555\text{ sq ft}$ SE front lawn framed on all interior sides by **straight $2.0'$ wide dark-mulched beds** (along driveway, porch walkway, front of `3152` porch with Japanese Maple, South property line, and 3-sided *Karl Foerster* grass screen around the green utility box) bordered by **continuous straight $6"$ flush pavers with prominent $45^\circ$ chamfered corners**, **white rocks on the South neighbor's side (left)**, and **empty bare dirt on the North neighbor's side (right)**. |
| 12 | `photos_backyard_ideas/render_front_full_elevation_park_strips.jpg` | **Full Front Elevation & $6.0'$ Park Strips (Looking West)** | `PXL_20261022_004640801.MP.jpg` | Full Lot 3152 street elevation showing **water-wise $6.0'$ South ($21'$) and North ($11'$) street park strips** (`wx = 100.7'–106.7'`); SE front lawn with $2.0'$ perimeter beds & **prominent $45^\circ$ chamfered paver corners**; **both narrow $9.0'$ recessed white vinyl side gates**; **white rocks on the South neighbor's side (far left)**; and **completely empty bare dirt on the North neighbor's side (far right)**. |

---

## 10. 6-Year Phased Itemized Budget Roadmap (2026–2031)

To pace capital expenditure evenly across 6 years ($\approx \$3,477/\text{yr}$ under the **Recommended Hybrid Plan**), purchasing and installation are broken down into 6 annual phases:

| Year & Phase | Line Item | Reconciled Lot 3152 Specification & Quantity | DIY Est. | Pro Est. | Hybrid Target |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **2026 · Phase 1**<br>*South Fence & Person Gate* | South Property Line White Vinyl Fence (`6' H`) | $57.5\text{ lin ft}$ (`wx = 0.0'–57.5'`: $30.0'$ backyard + $27.5'$ South side yard) | $\$1,495$ | $\$2,415$ | **$\$2,415$** *(Pro)* |
| **2026 · Phase 1** | South Pedestrian ("Person") Gate & Fixed Wings | $9.0\text{ lin ft}$ return at `wx = 57.5'` ($4.0'$ walk gate + $5.0'$ vinyl wings @ $2.2'$ stucco setback) | $\$425$ | $\$725$ | **$\$725$** *(Pro)* |
| **2026 · Phase 1** | Post Footings, Gate Stiffeners & Hardware | $11\text{ posts}$, $\approx 22\text{ bags}$ ($80\text{ lb}$) concrete, aluminum gate stiffeners & stainless latch | $\$230$ | $\$310$ | **$\$310$** *(Pro)* |
| *2026 Subtotal* | **Phase 1 Total (South Fence & Person Gate)** | **$66.5\text{ lin ft}$ Total South Fencing & Gate Assembly** | **$\$2,150$** | **$\$3,450$** | **$\$3,450$** |
| **2027 · Phase 2**<br>*Sprinklers, Pavers, Grass, Mulch & Flat-Dirt Plants* | Multi-Zone Underground Sprinkler System | $6\text{–}8\text{ zones}$ ($\approx 1,345\text{ sq ft}$ turf + smart Wi-Fi controller + PVB backflow + North garden stub-out) | $\$1,350$ | $\$3,400$ | **$\$1,350$** *(DIY)* |
| **2027 · Phase 2** | Flush Lawn Paver Mow Strip ($45^\circ$ Corners) | $\approx 195\text{ lin ft}$ Home Depot Pavestone Holland (`#21703 Charcoal` / `#21777 Sierra`, $315\text{–}625\text{ pcs}$) | $\$450$ | $\$1,350$ | **$\$450$** *(DIY)* |
| **2027 · Phase 2** | Sod / Grass & Topsoil Grading | $1,400\text{ sq ft}$ sod ($679\text{ sq ft}$ BY + $110\text{ sq ft}$ $4'\text{+}$ S. wrap + $555\text{ sq ft}$ Front) + $4\text{ cu yds}$ topsoil | $\$1,050$ | $\$2,300$ | **$\$1,050$** *(DIY)* |
| **2027 · Phase 2** | Dark Shredded Bark Mulch & Weed Barrier | $5.5\text{ cu yds}$ ($3"$ depth across $560\text{ sq ft}$ West, South & Front perimeter beds) + fabric | $\$360$ | $\$750$ | **$\$360$** *(DIY)* |
| **2027 · Phase 2** | West Wall Lush Green Junipers (`10×`) & Perennials | $10\times$ `'Taylor'` / `'Spartan'` Junipers ($2/\text{panel} \text{ @ } 5'\text{ O.C.}$) + $5\times$ Sage/Lavender + $5\times$ Coneflower + $4\times$ Grasses | $\$890$ | $\$1,550$ | **$\$890$** *(DIY)* |
| **2027 · Phase 2** | South Berry/Kiwi Bed, Front Tree & Utility Screen | $1\times$ Front Japanese Maple/Crabapple, $6\times$ utility screen grasses, raspberries, kiwi, snap peas, strawberries & hostas | $\$620$ | $\$1,100$ | **$\$620$** *(DIY)* |
| **2027 · Phase 2** | In-Ground Flat Dirt Garden Soil Prep & Plants | $184\text{ sq ft}$ flat dirt area (`wx = 4.0'–27.0', wy = 0.0'–8.0'`): tilled compost + starts (**$\$0$ raised beds / $\$0$ gravel**) | $\$160$ | $\$280$ | **$\$160$** *(DIY)* |
| *2027 Subtotal* | **Phase 2 Total (Sprinklers, Pavers, Grass, Mulch & Plants)** | **Complete Turf, Paver Edging, Perimeter Beds & Flat-Dirt Garden** | **$\$4,880$** | **$\$10,730$** | **$\$4,880$** |
| **2028 · Phase 3**<br>*North Cement Pad & Connecting Sidewalk* | North Side Yard Full Poured Concrete Pad | $9.0'\text{ W} \times 43.2'\text{ L} = 388.8\text{ sq ft}$ ($4"$ thick $4,000\text{ PSI}$ reinforced slab, $\approx 4.8\text{ cu yds}$) | $\$2,150$ | $\$3,500$ | **$\$3,500$** *(Pro)* |
| **2028 · Phase 3** | Rear House Wall Connecting Concrete Sidewalk | $3.0'\text{ W} \times 11.0'\text{ L} = 33.0\text{ sq ft}$ (`wx = 27.0'–30.0', wy = 9.0'–20.0'`) linking Patio to North Pad | $\$210$ | $\$320$ | **$\$320$** *(Pro)* |
| **2028 · Phase 3** | Expansion Joint Sealant & Cure-and-Seal Coat | Polyurethane joint caulk & breathable acrylic concrete sealer across all $421.8\text{ sq ft}$ | $\$120$ | $\$180$ | **$\$180$** *(Pro)* |
| *2028 Subtotal* | **Phase 3 Total (North Cement Pad & Rear Sidewalk)** | **$421.8\text{ sq ft}$ ($\approx 5.25\text{ cu yds}$) Monolithic Concrete Pour** | **$\$2,480$** | **$\$4,000$** | **$\$4,000$** |
| **2029 · Phase 4**<br>*Patio Furniture & Awning* | Patio Awning / Overhead Shade Cover | Motorized retractable awning ($16'\text{–}20'\text{ W} \times 10'\text{–}12'\text{ D}$ Sunbrella) or shade structure over $21'\times 12.5'$ patio | $\$2,200$ | $\$3,600$ | **$\$2,200$** *(Direct)* |
| **2029 · Phase 4** | Patio Lounge Sectional / Club Seating Set | Deep-seated L-shaped outdoor sectional or $4\times$ club armchairs with Sunbrella cushions & covers | $\$1,650$ | $\$2,400$ | **$\$1,650$** *(Direct)* |
| **2029 · Phase 4** | Rectangular Propane Fire Pit Table & Patio Rug | $50,000\text{ BTU}$ fire table ($28"\times 48"$ or $32"\times 52"$) with flush lid + $8'\times 10'$ all-weather area rug | $\$650$ | $\$950$ | **$\$650$** *(Direct)* |
| *2029 Subtotal* | **Phase 4 Total (Patio Furniture & Awning)** | **Complete $262.5\text{ sq ft}$ Patio Shade & Fire Lounge ($0\text{ sq ft}$ Grass Lost)** | **$\$4,500$** | **$\$6,950$** | **$\$4,500$** |
| **2030 · Phase 5**<br>*Raised Beds, Drip & Crushed Rock* | 5 Raised Western Red Cedar Garden Boxes (`N1`–`N5`) | $5\times$ boxes @ $3.0'\text{ W} \times 6.0'\text{ L}$ ($90\text{ sq ft}$ total, N–S orientation, dark espresso stain & rodent mesh) | $\$1,150$ | $\$2,100$ | **$\$1,150$** *(DIY)* |
| **2030 · Phase 5** | Bulk Organic Raised-Bed Soil & Compost Blend | $5.5\text{ cu yds}$ ($\approx 150\text{ cu ft}$ "Mel's Mix" organic topsoil, mushroom compost & pumice/vermiculite) | $\$380$ | $\$680$ | **$\$380$** *(DIY)* |
| **2030 · Phase 5** | Dedicated Raised-Bed Grid Drip Irrigation System | $25\text{ PSI}$ regulator, filter, $1/2"$ poly risers with per-box shutoff valves & $1/4"$ emitter grids ($6"$ spacing) | $\$260$ | $\$620$ | **$\$260$** *(DIY)* |
| **2030 · Phase 5** | Compacted Crushed Rock / Granite Between Beds | $2.0\text{ tons}$ ($3"$ depth of $3/8"$ crushed granite across the four $1.75'$ walkways & $1.0'$ N/S borders = $94\text{ sq ft}$) | $\$290$ | $\$650$ | **$\$290$** *(DIY)* |
| *2030 Subtotal* | **Phase 5 Total (Raised Garden Beds, Drip & Crushed Rock)** | **Upgrades 2027 Flat Dirt Plot into 5 N–S Cedar Planters ($8.5'$ to Grass)** | **$\$2,080$** | **$\$4,050$** | **$\$2,080$** |
| **2031 · Phase 6**<br>*Lighting & Front Porch Swing* | `300W` Stainless Low-Voltage Transformer & Wire | Multi-tap $12\text{V}/15\text{V}$ smart transformer + $250\text{ ft}$ `12/2` direct-burial wire & waterproof connectors | $\$320$ | $\$650$ | **$\$320$** *(DIY)* |
| **2031 · Phase 6** | Backyard `2700K` LED Uplights & Bistro Lights | $10\times$ brass/aluminum uplights for West Wall Junipers, $4\times$ garden path lights & $48'$ patio bistro lights | $\$540$ | $\$1,150$ | **$\$540$** *(DIY)* |
| **2031 · Phase 6** | Front Yard `2700K` Tree, Column & Path Lighting | $7\times$ fixtures (Japanese Maple uplights, `3152` stone column grazing & front walkway path lights) | $\$340$ | $\$750$ | **$\$340$** *(DIY)* |
| **2031 · Phase 6** | Hanging Front Porch Swing (`6' × 12'` Front Porch) | $4.0'\text{–}5.0'$ solid cedar/teak/polywood hanging porch swing with Sunbrella cushions & ceiling joist hardware | $\$750$ | $\$1,150$ | **$\$750$** *(DIY)* |
| *2031 Subtotal* | **Phase 6 Total (Front/Back Lighting & Porch Swing)** | **Full-Property Twilight Lighting & Covered Front Porch Swing** | **$\$1,950$** | **$\$3,700$** | **$\$1,950$** |
| **2026–2031** | **6-Year Master Plan Grand Total** | **All 6 Phases Complete ($\approx \$3,477/\text{yr}$ Hybrid Avg)** | **$\$18,040$** | **$\$32,880$** | **$\$20,860$** |