# Chapter 10 Dosage + Video Study Guide

Sources:
- Quiz PDF: `/home/tesfa/ch10dosquiz.pdf`
- Video 1: https://youtu.be/dvQ4ZZ_MiWw — multi-step conversions, layover method, infant lb/oz → kg dose example
- Video 2: https://youtu.be/DTR-bRwzOMo — safe metric notation rules for medication documentation

> Core idea: dosage math is patient-safety math. The unit setup is just as important as the arithmetic. If the units do not cancel into the unit the question asks for, the setup is not safe yet.

## 1. What to memorize first

| Must know | Equivalent | Why it matters |
|---|---:|---|
| Weight | 1 kg = 2.2 lb | Most weight-based medication orders use kg. |
| Weight | 1 lb = 16 oz | Infant weights may be recorded as pounds + ounces. |
| Metric mass | 1 g = 1000 mg | Common medication-strength conversion. |
| Metric mass | 1 mg = 1000 mcg | High-risk small-dose conversion. Do not mix up mg and mcg. |
| Volume | 1 L = 1000 mL | IV bags, intake/output, and fluid orders. |
| Household volume | 1 tsp = 5 mL | Oral-liquid medication doses. |
| Household volume | 1 Tbsp = 15 mL | 1 Tbsp = 3 tsp. |
| Household volume | 1 fl oz = 30 mL | Common quiz conversion for liquid medication. |
| Length | 1 in = 2.54 cm | Height conversions. |
| Length | 1 m = 100 cm; 1 km = 1000 m | Metric length conversions. |

## 2. Safe dimensional-analysis setup

Use this loop for every dosage problem:

1. Write the **given** over 1.
2. Choose an equivalent that contains the current unit.
3. Put the **unit you want to cancel** on the opposite side of the fraction.
4. Keep chaining equivalents until the only unit left is the requested answer unit.
5. Multiply across the top, multiply across the bottom, then divide.
6. Round only at the end unless the course/test specifically tells you to round earlier.

Example unit-cancel pattern:

```text
8 oz × 1 lb / 16 oz × 1 kg / 2.2 lb = kg
```

`oz` cancels, then `lb` cancels, leaving `kg`.

## 3. The layover method for no-direct-equivalent conversions

Video 1 teaches a useful mental model: if there is no direct conversion, find a **layover unit**.

- You cannot go straight from `oz` to `kg` with the common nursing equivalents.
- You can go `oz → lb → kg`.
- The middle unit, `lb`, is the layover.

Use the layover method whenever the start unit and end unit do not appear together in one equivalent.

| Start | Layover | End | Equivalents used |
|---|---|---|---|
| oz | lb | kg | 1 lb = 16 oz; 1 kg = 2.2 lb |
| tsp | mL | fl oz | 1 tsp = 5 mL; 1 fl oz = 30 mL |
| cm | m | km | 1 m = 100 cm; 1 km = 1000 m |

## 4. Video 1 worked example: infant 8 lb 8 oz ordered 15 mcg/kg

Problem from the video: a newborn weighs **8 lb 8 oz**. Medication C is ordered at **15 mcg/kg**. Find the dose in micrograms.

### Method A: convert each part to kg, then add

```text
8 lb × 1 kg / 2.2 lb = 3.6364 kg
8 oz × 1 lb / 16 oz × 1 kg / 2.2 lb = 0.2273 kg
3.6364 kg + 0.2273 kg = 3.8637 kg ≈ 3.86 kg
```

### Method B: convert all weight to ounces, then to kg

```text
8 lb × 16 oz / 1 lb = 128 oz
128 oz + 8 oz = 136 oz
136 oz × 1 lb / 16 oz × 1 kg / 2.2 lb = 3.86 kg
```

### Method C: convert ounces to pounds, then to kg

```text
8 oz × 1 lb / 16 oz = 0.5 lb
8 lb + 0.5 lb = 8.5 lb
8.5 lb × 1 kg / 2.2 lb = 3.86 kg
```

All three methods land at the same weight because the equivalents are oriented correctly.

Now calculate the medication dose:

```text
15 mcg/kg × 3.86 kg = 57.9 mcg per dose
```

Answer: **57.9 mcg per dose**.

## 5. Video 1 lesson: several paths can be correct

When a problem has three or more units, you are not locked into one path. You can:

- convert each component to the final unit and add,
- convert all components into a common unit first,
- or convert a leftover unit into the main unit, then convert once.

The safety checks are:

- Do the units cancel cleanly?
- Did you use approved medical/nursing equivalents?
- Did you avoid rounding too early?
- Does the final unit match what the question asks for?

## 6. Video 2: 10 safe notation rules

These rules prevent medication-order confusion.

| # | Rule | Safe example | Unsafe / avoid |
|---:|---|---|---|
| 1 | Unit follows the amount. | `5 mg` | `mg 5` |
| 2 | Do not put a period after a unit abbreviation. | `5 mg` | `5 mg.` |
| 3 | Do not add `s` to make units plural. | `5 mg` | `5 mgs` |
| 4 | Put a space between number and unit. | `5 mg` | `5mg` |
| 5 | For 1000 or larger, use commas every third digit. | `10,000,000` | `10000000` |
| 6 | For metric fractional units, use decimals. | `0.5 mg` | fraction-style metric notation |
| 7 | Use a leading zero for values between 0 and 1. | `0.5 mg` | `.5 mg` |
| 8 | Omit unnecessary zeros. | `0.671 mg` | `0.6710 mg`; `05 mg` |
| 9 | Write micrograms as `mcg`, not the Greek mu symbol. | `50 mcg` | `50 μg` |
| 10 | Use `mL`, not `cc`, for milliliters. | `5 mL` | `5 cc` |

