# Magnetic Compass - PPL Notes (Oral/Checkride)

## Big Picture (What’s “true” vs “magnetic”)

- **True north (TN)**: Geographic north pole / lines of longitude converge here.
- **Magnetic north (MN)**: Where the Earth’s magnetic field points; it is **not** the same as true north and it **moves** over time.
- **Sectional charts**: Drawn using **true** references (lat/long grid is true). Variation info is printed so you can convert between true and magnetic.

## Variation (True vs Magnetic)

- **Magnetic variation**: The angle between **true north** and **magnetic north** at a location.
- On charts it’s shown with an **isogonic line** value (e.g., “10°E”, “6°W”) and changes over time (chart shows annual change).

### Converting headings/courses

- **True → Magnetic**: \(M = T \pm \text{Variation}\)
- Rule of thumb: **East is least, West is best**
  - If variation is **East**, subtract it from true to get magnetic.
  - If variation is **West**, add it to true to get magnetic.

Examples:
- \(T 090\) with \(10°E\) variation → \(M 080\)
- \(T 090\) with \(10°W\) variation → \(M 100\)

## Deviation (Compass vs Magnetic)

- **Compass deviation**: Error caused by magnetic fields in/near the aircraft (wiring, speakers, engine, metal structure).
- It varies with **heading** and is corrected using the **compass correction card**.

### Converting magnetic ↔ compass

- **Compass heading (CH)** is what the wet compass shows.
- Apply **deviation** from the card to convert:
  - \(C = M \pm \text{Deviation}\)
  - Same memory aid works: **East is least, West is best** (for whichever correction direction your card uses).

## “Heading” vs “Course” (What you say vs what you fly)

- **Heading**: Direction the nose points (what you steer).
- **Course / Track**:
  - **Course**: Desired path over the ground (planned).
  - **Track**: Actual path over the ground (result).
- **Wind correction angle (WCA)**: Difference between heading and course caused by wind.

### What’s on a sectional?

- **True course** is measured on the chart relative to **true north**.
- In typical pilotage/DR, you measure **true course**, then apply **variation** to get **magnetic course/heading**, then apply **wind correction** to get a **magnetic heading** to fly, then apply **deviation** to know what compass heading shows.

## Runway Headings (Why runway numbers look the way they do)

- Runways are numbered based on their **magnetic direction** (magnetic azimuth), rounded to the nearest **10 degrees**, with the last digit dropped.
  - Example: A runway aligned ~184° magnetic is **Runway 18**.
  - Opposite direction differs by ~180° → Runway 18/36, 09/27, etc.
- Runway numbers can change over the years as **magnetic variation** changes enough to justify re-designation.

## What you say on the radio (headings, not courses)

- If ATC says: “**Fly heading 270**,” you fly a **heading** (magnetic in most systems) regardless of your planned course.
- If ATC says: “**Proceed direct**” or “**Join Vxxx**,” that’s more like a **course/track** requirement; you will still steer headings as needed for wind.
- On CTAF/Unicom (non-towered), pilots commonly announce:
  - **Runway** (e.g., “departing runway 27”)
  - Position and intentions
  - Not usually “true” anything—operations are conventionally referenced to **magnetic** (runways, headings).

### Is ATC-reported wind magnetic or true?

- **Tower/ATC/ATIS wind for takeoff/landing** is given in **magnetic degrees**, to match:
  - **Runway magnetic heading**, and
  - The **magnetic heading** you will actually fly.
- **METAR/TAF winds** are normally in **true degrees** in the coded report, but what you hear on **ATIS/AWOS/ATC** for runway operations is **magnetic**.
- Oral takeaway:  
  - **Headings, runways, and ATC instructions = magnetic.**  
  - **Charts, “true course,” and high‑level winds aloft = true.**

## Magnetic Compass Errors (The classics)

The magnetic compass is reliable for **steady, unaccelerated, straight-and-level** flight, but it has well-known errors when turning or accelerating.

### Acceleration/Deceleration Error (ANDS)

In the **Northern Hemisphere**:
- **Accelerate** → compass indicates a **turn to North**
- **Decelerate** → compass indicates a **turn to South**

Memory aid: **ANDS** = **A**ccelerate **N**orth, **D**ecelerate **S**outh

What to say in an oral:
- On an east/west heading, if you add power and accelerate, the compass will momentarily show a turn toward **north** even if you’re not turning.
- If you pull power and slow down, it will momentarily show a turn toward **south**.

### Turning Error (UNOS)

In the **Northern Hemisphere**:
- **U**ndershoot **N**orth
- **O**vershoot **S**outh

Memory aid: **UNOS**

What it means:
- When turning **to a northerly heading**, the compass **lags** → you must **stop the turn early** (undershoot north).
- When turning **to a southerly heading**, the compass **leads** → you must **stop the turn late** (overshoot south).

Why it’s worst near north:
- The compass is most unstable and sluggish near **north** because of how the magnetic field lines dip; turning indications can be most misleading there.

### Practical examples (oral-style)

- **Turning to North**: You’re rolling out on 360. The compass is lagging, so you roll out **before** the compass reaches 360.
- **Turning to South**: You’re rolling out on 180. The compass is leading, so you roll out **after** the compass passes 180.

## Quick Conversion Flow (What examiners like)

1. **Measure true course** on sectional (true).
2. Apply **variation** → **magnetic course/heading**.
3. Apply **wind correction** → **magnetic heading** to steer.
4. Apply **deviation** (compass card) → **compass heading** you’ll see.

## Common Oral Questions (with short answers)

- **Q: Are sectionals true or magnetic?**  
  **A:** They’re referenced to **true** (lat/long grid). You apply **variation** to convert to magnetic.

- **Q: Are runway numbers true or magnetic?**  
  **A:** **Magnetic**, rounded to the nearest 10°.

- **Q: What does ATC mean by “fly heading 090”?**  
  **A:** Fly a **magnetic heading** of 090 (unless local procedures specify otherwise).

- **Q: Difference between variation and deviation?**  
  **A:** **Variation** is Earth (true vs magnetic). **Deviation** is aircraft (compass error due to onboard magnetism).

- **Q: What are the acceleration and turning errors?**  
  **A:** In the Northern Hemisphere: **ANDS** and **UNOS**.

