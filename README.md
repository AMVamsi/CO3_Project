## 🔬 Project Overview

This project presents a bio-inspired optimization system for **personalized Type 2 diabetes management**, integrating **insulin dosage**, **carbohydrate intake**, and **exercise scheduling** into one intelligent decision making framework.

We combine a simplified **glucose-insulin physiological model** with a two stage optimization pipeline:
- An **initial grid search** to explore feasible patterns,
- Followed by a **Genetic Algorithm (GA)** to fine-tune daily schedules for glucose control.

The system is enhanced by a **hybrid Mini-Bergman model** for improved physiological realism. Personalized virtual patient avatars were used to simulate daily routines, where the GA successfully maintained glucose levels within ±20 mg/dL of the target range **82% of the time**, while promoting lifestyle flexibility.

Compared to brute force grid search, our GA approach:
- ✅ Reduced computation time by **73%**
- ✅ Preserved diversity in schedules
- ✅ Maintained safe glucose thresholds

This highlights the promise of **evolutionary algorithms** in advancing smarter, adaptive, and personalized diabetes care.
