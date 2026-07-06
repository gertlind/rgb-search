# Filament RGBSearch

## Analyzes a picture and calculates the average HEX RGB color

### An AI answer on how it works

CIEDE2000 (often written as Δ E₀₀) is an internationally recognized mathematical formula used to measure the perceptual difference between two colors. It takes two color coordinates (typically in the standard CIELAB space) and calculates a single number representing how different those colors look to the human eye.
Because the standard CIELAB color space is geometrically uneven—meaning the human eye is more sensitive to changes in certain colors (like grays or pastels) than others (like highly saturated blues)—older formulas could not reliably reflect human perception.

| ΔE | How the Eye Perceives the Difference |
| :----: | :----------------------------------: |
| < 1 | No visible difference |
| 1–2 | Barely perceptible |
| 2–5 | Small but noticeable difference |
| 5–10 | Clearly different, but still related |
| > 10 | Completely different color |

![target color](images/target_color.png)
