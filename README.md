# Vehicle Aerodynamics: SolidWorks Design & Wind-Tunnel Testing

**University of Central Florida · Mechanical Engineering Measurements · Summer 2026**  
**Type:** Four-person academic team project  
**Methods and tools:** SolidWorks, wind-tunnel drag testing, Pitot/pressure instrumentation, Microsoft Excel

> **Project overview:** Our team designed and built a small vehicle model, measured its aerodynamic drag across multiple wind-tunnel airspeeds, and compared its performance with a reference vehicle using drag coefficients, Reynolds number, and uncertainty analysis.

📄 **[View the illustrated engineering case study (PDF)](Vehicle_Aerodynamics_Case_Study.pdf)** — prototype photos, test setup, graphs, key calculations, and engineering discussion.

## Engineering objective

Assess whether the custom vehicle's aerodynamic characteristics differed from a provided reference model. Because the vehicles had different frontal areas and were tested at different airspeeds, the comparison used **drag coefficient** rather than drag force alone.

## Project workflow

1. **Design and fabrication:** Developed a vehicle model in SolidWorks and fabricated a physical prototype that met course test requirements.
2. **Wind-tunnel testing:** Recorded drag measurements over increasing and decreasing airspeed sequences and repeated the procedure for the reference vehicle.
3. **Data analysis:** Calculated drag force, drag coefficient, and Reynolds number; fitted drag-versus-velocity data and evaluated experimental uncertainty.
4. **Flow visualization:** Observed the air wake around the model and discussed possible flow separation.

## Key results

| Metric | Student-designed vehicle | Reference vehicle |
|---|---:|---:|
| Highest recorded airspeed | 14.69 m/s | 15.57 m/s |
| Drag at the respective highest airspeed | 0.1167 N | 0.0765 N |
| Frontal area | 0.002503 m² | 0.001350 m² |
| Drag coefficient, *C<sub>D</sub>* | 0.355 ± 0.038 | 0.384 ± 0.038 |

**What the data show:** The student vehicle's **measured drag coefficient was approximately 7.6% lower** than the reference model's. However, the estimated uncertainty intervals overlap, so this result is **not conclusive evidence** of a performance improvement. The student model also had a higher measured total drag force at its own highest test speed; the two peak tests were performed at different airspeeds and frontal areas.

The quadratic fit of drag force versus airspeed yielded **R² = 0.9915**, consistent with drag increasing approximately with the square of velocity. The maximum recorded hysteresis/run-to-run difference was **0.344 g**, or **2.89%** of the maximum drag reading.

## Engineering methods

The project used the standard aerodynamic relationships:

- **Drag force:** `F_D = mg` (conversion from the sensor's mass-equivalent reading)
- **Drag coefficient:** `C_D = 2 F_D / (ρ V² A)`
- **Reynolds number:** `Re = ρ V L / μ`

At the highest recorded student-vehicle airspeed, the 11.9 g drag reading corresponds to approximately **0.1167 N**. The report used air density **1.2174 kg/m³** and student-vehicle frontal area **0.002503 m²** to calculate **C_D ≈ 0.355**.

## Limitations and next improvements

- The reference and custom models were not compared at identical maximum airspeeds.
- Drag-coefficient uncertainties of ±0.038 are **design-stage estimates**, not 95% confidence intervals; they overlap.
- Potential error sources include vehicle alignment, sensor zero offset, frontal-area estimates, model vibration, test-section wall effects, and wind-tunnel restarts between runs.
- A useful follow-up would repeat tests at matched speeds with multiple trials, test another CAD geometry, and compare the wind-tunnel data with a CFD simulation.

## Project attribution

This was a **four-person team project** in UCF Mechanical Engineering Measurements. The results and figures in the attached PDF come from the team's course report; this repository does not claim that one person independently completed all design, testing, and analysis tasks.

<!-- Before making the repository public, add a sentence describing your own verified contributions and confirm you have permission to publish team-produced photos, plots and results. If you have original SolidWorks files, add them in a separate follow-up commit. -->
