## 📅 Project Progress

### ✅ Day 1 – Site Layout + Equipment Placement

**Goal:**  
Create a top-down conceptual layout of a municipal booster pump station to visualize the physical location and interaction of key electrical and mechanical components.

**Tools Used:**  
AutoCAD 2025

**Deliverables:**  
- `autocad/site_layout.dwg`
- `docs/screenshots/site_layout.png`
- Color-coded layer legend

**Key Components Included:**
- Electrical Room: MCC, PLC, RTU
- Pumps: P-101 & P-102 (50HP each)
- VFDs: VFD-1, VFD-2 (external-mounted)
- XFMR-UTIL: Utility transformer (12.47kV → 480V)
- XFMR-1: 480V → 208Y/120V transformer
- CPT-1: 480V → 120V control power
- LP-1: Lighting Panel (feeds HVAC, lights, outlets)
- HVAC unit
- SCADA Communications block
- Suction/Discharge headers with directional flow arrows

**Highlights:**
- Demonstrated understanding of physical layout and equipment relationships
- Applied standard AutoCAD layering and annotation techniques
- Clear flow of water and power throughout the facility
- Used industry-relevant naming conventions and tags

---

### ✅ Day 2 – Single-Line Diagram (SLD)

**Goal:**  
Create a simplified, top-down electrical distribution diagram showing how 480V 3-phase power is distributed to all major loads and subsystems.

**Tools Used:**  
AutoCAD 2025

**Deliverables:**  
- `autocad/single_line_diagram.dwg`
- `docs/screenshots/single_line_diagram.png`

**Key Components Represented:**
- XFMR-UTIL (12.47kV → 480V)
- Main Disconnect (480V, 3φ)
- MCC-1 (Motor Control Center)
- VFD-1 → P-101 (Pump 1, 50HP)
- VFD-2 → P-102 (Pump 2, 50HP)
- XFMR-1 → LP-1 (Lighting Panel, feeds HVAC/lights)
- CPT-1 → PLC + RTU (control and SCADA)

**Highlights:**
- Clear one-line representation of power flow
- Proper use of hierarchy: utility → disconnect → MCC → loads
- Accurate voltage labels and component functions
- Structured and readable layout for use in documentation and QA
