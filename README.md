## Dataset Description

The repository uses three image datasets located in the `data#1`, `data#2`  and `data#3` folders:

### 📁 data#2 — Strawberry Detection Dataset
- Binary classification task:
  - **Class 1**: Images containing at least part of a **strawberry**
  - **Class 0**: Images of other **berries** (raspberries, blueberries, rose hips, etc.), **fruits** (apples, bananas, pomegranates, etc.), **figs**, and **mint**

### 📁 data#2 — Animal Classification Dataset
- Multi-class classification with 3 classes: **rabbits**, **cats**, and **dogs**
- 695 original images per class (AI-generated + open-source)
- Augmented to 2600 images per class → **9800 total images**

### 📁 data#3 — Multi-Animal Combination Dataset
This dataset was created for a multi-label classification task involving combinations of animals (rabbits, cats, dogs) on the same image.
- **90 original images** for each of the 7 possible class combinations (some manually created by combining animals in one image, e.g., adding a rabbit to a "dog and cat" photo)
- Includes AI-generated and open-source images
- **630 original images total** (90 × 7 combinations)
- **70 augmented images total** (10 per combination)
- Final dataset size: **700 images**
