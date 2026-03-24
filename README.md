# Car Comparison Tool (India)

A simple comparison system designed to help Indian car buyers make better decisions using structured data.

---

## Problem
Car buyers often get confused between multiple options with similar pricing and features.

---

## Solution
This tool compares two cars based on:
- Price
- Mileage
- Features

And provides a simple, practical verdict.

---

## Features
- Compare two cars side-by-side
- Structured automobile dataset
- Easy-to-understand output

---

## How It Works
1. User selects two cars from dataset  
2. System compares:
   - Price  
   - Mileage  
   - Features  
3. Outputs a final recommendation  

---

## Example Output

Comparing:  
Hyundai Creta vs Kia Seltos  

Result:
- Price: Similar  
- Mileage: Creta slightly better  
- Features: Seltos offers more tech  

Final Verdict:  
Kia Seltos is better for features, Creta for balanced usage  

---

## How to Run

1. Install Python  
2. Run:
   python compare.py  

3. View comparison output in terminal  

---

## Sample Logic

```python
if car1_mileage > car2_mileage:
    print("Car 1 has better mileage")
else:
    print("Car 2 has better mileage")
