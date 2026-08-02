## 📱 Thunkable MVP Plan

### Goal

Build the **first working SoilRevive prototype** in Thunkable.

---

## Screen 1 — Home

### Components Needed

#### Label

* Text: **🌱 SoilRevive**

#### Dropdown

**Items**

* Curry Patta
* Tulsi
* Money Plant
* Other

#### Radio Buttons or Buttons

**Location**

* Indoor
* Outdoor

#### Dropdown

**Pot Size**

* Small
* Medium
* Large

#### Button

* Text: **Check Plant Health**

---

## Screen 2 — Symptom Check

### Checkboxes

* Yellow Leaves
* Drooping Leaves
* Soil Very Wet
* Soil Very Dry
* Fungus Visible

### Button

* **Get Diagnosis**

---

## Screen 3 — Result

### Labels

**Possible Cause**

* Overwatering
* Underwatering
* Poor Drainage
* Nutrient Deficiency

**Soil Health Score**

* Example: **43/100**

**Quick Action**

* Stop watering
* Improve airflow
* Remove fungal growth

### Buttons

* **Check Again**
* **Save Result**

---

## Phase 1 Logic

### If

* Yellow Leaves = YES
* Soil Very Wet = YES
* Fungus Visible = YES

### Then

* Diagnosis = **Overwatering**
* Score = **43**
* Action = **Stop watering for 2–3 days**

---

## Minimum Working Prototype

The app is considered successful when a user can:

1. Select a plant
2. Tick symptoms
3. Press **Get Diagnosis**
4. Receive:

   * A probable cause
   * A Soil Health Score
   * A quick remedy

This is the **SoilRevive Phase 1 MVP**.
