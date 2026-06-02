# The Universal Modular Laptop Cooler
**Designed by:** Him C. <himc.29z@gmail.com>

## The Problem with Regular Laptop Coolers
Most off-the-shelf laptop cooling pads have fixed fans locked into permanent positions. This creates a massive engineering flaw: every laptop model has its air intake vents in completely different locations. For example, the **Asus VivoBook S15 X530UN** has its intake vent tucked away in a single upper quadrant near the hinge. Generic coolers blast air at the solid plastic base of the laptop rather than the actual vents, wasting energy and dropping temperatures by only 1 to 2 degrees.

## My Solution
A universal, modular laptop ecosystem designed to adapt dynamically to **any** laptop's thermal layout. The system consists of three main components:

*   **The Grid Platform:** A robust, elevated chassis featuring a dense grid of mounting holes across the surface (similar to an engineering pegboard).
*   **Active Fan Blocks:** Interchangeable squares of varying sizes housing high-pressure 5V 1A blower fans lined with soft, open-cell foam gaskets. These modules bolt anywhere onto the grid to target your laptop's vents precisely, creating a localized airtight plenum chamber that forces cool air exactly where the internal heatsinks need it.
*   **Passive Support Blocks:** Non-ventilated modular blocks topped with high-friction rubber padding. These screw into the remaining grid coordinates to distribute the laptop’s weight evenly, ensuring a perfectly level typing surface with zero tipping risks.

---

## Why This Wins Over Generic Cooling Pads


| Feature | Cheap Generic Pads | High-End Turbo Pads (IETS/Llano) | My Modular Grid Design |
| :--- | :--- | :--- | :--- |
| **Targeted Vent Alignment** | ❌ No (Fixed fans blow at solid plastic) | ❌ No (Forcibly seals the *entire* laptop base) | **✓ Yes** (Fan modules adjust to match exact vent grids) |
| **Airtight Foam Seal** | ❌ No (Air escapes uselessly out the sides) | ✓ Yes (Requires loud, industrial turbo power) | **✓ Yes** (Localized seal provides max pressure efficiently) |
| **Future-Proof Utility** | ❌ No (Becomes obsolete if you buy a new laptop) | ⚠️ Partial (Only fits specific chassis dimensions) | **✓ Yes** (100% universal configuration layout) |
| **Noise & Efficiency** | Medium / Inefficient | ❌ Extremely Loud (Industrial high-RPM noise) | **✓ Low-Medium** (Optimized 5V airflow via smart placement) |
| **Ergonomic Stability** | ⚠️ Unbalanced on single-vent laptops | ✓ Yes | **✓ Yes** (Passive blocks eliminate chassis wobble entirely) |

---

## Project Specifications
*   **Power Architecture:** Safe, independent 5V USB power supply (optimally driven by a standard 5V 3A mobile phone charger block to safeguard laptop USB ports).
*   **Airflow Regulation:** Integrated low-voltage potentiometer/PWM controller circuit to adjust fan speeds dynamically and dial in the perfect static pressure envelope.

## What I Need Help With
I have fully mapped out the low-voltage electronics and have active access to a 3D printer. I am looking for intermediate/advanced CAD collaborators or open-source hardware developers to help me with:

1.  **Advanced Onshape Workflows:** Moving past basic part creation to optimize top-down multi-part design structures inside a single Part Studio.
2.  **Design for Manufacturing (DFM):** Calculating precise virtual clearances (e.g., the 0.2mm tolerance rule) so the interlocking grid blocks fit together perfectly on the very first try, optimizing limited school/maker print windows.
3.  **Mechanical Simulation:** Stress-testing the grid platform configuration under real-world load distributions to eliminate plastic warping or sagging over prolonged gaming/rendering sessions.
