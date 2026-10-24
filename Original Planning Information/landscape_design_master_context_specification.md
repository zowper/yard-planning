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
  * **House-to-Grass & Concrete Transitions:** Where grass meets flat poured concrete (Patio, Porch Walkway, Driveway, City Sidewalk), the concrete slab itself serves as the flush mower edge (no redundant pavers against flat concrete). Where lawn approaches vertical stucco house walls (such as the $11.0\text{ ft}$ rear wall with the $4.0\text{ ft} \times 1.3\text{ ft}$ basement window well), a **$2.0\text{ ft}$ straight rock/mulch Foundation Drip Buffer** separates the house wall and window well from the flush paver edging.
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
| **Edging (Track B — Locked)** | **Home Depot Pavestone Holland Concrete Paver** (`7.87" L × 3.94" W × 2.36" H` 60mm or `7.75" × 4" × 1.75"` 45mm) + $45^\circ$ chamfered corners | **`Charcoal Blend` (`#21703`)** / **`Antique Grey` (`#21778-AGR`)** or **`Sierra Blend` (`#21777`)** / **`Old Town Blend` (`#15699`)** (soil-flush) | All grass-to-bed perimeters ($\approx 195\text{ lin ft}$: `315 pcs` single row or `625 pcs` double/crosswise) & $2.0\text{ ft}$ foundation buffer |
| **Edging (Track A)** | Extruded concrete landscape curbing | Stamped stone texture, mid-grey ($6\text{ in}$ raised) | All S-curve beds and gravel borders |
| **Fire Feature** | Rectangular propane gas fire pit table | Dark bronze / espresso aluminum frame, $50,000\text{ BTU}$ | Center of covered concrete patio |
| **Outdoor Rug** | Polypropylene all-weather flatweave | Charcoal, warm grey, and cream geometric/medallion | Under patio sectional / armchair grouping |
| **Fence Accents** | Western Red Cedar $1 \times 4\text{ in}$ horizontal slats + steel trellises | Espresso wood stain + matte black powder-coated steel | Left white vinyl fence (Backyard View 1) |
| **Low-Voltage Lighting** | $12\text{V}$ LED landscape system ($2700\text{K}$ warm white) | Matte black / bronze fixtures | Tree uplights, back wall wash, under-cap bed LEDs |

---

## 6. Recommended Plant Schedule (Including $4.0\text{ ft}$ Western Wall Juniper & Perennial Bed)

All plants selected for structural contrast, low maintenance, reflected-heat resilience, and cold-hardy performance:

1. **Western Wall Bed ($4.0\text{ ft}$ Deep $+ 6\text{"}$ Paver $= 4.5\text{ ft}$ to Grass; $wx = 0.0\text{ ft}\text{–}4.0\text{ ft}, wy = 0.0\text{ ft}\text{–}50.0\text{ ft}$):**
   * **Primary Architectural Layout — `10 Upright Lush Green Junipers (2 per 10.0 ft Panel @ 5.0 ft On-Center)` (`J1`–`J10` at $wy = 2.5', 7.5', 12.5', 17.5', 22.5', 27.5', 32.5', 37.5', 42.5', 47.5'$, $wx = 1.85'$):**
     * **Why 10 Trees (`2 per Panel`) Solves All 4 Goals (City Works Screening + Afternoon Shade + Zero Claustrophobia + Symmetry):** Placing **10 narrow upright green junipers (`2 inside each 10.0 ft panel` at $2.5'$ and $7.5'$ of each bay = $5.0\text{ ft}$ O.C.)** keeps every $10\text{ ft}$ precast panel $100\%$ symmetrical, leaves all 6 concrete columns completely exposed, keeps **$40\%\text{–}50\%$ of the lower stone wall open** so the $30\text{ ft}$ backyard never feels claustrophobic, and rises **$12\text{ to }19\text{ ft}$ above the $6\text{ ft}$ concrete wall** ($18\text{–}25\text{ ft}$ total height) to block the neighboring **City Works buildings and antennas** while casting deep afternoon shade across the lawn and patio.
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

* **View 1 Prompt (Backyard — House & Pergola):**
  > *"Edit this backyard photo to keep almost 100% of the open green grass intact while upgrading the vertical surfaces and patio. On the left white vinyl fence, mount three dark espresso-stained horizontal cedar slat accent panels alternating with flat black metal trellises with climbing vines, keeping the grass growing right up to the fence line. In the far back-left corner, place a small triangular pocket bed with a single multi-stem serviceberry tree lit by a warm uplight. On the right side, stain the raised garden beds dark espresso to match the pergola, keep grass right up to the beds, and embed a single curving row of flat natural flagstone stepping stones completely flush with the lawn leading from the concrete patio to the garden beds. Under the pergola, add a patterned outdoor rug under the grey sectional, replace the coffee table with a rectangular dark espresso propane fire table with warm flames, and hang two flowering baskets from the pergola posts. Maintain the twilight sunset lighting."*

* **View 2 Prompt (Backyard — Back Wall & Patio Seating):**
  > *"Edit this backyard photo to preserve the entire expanse of green lawn while upgrading the perimeter and patio. Keep the mulch bed along the back stone concrete wall in its original narrow, straight footprint, bordered by a flat concrete mowing strip flush with the grass. Inside that narrow bed, alternate groups of the existing arborvitae evergreens with upright Karl Foerster ornamental grasses and compact purple Russian sage, illuminated by warm low-voltage uplights at their bases. In the back-right corner, keep the three dark espresso raised garden boxes, bring the green turf up to the beds, and set a curving row of flat flagstone stepping stones completely flush into the grass from the patio corner to the garden beds. On the concrete patio foreground, replace the lightweight black chairs and small table with four deep-seated dark-frame outdoor armchairs with grey cushions arranged around a rectangular dark metal propane fire table with warm flames on a patterned outdoor rug."*

* **View 3 Prompt (Front Yard — Maximum-Grass Curb Appeal):**
  > *"Edit this front yard photo to maximize the unbroken green lawn while enhancing curb appeal and functionality. Keep the large rectangular front lawn completely intact without cutting a walkway through the middle of the grass; instead, add a 24-inch wide natural flagstone step-out border flush along the left edge of the concrete driveway that connects into soil-flush flagstone steppers tucked along the edge of the foundation mulch bed leading to the front porch. Inside the existing front-left mulch bed, surround the back and sides of the green metal utility box with a neat U-shaped screen of 3-foot upright ornamental grasses and compact evergreens, and plant a single red-leaf Japanese Maple tree inside the mulch bed just behind the utility box for vertical scale. Upgrade the foundation mulch bed along the stone wainscot with neat mounds of purple lavender and low evergreens bordered by concrete curbing. Maintain the dusk sunset sky."*

### 7.2 Track A Prompts (Lush S-Curve & Gravel Pad Design)

* **View 1 Prompt (Backyard — S-Curve & Gravel Pad):**
  > *"Edit this backyard photo to add sweeping S-curve garden beds bordered by 6-inch raised grey concrete curbing along the left white vinyl fence, planted with trellised purple clematis, Russian sage, ornamental grasses, and a focal tree in the back-left corner with warm uplighting. On the right side, stain the raised garden beds dark espresso and place them on a dedicated crushed grey gravel pad bordered by S-curved concrete curbing, with large flagstone stepping stones inlaid in the gravel leading from the patio to the back gate. Under the pergola, add a patterned outdoor rug and a rectangular propane fire table."*

* **View 2 Prompt (Backyard — S-Curve Back Wall):**
  > *"Edit this backyard photo to widen the back wall mulch bed into a flowing S-curve bordered by 6-inch concrete curbing, layering purple Russian sage, ornamental grasses, and colorful perennials in front of the existing row of arborvitae trees with warm landscape lighting. Connect the concrete patio to the back-right dark-stained garden beds with a curving crushed gravel pathway inlaid with large flagstone stepping stones. Upgrade the patio furniture to cushioned dark armchairs on an outdoor rug around a rectangular propane fire table."*

* **View 3 Prompt (Front Yard — Mid-Lawn Walkway):**
  > *"Edit this front yard photo to add a curving 4-foot wide natural flagstone walkway leading from the concrete driveway through the grass to the front porch. Plant a Japanese Maple tree in a curbed mulch ring in the middle-left lawn, camouflage the green utility box near the sidewalk with dense ornamental grasses, and fill the curbed foundation beds with purple lavender and layered evergreens."*

---

## 8. Whole-Yard Decision Matrix & Engineering Rationale (6 Key Decisions)

### Decision 1: Straight Flush Paver Mow Strip (Home Depot Pavestone Holland Paver) + 45° Chamfered Corners & House Wall Transition
* **Locked-In Lawn Perimeter & Paver Selection Rules:**
  * **Zero Curvy / S-Curve Edging:** All lawn borders use clean, straight geometric runs ($\approx 195\text{ linear ft}$ total: $120\text{ lin ft}$ Backyard + $75\text{ lin ft}$ Front Yard).
  * **Selected Home Depot Paver (`Pavestone Holland Concrete Paver`):** Listed on `homedepot.com` by exact metric mold size ($200\text{ mm} \times 100\text{ mm}$) as **`7.87 in. L × 3.94 in. W × 2.36 in. H (60 mm)`** ($\approx \$0.68\text{–}\$0.78/\text{brick}$) or **`7.75 in. L × 4 in. W × 1.75 in. H (45 mm)`** ($\approx \$0.58\text{–}\$0.68/\text{brick}$). Includes built-in side spacer nubs and micro-chamfered top edges so mower wheels roll smoothly without catching.
  * **Selected Colors:** **`Charcoal` / `Charcoal Blend` (`#21703` / SKU `204701612`)** or **`Antique Grey` (`#21778-AGR` / SKU `301595154`)** for high-contrast framing between dark mulch and green turf; or **`Sierra Blend` (`#21777` / SKU `204701614`)** / **`Old Town Blend` (`#15699` / `#22099`)** to tie into the `3152` front stone wainscot and rear precast wall.
  * **Quantity & Layout Options (`~195 lin ft` + $5\%$ waste):** **Single Lengthwise Ribbon (`3.94"` wide)** = **`315 bricks` (~$220–$245)**; or **Crosswise / Staggered Double Row (`7.87"` wide)** = **`625 bricks` (~$430–$485)**.
  * **45° Paver Corners Everywhere:** Every $90^\circ$ turf corner is replaced by a **$45^\circ$ chamfered paver corner** ($2.0\text{ ft} \times 2.0\text{ ft}$ diagonal transition with $22.5^\circ$ miter cuts) so the mower turns smoothly in one pass without backing up or scalping corners.
  * **Where Grass Meets Flat Concrete (Patio, Porch Walkway, Driveway, Sidewalk):** *No extra pavers needed*—the flat poured concrete slab already acts as a built-in flush mower strip, avoiding a redundant "double-concrete" seam.
* **Recommended Option — $2.0\text{ ft}$ Foundation Rock/Mulch Drip Buffer + Flush Holland Paver Edging:**
  * **Solves the $11.0\text{ ft}$ Rear Wall & Window Well ($4.0\text{ ft} \times 1.3\text{ ft}$):** A $2.0\text{ ft}$ rock buffer ($X = 28.0\text{ ft}\text{–}30.0\text{ ft}$) completely encloses the $1.3\text{ ft}$ deep metal window well grate and downspout so the paver strip runs straight across without awkward notches.
  * **Mower Handlebar & Stucco Clearance:** A narrow strip right against a vertical wall is too tight for a mower deck/handlebar without scraping the stucco. A $2.0\text{ ft}$ buffer gives full knuckle and mower clearance.
  * **Prevents Hard-Water Stains & Basement Seepage:** Keeps turf sprinklers $2\text{ ft}$ away from the stucco weep screed and basement window well.
* **Alternative Option — Paver Strip Tight Against Stucco Foundation:**
  * Runs turf all the way to a paver strip laid directly against the vertical house foundation wall (requires notching around the $4.0\text{ ft} \times 1.3\text{ ft}$ basement window well grate and risks sprinkler overspray on stucco).

### Decision 2: NW Backyard Raised Garden Bed Layout (7 Cedar Boxes @ $6.0\text{ ft} \times 3.0\text{ ft} = 126\text{ sq ft}$)
* **Option B (Recommended) — "Gate-Clear Utah" (`2 Patio + 4 North Fence + 1 West Wall`):** Keeps 2 boxes North of the patio ($4.5\text{ ft}$ clear of the basement window well) and 4 boxes along the North fence, moving the 5th North box onto the sunny West precast wall (`W1`). Opens a full **$10.25\text{ ft}$ wide turnaround** at the NW house corner so trailers, ATVs, or wheelbarrows can drive straight through the North vehicle gate.
* **Option A — "Your Utah" (`2 Patio + 5 North Fence`):** Places 2 N–S boxes North of the patio and 5 N–S boxes along the North fence ($1.75\text{ ft}$ gaps). Preserves the entire West wall for trees/shrubs, but Box `N5` extends to $X = 24.5\text{ ft}$, leaving a $5.5\text{ ft}$ diagonal pinch point at the NW house corner.
* **Option C — "Sunny NW Wall L" (`4 North Fence + 3 West Wall`):** Hugs all 7 boxes along the NW perimeter walls in $100\%$ unobstructed sun and leaves the $20\text{ ft} \times 12.5\text{ ft}$ area North of the patio completely open.

### Decision 3: Propane Fire Pit Placement ($21.0\text{ ft} \times 12.5\text{ ft}$ Existing Patio)
* **Option A (Recommended — Melinda's Idea) — On Existing Concrete Patio (2-Zone Split):** Divides the $21.0\text{ ft}$ patio into **Zone 1 ($9.5\text{ ft} \times 12.5\text{ ft}$ Grill & Dining near sliding door)** and **Zone 2 ($11.5\text{ ft} \times 12.5\text{ ft}$ Fire Pit Lounge)** with a convertible rectangular propane fire table ($28\text{ in} \times 48\text{ in}$ or $32\text{ in} \times 52\text{ in}$). Zero hardscape cost and $0\text{ sq ft}$ grass lost.
* **Option B — Connected Patio Corner Bump-Out:** Adds an $8\text{ ft} \times 8\text{ ft}$ or $10\text{ ft}$ paver extension off the outer patio corner ($+64\text{--}80\text{ sq ft}$ pavers).
* **Option C — Dedicated Backyard Corner Pad:** $13.5\text{ ft}$ diameter circle in the SW backyard corner (requires $9.5\text{ ft}$ center setback from vinyl fences; loses $\approx 150\text{ sq ft}$ lawn).

### Decision 4: Side-Yard White Vinyl Fence Setbacks & Gate Positions ($145.5\text{ lin ft}$)
* **Option A (Recommended) — Relative Stucco Setback (`N: X = 70.0' | S: X = 57.5'`):**
  * **North Side (Garage):** $8.0\text{--}8.5\text{ ft}$ Double-Swing Vehicle Gate at $X = 70.0\text{ ft}$ ($3.2\text{ ft}$ behind NE garage face, cleanly behind the $2.0\text{ ft}$ stone masonry wrap and downspout). Encloses $360.0\text{ sq ft}$.
  * **South Side (Porch):** $4.0\text{ ft}$ Single-Swing Pedestrian Gate at $X = 57.5\text{ ft}$ ($2.2\text{ ft}$ behind SE stucco corner / $8.2\text{ ft}$ behind `3152` porch pillar). Encloses the gas and electric meters ($X = 51.0\text{ ft}\text{–}54.5\text{ ft}$) behind the gate while framing the front stone pillar. Encloses $247.5\text{ sq ft}$.
* **Option B — Flush SE Stucco Corner Alignment (`N: X = 70.0' | S: X = 59.7'`):** Places the South pedestrian gate flush with the SE stucco corner ($6.0\text{ ft}$ behind the porch column), gaining $19.8\text{ sq ft}$ of enclosed side yard.

### Decision 5: North & South Side Yard Surfacing, Walkway & Utility Screening
* **Option A (Recommended) — South Flagstone Path + AC Screen & North Utility/Trailer Pad:**
  * **South Side Yard (Human Gate, $9.0\text{ ft} \times 29.7\text{ ft}$):** Large charcoal flagstone steppers inlaid in grey crushed granite gravel, shade plantings (hostas, ferns, ornamental grasses) along the house wall, and a **horizontal cedar-slat screen** hiding the $3\text{ ft} \times 3\text{ ft}$ AC unit while preserving a $6.0\text{ ft}$ walk path.
  * **North Side Yard (Vehicle Gate, $9.0\text{ ft} \times 43.2\text{ ft}$):** Compacted crushed stone/road-base utility pad over commercial weed barrier from the $8.5\text{ ft}$ double gate to the backyard for trash bins, trailer/mower parking, and clean access to the water spigot ($X = 51.0\text{ ft}$) and raised garden beds.
* **Option B — Poured Concrete North RV/Utility Pad + Gravel/Stepper South Corridor:** Pours a $4\text{-inch}$ concrete slab down the $9.0\text{ ft}$ North side yard paired with gravel and steppers on the South side.

### Decision 6: Front Yard ($813.5\text{ sq ft}$), Utility Box Camouflage & $6.0\text{ ft}$ Park Strips
* **Option A (Recommended) — Open Front Lawn + 3-Sided Utility Box Grass Screen + Water-Wise $6\text{ ft}$ Park Strips:**
  * **SE Front Lawn ($555.0\text{ sq ft}$):** Continuous lush turf with straight $6\text{-inch}$ flush paver edging and $45^\circ$ corners; focal specimen tree (*Japanese Maple* or *Little Gem Magnolia*) planted inside the foundation bed corner with lavender and boxwoods.
  * **Green Utility Transformer Box ($X = 93.0\text{ ft}\text{–}96.4\text{ ft}, Y = 45.5\text{ ft}\text{–}48.5\text{ ft}$):** Tucked in the SE corner near the sidewalk and South property line; screened on 3 sides with upright *Karl Foerster* feather reed grasses inside a $2.0\text{ ft}$ buffer bed with $6\text{-inch}$ chamfered pavers (leaving the East service face accessible from the sidewalk).
  * **NE Front Strip ($258.5\text{ sq ft}$):** Clean decorative rock or turf transition leading up to the $8.5\text{ ft}$ North vehicle gate.
  * **$6.0\text{ ft}$ Park Strips (South $21\text{ ft}$ / $\approx 126\text{ sq ft}$ & North $11\text{ ft}$ / $\approx 66\text{ sq ft}$):** Drip-irrigated decorative cobble/gravel with accent boulders and drought-hardy perennials/ornamental grasses (no narrow turf strips to edge or overspray onto the sidewalk/street).
* **Option B — Mid-Lawn Flagstone Walkway + Sod/Tree Park Strips:** Adds a $4.0\text{ ft}$ wide curving natural flagstone walkway across the SE front lawn and finishes the $6.0\text{ ft}$ park strips in lawn/street trees.

---

## 9. Complete 10-Angle CAD-Reconciled Concept Render Inventory (`photos_backyard_ideas/`)

All 10 concept renderings in `photos_backyard_ideas/` are generated directly from the October 2026 site walkaround photos (`photos_current_backyard/`) and reconciled 1:1 against the Master CAD Blueprint (`cad_architectural_blueprint_3152.html`):

| # | Render File Path | Property Zone & Camera Angle | Base Site Photo (`photos_current_backyard/`) | Reconciled CAD Specification Shown |
| :--- | :--- | :--- | :--- | :--- |
| 1 | `photos_backyard_ideas/render_backyard_pergola_north_planters.jpg` | **Backyard (Looking East)** | `PXL_20261022_004857161.MP.jpg` | $21.0'\times 12.5'$ concrete patio with dark-espresso timber pergola, warm bistro string lights, L-shaped sectional & propane fire table; **Left (North):** 5 N–S raised cedar planters ($3'\times 6'$) in $8.0'$ gravel bed + $6"$ flush pavers ($8.5'$ to grass), $2.0'$ basement window well rock buffer, and full poured concrete North side yard + $8.5'$ double gate; **Right (South):** $2.0'$ Southern berry/pea/kiwi trellis bed + $4.0'$ single walk gate. |
| 2 | `photos_backyard_ideas/render_backyard_west_juniper_bed_patio.jpg` | **Backyard (Looking NW from Patio)** | `PXL_20261022_004940478.MP.jpg` | $4.0'$ deep Western precast wall bed ($+6"$ flush pavers = $4.5'$ to grass) planted with **6 upright columnar Junipers spaced $8.0'$ on-center** (`J1–J6`) and inter-bay perennial trios (*Karl Foerster* feather reed grass, purple *Russian Sage*, coral *Coneflower*) with $2700\text{K}$ uplights; 5 N–S North fence planters in $8.0'$ gravel zone; $45^\circ$ chamfered paver corners; unbroken lawn; propane fire table lounge on patio. |
| 3 | `photos_backyard_ideas/render_backyard_nw_five_planters_window_well.jpg` | **Backyard (Looking SE from NW Corner)** | `PXL_20261022_004913415.MP.jpg` | Close-up along the North white vinyl fence showing all **5 N–S raised cedar planters ($3.0'\text{ W} \times 6.0'\text{ D}$)** with $1'$ N space, $2'$ gravel walking aisles, and $1'$ S space + straight $6"$ flush pavers ($8.5'$ total to grass); $2.0'$ river rock drip buffer enclosing the $4.0'\times 1.3'$ basement egress window well grate on the $11.0'$ rear wall; full poured cement North side yard entry; pergola & fire table on patio. |
| 4 | `photos_backyard_ideas/render_backyard_south_berry_west_juniper_panoramic.jpg` | **Backyard (Looking SW Panoramic)** | `PXL_20261022_004925322.MP.jpg` | Full $50.0'$ N–S backyard span showing the **$2.0'$ deep Southern white vinyl fence bed** ($+6"$ pavers = $2.5'$ to grass) planted with trellised raspberries, sugar snap peas, hardy kiwis, and alpine strawberries meeting the **$4.0'$ deep Western precast wall 6-Juniper bed** at a crisp $45^\circ$ chamfered paver corner across the $679\text{ sq ft}$ open lawn. |
| 5 | `photos_backyard_ideas/render_north_side_cement_pad_corridor.jpg` | **North Side Yard (Looking East from NW Corner)** | `PXL_20261022_162209617.MP.jpg` | **Full $9.0'\times 43.2'$ poured concrete (cement) North side yard utility/trailer pad** ($388.8\text{ sq ft}$ total / $360.0\text{ sq ft}$ inside gate) with saw-cut control joints, $70.0'$ North white vinyl fence on the left, $8.5'$ double-swing vehicle gate (`wx = 70.0'`) & trash bins at the East end, exterior hose bib (`wx = 51.0'`), easternmost cedar planter on the bottom-left, and $2.0'$ rear window well rock buffer + $45^\circ$ chamfered pavers on the bottom-right. |
| 6 | `photos_backyard_ideas/render_north_vehicle_gate_ne_strip.jpg` | **North Vehicle Gate & NE Strip (Looking West)** | `PXL_20261022_162017040.MP.jpg` | **$8.5'$ wide double-swing white vinyl vehicle gate** spanning the $9.0'$ North side yard at `wx = 70.0'` (**set back $3.2'$ West of NE garage face / $1.2'$ behind the $2.0'$ decorative stone masonry corner wrap & downspout** so the stone wrap is $100\%$ visible), poured concrete driveway apron connection, and water-wise river rock/boulder/ornamental grass landscaping in the $11.0'\times 23.5'$ NE front strip. |
| 7 | `photos_backyard_ideas/render_south_side_flagstone_ac_screen.jpg` | **South Side Yard Corridor (Looking West)** | `PXL_20261022_004709213.MP.jpg` | $9.0'$ wide South side corridor with **100% straight $6"$ flush paver edging** (zero S-curves), straight **$2.0'$ Southern fence shade/berry/kiwi bed** along the left white vinyl fence, straight $6.0'$ charcoal crushed granite walkway inlaid with natural buff-grey flagstone steppers, straight $2.0'$ house-wall buffer under the gas/electric meters (`wx = 51'–54.5'`), horizontal dark-espresso cedar slat privacy screen around the $3'\times 3'$ AC condenser (`wx = 45'–48'`), and SW backyard lawn + West juniper wall in the background. |
| 8 | `photos_backyard_ideas/render_south_gate_porch_entry.jpg` | **South Pedestrian Gate & `3152` Porch (Looking West)** | `PXL_20261022_162104480.MP.jpg` | **$4.0'$ single-swing white vinyl pedestrian walk gate + $5.0'$ fixed vinyl wing panels** set back **$2.2'$ West of the SE stucco corner (`wx = 57.5'`, $8.2'$ behind the `3152` stone column)** so the gas/electric meters and AC unit are enclosed behind the gate while leaving the `3152` stone column and siding return $100\%$ visible; framed by $2.0'$ front-of-porch and South property-line beds with straight $6"$ flush pavers and $45^\circ$ chamfered corners. |
| 9 | `photos_backyard_ideas/render_front_se_lawn_chamfered_beds.jpg` | **SE Front Yard & Utility Box Screen (Looking NW)** | `PXL_20261022_004655951.MP.jpg` | $555\text{ sq ft}$ SE front lawn framed on all interior sides by **straight $2.0'$ wide dark-mulched beds** (along driveway, porch walkway, front of `3152` porch with Japanese Maple, South property line, and a 3-sided *Karl Foerster* feather reed grass screen wrapping $2.0'$ around the green utility box at `wx = 93.0'–96.4', wy = 45.5'–48.5'`) bordered by **continuous straight $6"$ flush pavers with $45^\circ$ chamfered corners**. |
| 10 | `photos_backyard_ideas/render_front_full_elevation_park_strips.jpg` | **Full Front Elevation & $6.0'$ Park Strips (Looking West)** | `PXL_20261022_004640801.MP.jpg` | Full Lot 3152 street elevation showing **water-wise $6.0'$ South ($21'$) and North ($11'$) street park strips** (`wx = 100.7'–106.7'`) landscaped with river cobble, sandstone boulders, ornamental grasses & lavender; $21.5'$ driveway + walkway; SE front lawn with $2.0'$ perimeter beds & $6"$ chamfered pavers; and **both recessed white vinyl side gates** (`57.5'` South walk gate & `70.0'` North double vehicle gate). |