Unspoken safety rule from the video: **when in doubt, ask the writer.** Do not guess your way through a confusing order.

## 7. Common quiz-style conversions from Chapter 10

### 8 lb 4 oz to kg

```text
4 oz ÷ 16 = 0.25 lb
8 lb + 0.25 lb = 8.25 lb
8.25 lb ÷ 2.2 = 3.75 kg
```

Answer: **3.75 kg**.

### 4500 g newborn to pounds

```text
4500 g ÷ 1000 = 4.5 kg
4.5 kg × 2.2 = 9.9 lb
```

Answer: **9.9 lb**.

### 288 m + 400 cm to km

```text
400 cm ÷ 100 = 4 m
288 m + 4 m = 292 m
292 m ÷ 1000 = 0.292 km
```

Answer: **0.292 km**, or **0.3 km** if rounding to tenths.

### 6 ft 5 in to meters

```text
6 ft × 12 = 72 in
72 in + 5 in = 77 in
77 in × 2.54 cm/in = 195.58 cm
195.58 cm ÷ 100 = 1.9558 m
```

Answer: **1.96 m** if rounding to hundredths; **2.0 m** if rounding to tenths. If the course key expects **1.9 m**, follow the course key for that quiz but know the standard rounding issue.

## 8. Oral-liquid dose conversions

### 125 mg ordered; supply 62.5 mg/5 mL; convert to teaspoons

```text
125 mg ÷ 62.5 mg = 2 supply-units
2 × 5 mL = 10 mL
10 mL ÷ 5 mL/tsp = 2 tsp
```

Answer: **2 tsp**.

### 0.6 g ordered; supply 100 mg/5 mL; convert to fluid ounces

```text
0.6 g × 1000 mg/g = 600 mg
600 mg ÷ 100 mg = 6 supply-units
6 × 5 mL = 30 mL
30 mL ÷ 30 mL/fl oz = 1 fl oz
```

Answer: **1 fl oz**.

## 9. IV time and infused-volume items

### 1 L at 50 mL/hr started 6:30 AM; when is the next bag due?

```text
1 L = 1000 mL
1000 mL ÷ 50 mL/hr = 20 hr
6:30 AM + 20 hr = 2:30 AM next day
```

Answer: **2:30 AM next day**.

### 1000 mL at 50 mL/hr started 5 AM; when is the next bag due?

```text
1000 mL ÷ 50 mL/hr = 20 hr
5:00 AM + 20 hr = 1:00 AM next day
```

Answer: **1:00 AM next day**.

### How much infused?

Use:

```text
infused = starting volume - amount left
```

- 1000 mL bag with 75 mL left: `1000 - 75 = 925 mL` infused.
- 1000 mL bag with 300 mL left: `1000 - 300 = 700 mL` infused.

## 10. Rounding and notation traps

- Do not round intermediate values too early in multi-step conversions.
- Always include a leading zero: write `0.5 mg`, not `.5 mg`.
- Never add a trailing zero after a decimal: write `5 mg`, not `5.0 mg`; write `0.5 mg`, not `0.50 mg` unless a very specific measurement format requires it.
- Use `mcg`, not `μg`.
- Use `mL`, not `cc`.
- Keep a space between the number and the unit: `30 mL`, not `30mL`.
- If the final answer unit is not the requested unit, the problem is not finished.

## 11. Active recall practice

Try these without looking first.

1. A baby weighs 7 lb 12 oz. Convert to kg.  
2. A medication order is 12 mcg/kg and the patient weighs 3.5 kg. How many mcg?  
3. Convert 0.75 mg to mcg.  
4. Convert 2500 mcg to mg.  
5. Convert 45 mL to tablespoons.  
6. Convert 2 fl oz to mL.  
7. A 1000 mL IV is running at 125 mL/hr. How long will it run?  
8. A 1000 mL IV has 180 mL left. How much infused?  
9. Which is safer: `.25 mg` or `0.25 mg`?  
10. Which is safer: `5 cc` or `5 mL`?

## 12. Quick answers

1. `12 oz ÷ 16 = 0.75 lb`; `7.75 lb ÷ 2.2 = 3.52 kg`.
2. `12 mcg/kg × 3.5 kg = 42 mcg`.
3. `0.75 mg × 1000 = 750 mcg`.
4. `2500 mcg ÷ 1000 = 2.5 mg`.
5. `45 mL ÷ 15 = 3 Tbsp`.
6. `2 × 30 = 60 mL`.
7. `1000 ÷ 125 = 8 hr`.
8. `1000 - 180 = 820 mL`.
9. `0.25 mg` because it has a leading zero.
10. `5 mL` because `cc` can be mistaken for zeros.

## 13. What to drill first before a quiz

1. Memorize the core equivalent table.
2. Practice lb + oz infant weights until the layover method feels automatic.
3. Practice metric mass conversions: g ↔ mg ↔ mcg.
4. Practice IV bag finish-time questions.
5. Recite the notation safety rules, especially leading zero, no trailing zero, `mcg`, and `mL`.
