 Antimicrobial Resistance Surveillance Analysis 🧫💊

Exploratory and analytical study of antimicrobial resistance (AMR) patterns using anonymized institutional microbiology data.

This project investigates bacterial resistance behavior across antibiotics, organism groups, and clinically relevant pathogens to support antimicrobial stewardship and epidemiological surveillance.

---

## 📊 Project Scope

The analysis focuses on:

- resistance distribution across microorganisms
- Gram-positive vs Gram-negative resistance patterns
- antibiotic effectiveness ranking
- organism-specific resistance profiles
- probabilistic characterization of resistant organisms

All data are aggregated and anonymized to preserve institutional confidentiality.

---

## 🧪 Dataset

Institutional antimicrobial susceptibility dataset containing:

- bacterial organisms  
- antibiotic agents  
- resistance percentages  

No patient or institutional identifiers are included.

---

## 📈 Analyses Performed

### Resistance Distribution

- Boxplot of resistance percentages across microorganisms
- Comparison by Gram classification (Gram-positive vs Gram-negative)

---

### High-Resistance Organisms

- Top 10 microorganisms with highest resistance levels
- Ranking based on resistance prevalence

---

### High-Susceptibility Organisms

- Top 10 microorganisms with lowest resistance
- Identification of most treatable organisms

---

### Antibiotic Effectiveness

- Top 10 antibiotics with lowest effectiveness
- Resistance-based ranking of antimicrobial performance

---

### Resistant Organism Probability

Conditional probability estimation:

P(microorganism | resistant)

Identifies organisms most likely present among resistant isolates.

---

### Species-Specific Resistance Profiles

Detailed resistance profiles were generated for key pathogens:

- *Escherichia coli*
- *Klebsiella pneumoniae*
- *Staphylococcus aureus*

A reusable visualization function was developed to standardize antimicrobial resistance profile plots across organisms.

---

## 🛠️ Methods & Tools

- Python
- pandas
- numpy
- matplotlib / seaborn
- epidemiological AMR metrics
- conditional probability analysis
- reusable visualization functions
