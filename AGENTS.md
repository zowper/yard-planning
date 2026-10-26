# AGENTS.md — AI Context Router & Canonical Quick-Reference (Lot 3152)

> **AI Indexing & Retrieval Mandate:** Do **NOT** search or grep every file in this repository. Start here. This file provides the **Topic $\rightarrow$ Single-Source-of-Truth (SSOT) Routing Table** and the **Machine-Readable Canonical State Block** for **Lot 3152** (Jared & Melinda Carter). Each domain specification lives in **strictly one** numbered file inside [`docs/`](./docs/) with zero cross-file duplication.

---

## 1. Topic $\rightarrow$ Single-Source-of-Truth (SSOT) File Routing Table

| If You Need Information About... | Read ONLY This Canonical File | Key Contents & Sections |
| :--- | :--- | :--- |
| **Dimensions, `(wx, wy)` Coordinates, Reconciliations, 4 Zones & 45-Item Schedule** | [`docs/01-site-measurements-and-coords.md`](./docs/01-site-measurements-and-coords.md)<br>*(+ CSV: [`docs/measurements.csv`](./docs/measurements.csv))* | Compass orientation (`West = Rear`, `East = Street`), tape-measure reconciliations (`50.0' W × 96.7' D` to walk / `108.7'` to curb), 1:1 `(wx, wy)` coordinate axes, 4-zone spatial table, 45-row reconciled measurement schedule, and 2D/3D web app software architecture. |
| **Fencing, Gates, Patio Awning (`#1C`), Ceiling Fans, Fire Table, 5 Cedar Boxes, Pavers, Road Base & White Rock** | [`docs/02-hardscape-fencing-and-structures.md`](./docs/02-hardscape-fencing-and-structures.md) | Material/finish/lighting palette, `145.5 lin ft` white vinyl fence & relative stucco gate setbacks (`wx=57.5'` S in 2026, `wx=70.0'` N in 2027, 50/50 neighbor split vs. 100% gate ownership), Pavestone Holland paver mow strip rules (`~206–215 lin ft` + `45°` corners), `487 sq ft` compacted road base network, 5 N–S raised cedar boxes (`N1`–`N5`), and `Option #1C` 2-pillar solid-roof timber patio awning + 2× `52"` lighted ceiling fans (`F1` & `F2`) + L-sectional & propane fire table. |
| **Trees, Plants, `5+4` West Wall Hybrid, Norwegian Sunset® Maple, Melinda's Hyacinths, Pruning & Turf** | [`docs/03-planting-and-botanical-schedule.md`](./docs/03-planting-and-botanical-schedule.md) | Continuous seeded turf (`~1,385 sq ft` continuing under South gate), West wall `5+4` hybrid (`5×` `'Standing Ovation'` Serviceberry pillars `S1`–`S5` + `4×` Upright Evergreen Junipers `J1`–`J4`), cultivar comparison matrix, 10-spot under-story ribbon (`wx=2.95'`), soil/clay planting instructions, SE Front Lawn **Norwegian Sunset® Maple** (`wx=83.0', wy=39.5'`) with 3-stage high-canopy pruning (`8.0'–9.5'` trunk $\rightarrow$ `11'–12'+` lawn ceiling) & 4-option placement audit, **Melinda's jewel-toned Spring Hyacinths**, continuous `2.0'` South bed to green box, and 3-sided utility box grass screen. |
| **Sprinklers (`28` Heads), 5 Hydrozones, Drip Irrigation, Backflow, Sleeves & Rain-Pooling Drainage** | [`docs/04-irrigation-and-drainage.md`](./docs/04-irrigation-and-drainage.md) | Point of Connection (`wx=51.0', wy=8.6'`), `1" Febco 765 PVB`, garage Wi-Fi controller (`wx=52.5', wy=10.2'`), dual manifolds (`M1` & `M2`), `2"` Schedule 40 road-base sleeves (`S-1`..`S-3`), 5-hydrozone hydraulics (`12.70 GPM` total), complete 28-head (`B1`–`B14`, `S1`–`S4`, `F1`–`F9`) coordinate/nozzle/arc/throw schedule (`PRS40-CV` check valves on low West heads `B1, B6, B8, B9, B11`; `0%` overspray rule), and Oct 2026 West-wall rain-pooling photos (`rain_pooling_01..03.jpg`), 7 engineering considerations & buried `4"` PVC downspout + catch-basin drainage plan. |
| **2026–2030 Phased Budget (`Phases 1–5`), DIY vs. Pro vs. Hybrid Costs & Procurement** | [`docs/05-phased-budget-roadmap.md`](./docs/05-phased-budget-roadmap.md) | Executive 5-year summary (`$19,930` Recommended Hybrid / `$18,015` All-DIY / `$33,070` All-Pro) and full line-item breakdown across Phase 1 (`2026`) through Phase 5 (`2030`). |
| **Site Photos (`33`), V2 Concept Renders (`14`), Quarantined Archive (`archive_v1/`) & AI Prompts** | [`docs/06-media-and-render-catalog.md`](./docs/06-media-and-render-catalog.md) | Complete catalog of [`photos_backyard_ideas/`](./photos_backyard_ideas/) (`13` V2 Gen-1 primary renders + `1` top-down drone render + strictly quarantined [`archive_v1/`](./photos_backyard_ideas/archive_v1/)), [`photos_current_backyard/`](./photos_current_backyard/) (`30` `.MP.jpg` walkaround photos + `3` `rain_pooling_01..03.jpg` photos + `thumbs/`), and 3D-guided Gen-1 AI prompts. |
| **Interactive Web Applications (Visual Showcase, 2D CAD Blueprint & 1:1 3D WebGL Model)** | [`index.html`](./index.html)<br>[`cad_architectural_blueprint_3152.html`](./cad_architectural_blueprint_3152.html)<br>[`model_3d_3152.html`](./model_3d_3152.html) | Root-level zero-build HTML applications served on GitHub Pages. `index.html` is kept **ultra-minimalist** (visual-first showcase with embedded iframes and interactive budget table). |

