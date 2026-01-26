## 1. METAR (Current Observation)

**METAR** (Meteorological Aerodrome Report) is a snapshot of what is happening **now**. They are usually issued every 30 or 60 minutes.

### The Anatomy of a METAR

Example: `VTBS 261230Z 24010G15KT 9999 TSRA FEW020CB BKN030 30/25 Q1008 NOSIG`

| Section | Code | Interpretation |
| --- | --- | --- |
| **Location** | `VTBS` | Suvarnabhumi Airport, Bangkok. (EASA examples: `EGLL`, `LFPG`). |
| **Date/Time** | `261230Z` | 26th day of the month, 12:30 Zulu (UTC). |
| **Wind** | `24010G15KT` | From 240° (True) at 10 knots, gusting to 15 knots. |
| **Visibility** | `9999` | 10km or more (Unlimited for VFR). `0500` = 500 meters. |
| **Weather** | `TSRA` | Thunderstorm (`TS`) and Rain (`RA`). |
| **Clouds** | `FEW020CB` | Few clouds at 2,000ft, specifically Cumulonimbus (`CB`). |
| **Temp/Dew** | `30/25` | Temp 30°C / Dewpoint 25°C. (Small spread = Fog risk). |
| **Pressure** | `Q1008` | QNH is 1008 hPa (Standard in EASA/CAAT, vs. `A2992` in USA). |
| **Trend** | `NOSIG` | No Significant Change expected in the next 2 hours. |

---

## 2. TAF (The Forecast)

**TAF** (Terminal Aerodrome Forecast) tells you what weather is **expected** over the next 9 to 30 hours.

### Key "Change Groups" in TAFs

* **BECMG (Becoming):** A permanent change over a period.
* *Ex: `BECMG 1214 0000` means between 12Z and 14Z, visibility will drop to 0 and stay there.*


* **TEMPO (Temporary):** Short-lived fluctuations (lasting < 1 hour).
* *Ex: `TEMPO 0810 TSRA` means brief thunderstorms are possible between 08Z and 10Z.*


* **PROB30 / PROB40:** The probability (30% or 40%) of a condition occurring.
* **Pro-tip:** In checkrides, treat PROB30 as a 100% certainty for safety planning!



---

## 3. Critical Codes & Abbreviations

Use this table to decode the "alphabet soup" of significant weather:

| Code | Meaning | Severity / Note |
| --- | --- | --- |
| **CAVOK** | Ceiling and Visibility OK | Vis >10km, No clouds <5000ft, No CB/TCU. |
| **NSC** | No Significant Cloud | No clouds below 5000ft, but visibility might be poor. |
| **FG / BR** | Fog / Mist | `FG` is <1000m visibility; `BR` is ≥1000m. |
| **TS / CB** | Thunderstorm / Cumulonimbus | High danger (turbulence/icing/windshear). |
| **HZ / FU** | Haze / Smoke | Common in Thailand during "burning season" (Jan–Mar). |
| **WS** | Wind Shear | Often found in the remarks: `WS RWY01R`. |

---

## 4. EASA vs. CAAT Nuances

While the format is identical, the **operational impact** differs:

1. **Units:** Both use **hPa** (Hectopascals) for pressure and **Meters** for visibility. (The US uses Inches of Mercury and Statute Miles).
2. **Thailand (CAAT) Specifics:** * **Monsoon/Heat:** You will frequently see `VRB02KT` (Variable winds) and very high temperatures, which affects your **Density Altitude**.
* **Vicinity Weather:** `VCTS` (Thunderstorm in the vicinity) is extremely common in Thailand and implies severe convection nearby even if the airport is clear.


3. **Europe (EASA) Specifics:**
* **Icing/Snow:** You will see `SN`, `FZRA` (Freezing Rain), and `M02` (Minus 2°C) much more often, requiring anti-ice/de-ice knowledge.



---

## Summary Checklist for Interpretation

1. **Check the Date/Time:** Is it current? (Look for `Z`).
2. **Check the Wind:** Is it within your aircraft's crosswind limit?
3. **Check the Ceiling/Vis:** Is it above your VFR minima (e.g., 1500ft / 5km)?
4. **Look for "The Killers":** Search for `TS`, `CB`, `FG`, or `WS`.
5. **Check the Temperature Spread:** If the temp and dewpoint are within 2°C of each other, expect fog or low clouds to form.

**Would you like me to give you a "raw" METAR string from a real Thai or European airport right now for you to practice decoding?**