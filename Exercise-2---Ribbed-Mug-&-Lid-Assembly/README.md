# Excersice 2: Ribbed Ergonomic Mug & Lid Assembly

![Ribbed Mug Render](./images/render-1.jpg)

Welcome to **Exercise 2** of the CAD Practice Series!

In this challenge, you will model an ergonomic plastic mug feasturing a corrugated external grip, an extruded handle, and a two-piece press-fit lid mechansim with a rotating closure insert.

---

## 🎯 Skill Check & Core Concepts
This exercise builds on primary modeling fundamentals while introducing pattern features and assembly fitments:
* **Linear & Patterned Geometry:** Generating consistent corrugated body rings along a tapered revolve profile.
* **Complex Handle Geometry:** Extrude a complex handle profile featuring multi-radius tangent arcs ($R10.00\text{ mm}$ and $R22.00\text{ mm}$).
* **Multi-Part Fit:** Creating matching clearance tolerances on the $\varnothing 74.00\text{ m}$ lid lip to snap securely into the top rim.
* **Sectional Wall Thickness:** Maintaining uniform $1.50\text{ mm}$ wall thickness across complex geometry using revolve cut feature.

---

## 📐 Blueprint & Technical Drawings

Review the detailed blueprint below before starting your model. Pay specific attention to **`SECTION A-A`** for the rib profile and handle mounting angles, and **`SECTION B-B` && `SECTION C-C`** for the internal lip dimensions on the lid.

![Technical Drawing Sheet](./files/Drawing_sheet.pdf)

### Key Specificaitons:
* **Overall Height:** $85.00\text{ mm}$
* **Top Rim Outside Diameter:** $\varnothing 73.00\text{ mm}$
* **Base Outside Diameter:** $\varnothing 60.00\text{ mm}$
* **Lid Outer Diameter:** $\varnothing 74.00\text{ mm}$
* **Wall Thickness:** $1.50\text{ mm}$ nominal
* **Handle Attachment Angles:** $135^\circ$ to mating face / $15^\circ$ bottom alignment angle.
 ---

* ## 💡 Pro Tips for Modeling
1. **Body First, Ribs Second:** Revolve the main tapered body profile before applying the corrugated ring pattern to avoid complicated geometry and errors.
2. **Extrude Handle Alignment:** Sketch the side profile of the plane of the ***Body*** and extrude using **Mid Plane blind** end condition to merge smoothly into the cup wall.
3. **Lid Clearance:** Use **``SECTION C-C``** on the drawing sheet (Scale $2:1$) to model the internal snap-ridge detail ($0.50\text{ mm}$ offset) for the rotating top insert.
