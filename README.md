# Precision Tweezers Grinder — Hack Club Stasis

An enclosure and hardware design for a precision tweezers grinder built during the Hack Club Stasis hackathon. This device provides a stable, motorized solution for sharpening and maintaining precision tools.

🌐 **OnShape CAD Workspace:** https://cad.onshape.com/documents/27c54b4b3d9ffb5c67df1a65/w/bfb7f68973eb2576e4aceb32/e/55b7abdc1bfcae4972785b61?renderMode=0&uiState=6a36ccd02e90be760462adf4

---

## 🛠️ Hardware & Components
* **Motor:** 5V DC Motor
* **Switch:** SPDT Toggle Switch
* **Power Input:** Direct USB Cable (modified 5V input)
* **Fasteners:** M3 Screws (tapped holes)



## 📑 Engineering Build Logs & Journal

### 🛠️ Log 1: Sketching and Main Measurements/Design
* **Focus:** Initial Component Gathering & Concept Layout
* Gathered all core project components: a 5V DC motor, SPDT switch, and USB power components.
* Sketched out all physical dimensions of the components by hand to translate the physical sizes into clean CAD parameters within OnShape.
 <img width="3072" height="4096" alt="IMG_20260617_184625" src="https://github.com/user-attachments/assets/5f65a715-04a4-47fc-bf0b-91ab8a404e72" />
<img width="4096" height="3072" alt="IMG_20260617_191351" src="https://github.com/user-attachments/assets/c9b2dafa-6726-4c2e-8543-8158931dcf88" />







### 💻 Log 2: Day 1 CAD Base
* **Focus:** Main Body Enclosure and Press-Fits
* Designed the primary motor and switch models in OnShape to visualize the spacing constraints.
* Built out the main body chassis and recessed a fitted compartment for the motor core.
* Designed mounting tabs for the top and bottom chassis split using $2.4\text{ mm}$ diameter guide holes optimized for custom tapping to M3 threads.
* Integrated a precise, low-clearance press-fit slot to securely friction-mount the SPDT switch into the outer shell wall.
<img width="1098" height="993" alt="Screenshot 2026-06-18 134315" src="https://github.com/user-attachments/assets/0f649fd7-2ffd-46e8-bda3-59b6e6b52413" />
<img width="410" height="272" alt="Screenshot 2026-06-18 134343" src="https://github.com/user-attachments/assets/fc289f16-4839-4418-989d-b574c40550d5" />
<img width="1167" height="811" alt="Screenshot 2026-06-18 134422" src="https://github.com/user-attachments/assets/395c25d8-2ae3-4069-aad9-650699a7ea0c" />
<img width="1202" height="953" alt="Screenshot 2026-06-18 134925" src="https://github.com/user-attachments/assets/43204c75-9c13-4792-baa8-af6d6c9d355c" />




### 🖨️ Log 3: First Print & CAD Refinements
* **Focus:** Proof of Concept & Tolerance Adjustment
* **Time Tracked:** 2 hours (1 hr 15 mins CAD / 45 mins assembly and tinkering)
* Manufactured the initial 3-part prototype assembly via a 3D printer.
* **Discovered Design Issues:**
  * The vertical alignment column on the base plate sat too close to the main structural wall, preventing clean fabrication with a standard $0.4\text{ mm}$ extrusion nozzle.
  * The raw Micro-USB cutout area required removal in favor of a specialized alignment pad on the lower chassis plate to simplify printing and increase wall stiffness.
  * The internal motor seating pocket wall required wider clearance for a smooth drop-in fit.
    <img width="3072" height="4096" alt="IMG_20260618_184531" src="https://github.com/user-attachments/assets/8b28d427-f4fa-4a4b-bddc-345c50e43a37" />
    <img width="3072" height="4096" alt="IMG_20260618_184612" src="https://github.com/user-attachments/assets/43dd02cd-1719-4025-93d1-5a172a9b2681" />
    <img width="3072" height="4096" alt="IMG_20260618_184643" src="https://github.com/user-attachments/assets/969909a0-bfd8-4ec8-a867-56b40f42bb09" />




### 🔧 Log 4: Final Adjustments & Part Fitment
* **Focus:** Hardware Integration & Mechanical Finish
* **Time Tracked:** 45 minutes (0.75 hours)
* Modified hole dimensions and re-worked the Micro-USB retention bracket constraints to lock it permanently in place against internal sliding forces.
* Fabricated the updated component set. All adjusted clearances matched physical parts perfectly.
* Tapped the main case guide holes for M3 hardware, routed all internal components, and securely bolted the entire enclosure shell together.
  <img width="3072" height="4096" alt="IMG_20260619_165453" src="https://github.com/user-attachments/assets/b64d5a09-8b8c-4ad8-8def-32aa76e3b88f" />
  <img width="3072" height="4096" alt="IMG_20260619_170158" src="https://github.com/user-attachments/assets/0f78ca31-7033-432c-8dc8-4c265975c3e6" />
  <img width="3072" height="4096" alt="IMG_20260619_170300" src="https://github.com/user-attachments/assets/1bde2355-fb0f-4b9a-9730-47c2daa04845" />




### ⚡ Log 5: Soldering & Final Assembly
* **Focus:** Wiring and Integration Challenges
* **Time Tracked:** 2 hours 20 minutes (2.33 hours)
* Hit unexpected integration friction while working with the standalone Micro-USB interface port. Soldering raw wires directly onto mini interface pins without creating solder bridges or wire detachment issues proved incredibly difficult.
* **Engineering Pivot:** Bypassed the unstable breakout interface port by stripping a standard USB power cable down to raw copper leads, routing it directly into the chassis, and soldering it inline.
* **Result:** Successfully closed the loop! The circuit operates reliably under full load. Future revisions will transition to a dedicated USB power breakout board for a cleaner commercial finish.
  <img width="3072" height="4096" alt="IMG_20260620_135519" src="https://github.com/user-attachments/assets/f6217956-919b-405f-9f29-312f2b370170" />
  <img width="3072" height="4096" alt="IMG_20260620_135528" src="https://github.com/user-attachments/assets/2ef09f8d-8820-4c3d-852e-370cdf1c0435" />