> **AI Visual Quarantine Rule (`photos_backyard_ideas/archive_v1/`):** AI agents and subagents are **STRICTLY FORBIDDEN** from viewing, reading, or passing any image inside `photos_backyard_ideas/archive_v1/` as a visual reference. Every V2 render in `photos_backyard_ideas/` must be a **Strictly Generation-1** output created directly from an unedited baseline dirt photo in `photos_current_backyard/` paired with a 1:1 3D/CAD spatial layout reference. If a render requires a tweak, regenerate from the virgin `photos_current_backyard/` photo—never re-edit an AI-generated output image.

---

## 2. Canonical Machine-Readable State Block (Lot 3152)

```yaml
project_context:
  lot:
    lot_number: "3152"
    owners: "Jared & Melinda Carter"
    area_acres: 0.11
    width_ns_ft: 50.0          # wy = 0.0' (North property line) to 50.0' (South property line)
    depth_to_sidewalk_ft: 96.7 # wx = 0.0' (East face of West precast wall) to 96.7' (West edge of city sidewalk)
    depth_to_curb_ft: 108.7    # + 4.0' sidewalk (96.7'-100.7') + 6.0' park strip (100.7'-106.7') + 2.0' curb (106.7'-108.7')
    area_to_sidewalk_sqft: 4835.0
    area_to_curb_sqft: 5435.0
    foundation_type: "Slab-on-grade (no basement, zero window wells anywhere on property)"
  compass_and_neighbors:
    west_wx_0: "Rear of property — 50.0' W x ~8.0' H precast concrete wall (5 panels @ 10.0' O.C., fluted columns at wy=0,10,20,30,40,50)"
    east_wx_108_7: "Front street curb — facing front of house from street is looking West"
    north_neighbor_wy_lt_0: "Completely empty bare dirt outside our 9.0' North side yard (6.0' H white vinyl fence)"
    south_neighbor_wy_gt_50: "White decorative rocks outside our 9.0' South side yard (6.0' H white vinyl fence; matched by our front park strips & NE strip; zero gravel on our South side)"
  house_and_patio_footprint:
    house_width_ns_ft: 32.0    # wy = 9.0' to 41.0'
    north_garage_wall_ft: 43.2 # wx = 30.0' to 73.2' (+0.3' front stone veneer to 73.5'; 2.0' stone wrap on N wall wx=71.2'-73.2')
    south_stucco_wall_ft: 29.7 # wx = 30.0' to 59.7' (front door plane)
    covered_porch_ft: "6.0' D x 12.0' W fdn (12.5' W w/ stone) at wx=59.7'-65.7', wy=29.0'-41.0'; '3152' pillar at wx=64.2'-65.7'; hanging swing at wy=35.8'-40.0'"
    concrete_patio_ft: "21.0' N-S x 12.5' E-W (262.5 sq ft, 4 quadrants @ 10.5'x6.25') at wx=17.5'-30.0', wy=20.0'-41.0'"
    driveway_and_walk_ft: "18.0' W driveway (wy=11.0'-29.0') + 3.5' W porch walk (wy=29.0'-32.5') x 23.5' L (wx=73.2'-96.7')"
    utilities:
      north_hose_bib_poc: "wx = 51.0', wy = 9.0' (Irrigation POC & 1-in Febco 765 PVB at wy=8.6')"
      south_open_ac_pad: "3.0' x 3.0' pad at wx = 45.0'-48.0', wy = 41.0'-44.0' — COMPLETELY OPEN (zero cover, zero shroud, zero gravel; wrapped on West, South & East by flush Holland pavers)"
      south_meters: "Electric meter (wx=51.0'-52.2') & gas meter (wx=52.8'-54.5', wy=41.0'-42.1') + green fiber/internet conduit (wx~49.8') strictly EAST of AC condenser over the continuous flush Holland paver strip along the South house wall (pavers notched ~4 in for power/internet/gas conduits, leaving ~3+ in of solid paver width)"
      front_se_green_box: "PacifiCorp transformer at wx = 93.0'-96.4', wy = 45.5'-48.5' (screened on N, W, S sides by 6x Karl Foerster grasses)"

locked_in_decisions:
  1_continuous_open_turf:
    total_seeded_area_sqft: 1435.0 # ~704.0 BY + 176.0 South 6.0' corridor wrap under gate (wx=30'-59.7', zero gravel!) + 555.0 SE Front Lawn (Phase 2, 2027)
    rule: "90%-95% open turf preservation; zero gravel on the South side — grass extends right up to the continuous flush Holland pavers along the entire South house wall (wx=30.0'-59.7', wrapping around the 3'x3' AC condenser pad at wx=45.0'-48.0' and returning to the house wall on the East side under the notched electric/internet/gas conduits) and continues directly under the wx=57.5' South walk gate into the SE front yard."
  2_flush_paver_mow_strip:
    product: "Home Depot Pavestone Holland Concrete Paver (60mm: 7.87x3.94x2.36 in OR 45mm: 7.75x4x1.75 in; uniform solid dark Charcoal #21703 / #475569)"
    linear_ft: 222 # ~138' Backyard/South House Wall & AC Wrap + ~84' Front (345-360 bricks single lengthwise row OR 680-710 bricks crosswise/double row)
    corner_style: "Zero S-curves; prominent 45-degree diagonal chamfered corners (2.0'x2.0' to 2.5'x2.5' with 22.5-deg miter cuts) for 1-pass mowing."
    west_wall_subbase: "6-in deepened trench lined with non-woven geotextile separation fabric + 3-4 in compacted 3/4-minus road base along the 50' West run (wx=4.0'-4.5') to prevent wet clay pumping & frost heave."
    placement_rule:
      installed: "Everywhere grass meets mulch, compacted road base, or the South house foundation wall (running continuously along the South wall from wx=30.0' to 59.7', wrapping around the 3'x3' Open AC Condenser pad at wx=44.5'-48.5', wy=41.0'-44.5', and continuing along the wall on the East side with ~4-in cutouts for the power/internet/gas ground conduits leaving ~3+ in of paver to spare)."
      not_installed: "NEVER where grass meets poured concrete (driveway, 21'x12.5' patio, 3.5' porch walkway, or 4.0' city sidewalk)."
  3_west_wall_5_plus_4_hybrid:
    bed_dimensions: "4.0' D mulch bed (wx=0.0'-4.0', crowned +3 to +4 in above paver grade in 2027) + 6-in paver (wx=4.0'-4.5') x 50.0' L (wy=0.0'-50.0') = 200.0 sq ft along the ~8.0' H West precast wall (Phase 3, 2028; root flares elevated +2 to +3 in)"
    panel_pillars_5x: "5x 'Standing Ovation' Serviceberry (Amelanchier alnifolia 'Obelisk', 15' H x 4.0' W, snow-white spring blossoms, summer Juneberries, red-orange fall) at wx=2.0', wy=5.0', 15.0', 25.0', 35.0', 45.0' (Alternates: 'Crimson Spire' Oak or 'Parkland Pillar' Birch)"
    column_junipers_4x: "4x Upright Evergreen Junipers ($20 Home Depot 'Spartan' or 'Taylor' Juniper, 18'-25' H x 3.0'-3.5' W) at wx=1.75', wy=10.0', 20.0', 30.0', 40.0'"
    understory_10_spots: "Alternating ribbon at wx=2.95' (wy=2.3, 7.6, 12.4, 17.6, 22.4, 27.6, 32.4, 37.6, 42.4, 47.4): 5x Catmint/Russian Sage + 5x Coneflower (wy=2.3..42.4) alternating with 5x 'Karl Foerster' Feather Reed Grass (wy=7.6..47.4)"
  4_compacted_road_base_and_5_cedar_boxes:
    road_base_total_sqft: 487.0 # Single bulk 3/4"-minus delivery in Phase 4 (2029): 360.0 N pad (wx=30'-70') + 33.0 rear path (wx=27'-30', wy=9'-20') + 94.0 garden paths
    cedar_boxes_5x: "5x Western Red Cedar boxes N1-N5 (3.0' W E-W x 6.0' L N-S = 90.0 sq ft growing area) at wy=1.0'-7.0' (+1' N & S gaps + 6-in paver = 8.5' to grass); wx = 5-8, 9.75-12.75, 14.5-17.5, 19.25-22.25, 24-27 (Flat dirt in 2028 -> Cedar boxes in 2029)"
  5_patio_awning_1c_fans_and_lounge:
    awning_spec: "Option #1C House-Attached 2-Pillar Solid-Roof Heavy-Timber Awning (Phase 5, 2030) — 100% OPEN ON ALL SIDES (zero privacy walls, zero house posts, zero center posts, zero translucent plastic)"
    pillars_2x: "P1 at (wx=18.0', wy=20.5') and P2 at (wx=18.0', wy=40.5'); 21.0' Glulam West header beam; 1x6 T&G cedar ceiling underneath + matte-black standing-seam steel roof & front gutter on top (NW downspout tied into 2027 buried 4-in PVC drain stub-out at P1)"
    ceiling_fans_2x: "2x 52-in wet/damp-rated outdoor ceiling fans with built-in dimmable warm (2700K/3000K) LED light kits below blades (0% blade strobing): F1 at (wx=23.75', wy=25.5') & F2 at (wx=23.75', wy=35.5')"
    furnishings: "North entry/BBQ zone (wy=20.0'-29.5') + South lounge zone (wy=29.5'-41.0') with L-shaped Sunbrella sectional, 8'x10' rug & rectangular 50,000 BTU propane fire table"
  6_side_yard_fencing_and_gates:
    total_linear_ft: 145.5 # 127.5 lin ft shared 6.0' H white vinyl property-line fence (split 50/50 w/ neighbors) + 18.0 lin ft 6.0' H gates/wings (paid 100% by us)
    west_swale_clearance: "2-in bottom-rail gap above grade across wx=0.0'-6.0' on both South (2026) and North (2027) 6.0' H vinyl fences so fences never dam the West wall swale."
    phase_1_2026_south: "57.5' South 6.0' H vinyl fence (wx=0.0'-57.5', 50% split = $1,210 Pro) + 9.0' return at wx=57.5' (2.2' W of SE corner) with 4.0' walk gate over grass & 5.0' wings (100% ours = $940 Pro) -> Total $2,150 Pro / $1,335 DIY"
    phase_2_2027_north: "70.0' North 6.0' H vinyl fence (wx=0.0'-70.0', 50% split = $1,590 Pro) + 9.0' return at wx=70.0' (3.2' W of NE corner) with 8.5' double vehicle gate (100% ours = $1,350 Pro) -> Total $2,940 Pro / $1,840 DIY"
  7_front_yard_maple_hyacinths_and_white_rock:
    norwegian_sunset_maple: "Centered in SE Front Lawn at (wx=83.0', wy=39.5') inside 6.0' dia octagonal paver mulch ring (30'-35' H x 20'-25' W spec; ~28'-32' H Utah). Pruned in 3 stages to 8.0'-9.5' trunk attachment (level w/ ~9.5' porch eave) -> 11.0'-12.0'+ outer lawn clearance ceiling via 45-deg ascending limbs + 15% crown thinning."
    melindas_hyacinths: "120+ jewel-toned fragrant Spring Hyacinths (Royal Purple, Delft Blue, Rose Pink, Lilac, White) + dwarf perennials in 2.0' porch-front bed (wx=65.2'-67.2', wy=31.0'-43.0') & continuous 2.0' South bed (wx=0.0'-96.7', wy=48.0'-50.0')."
    white_decorative_rock: "479.3 sq ft total (Front & NE Side Only — zero gravel on South side): 192.0 sq ft in both 6.0' street park strips (wx=100.7'-106.7') + 287.3 sq ft in NE front/side strip stopping cleanly at the wx=70.0' North fence/gate."
  8_five_hydrozone_irrigation_and_stormwater_drainage:
    total_flow_gpm: 12.70 # 28 directional Hunter PRS40 + MP Rotator / MP Side-Strip heads (0% overspray onto patio, pillars, or Open AC unit)
    stormwater_drainage_2027: "Buried 4-in smooth-wall PVC (SDR-35/Sch 40) NW (30',9') & SW (30',41') downspout drain lines (~140 lin ft) sloped East to front pop-up emitters (wx~95') + 2x 9x9-in West lawn catch basins at (wx=4.5', wy=12' & 38') + capped 4-in stub-out at (wx=18.0', wy=20.5') for 2030 Awning gutter (+$280 DIY / +$650 Pro in Phase 2)."
    zones:
      zone_1: "Backyard Full-Sun Turf (679 sq ft, Manifold M2): 15 heads (B1-B14, with PRS40-CV check valves on low West heads B1, B6, B8, B9, B11), 5.32 GPM"
      zone_2: "South Corridor Shaded Turf (176 sq ft, Manifold M1): 4 MP Side-Strip heads (S1-S4 at wx=35,44,53,62, wy=47.25'), 0.88 GPM (0% spray on Open AC)"
      zone_3: "SE Front Full-Sun Turf (555 sq ft, Manifold M1): 9 heads (F1-F9), 3.49 GPM"
      zone_4: "Perimeter Mulch Beds & Maple Ring 30 PSI PC Drip (Manifold M2): ~230 lin ft tubing, 1.63 GPM"
      zone_5: "5 Raised Cedar Boxes 25 PSI Grid Drip (Manifold M1): 5 per-box ball valves + 1/4-in grids, 1.38 GPM"
  9_five_year_budget_totals:
    phase_1_2026: { hybrid: 2150, diy: 1335, pro: 2150 }
    phase_2_2027: { hybrid: 5800, diy: 4700, pro: 10190 }
    phase_3_2028: { hybrid: 3580, diy: 3580, pro: 6680 }
    phase_4_2029: { hybrid: 2600, diy: 2600, pro: 5150 }
    phase_5_2030: { hybrid: 5800, diy: 5800, pro: 8900 }
    grand_total_2026_2030: { hybrid: 19930, diy: 18015, pro: 33070 }
```

---

## 3. Repository Maintenance & Synchronized Update Protocol

Whenever a design decision, coordinate, plant cultivar, or budget figure is updated:
1. **Update the Single Canonical Domain Module in [`docs/`](./docs/)** (`01` through `06`) rather than duplicating prose across multiple Markdown files.
2. **Sync the Machine-Readable State Block above** in [`AGENTS.md`](./AGENTS.md) and the summary table in [`README.md`](./README.md) if top-level dimensions or phase totals change.
3. **Sync the Interactive Web Applications** ([`index.html`](./index.html), [`cad_architectural_blueprint_3152.html`](./cad_architectural_blueprint_3152.html), and [`model_3d_3152.html`](./model_3d_3152.html)) if visual geometry, layer labels, or budget calculator rows are affected.
