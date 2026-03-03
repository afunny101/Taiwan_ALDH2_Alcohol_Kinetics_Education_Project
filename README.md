# Taiwan Adult Alcohol Metabolism and ALDH2 Polymorphism Study

## Abstract
Alcohol metabolism in humans involves a two-step enzymatic pathway:
ethanol is converted to acetaldehyde, and acetaldehyde is further oxidized
to acetate. The mitochondrial enzyme ALDH2 plays a critical role in
acetaldehyde detoxification. 

In East Asian populations, including Taiwan, ALDH2 polymorphism is common.
The mutant allele reduces enzymatic activity, leading to acetaldehyde
accumulation and alcohol flushing response.

This project simulates alcohol metabolism kinetics in Taiwanese adults
with different ALDH2 genotypes and investigates reaction-order behavior
under varying substrate concentrations. An additional educational
component evaluates high school students’ ability to classify zero-order
and first-order reaction kinetics.

---

## Biological Background

Alcohol metabolism pathway:

Ethanol --(ADH)--> Acetaldehyde --(ALDH2)--> Acetate

ALDH2 polymorphism significantly affects acetaldehyde clearance rate.

Genotype groups:
- Normal (functional ALDH2)
- Mutant (reduced ALDH2 activity)

Reduced enzyme activity may lead to:
- Slower acetaldehyde clearance
- Increased toxicity risk
- Alcohol flushing syndrome

---

## Research Objectives

1. To simulate metabolic rate differences between ALDH2 genotypes.
2. To evaluate whether alcohol metabolism exhibits:
   - First-order kinetics at low concentration
   - Zero-order kinetics at high concentration (enzyme saturation)
3. To integrate biochemical kinetics with secondary-level chemical education.

---

## Methods

### Dataset
- Simulated adult population (n = 100)
- Age range: 20–65 years
- Two genotype groups (normal vs mutant)
- Initial alcohol concentration: 10–80 units

### Kinetic Assumptions
- Low concentration: Rate proportional to concentration (first-order)
- High concentration: Enzyme saturation, constant rate (zero-order)

### Educational Component
- 10 high school student groups
- Classification of reaction order using graphical interpretation

---

## Results (Simulated)

- High concentration region demonstrated near-constant metabolic rate.
- Mutant genotype group showed significantly reduced metabolic rate.
- Approximately 70% of student groups correctly identified reaction order.

---

## Scientific Significance

This project demonstrates:

- The impact of genetic polymorphism on enzyme kinetics
- The transition from first-order to zero-order reaction behavior
- The interdisciplinary integration of biochemistry, kinetics, and education

The model provides a simplified framework for understanding
enzyme saturation and genetic variability in alcohol metabolism.

---

## Tools and Environment

- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab
- GitHub

---

## Future Directions

- Fit Michaelis-Menten model to simulated data
- Introduce time-dependent kinetic modeling
- Apply logistic regression to predict genotype classification
- Incorporate real-world epidemiological data
