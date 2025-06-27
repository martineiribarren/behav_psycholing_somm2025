# Developing skills for behavioral experiments in psycholinguistics (SoSe 2025)

# Scalar Judgments Experiment on Gradable Adjectives 

This repository contains the implementation of a 2×2 within-item factorial behavioral experiment developed in PCIbex. The study investigates how participants judge the congruence between visually presented images and descriptive sentences containing gradable adjectives, focusing on the interplay between sentence context and visual salience.

## Research Background

Gradable adjectives such as tall, deep, clean, or transparent refer to degrees on a conceptual scale. Their interpretation depends on contextual anchoring, especially the comparison class involved. For instance:

> "Jonathan is tall"  
> This can only be interpreted meaningfully relative to a comparison class: Is Jonathan tall for a toddler? For a basketball player?

The experiment is grounded in the theory of context-sensitive scalar semantics, particularly how gradable adjectives acquire thresholds for interpretation. It draws inspiration from:

- Weicker, M., & Schulz, P. (2024). Children and adults privilege linguistic over visual information when creating comparison classes for prenominal gradable adjectives. Glossa a journal of general linguistics, 9(1). https://doi.org/10.16995/glossa.9912



## Research Objectives

- Investigate whether participants privilege linguistic or visual information when interpreting scalar predicates.  
- Explore how contextual variation in both language and perception modulates scalar judgments.  
- Partially replicate earlier findings on comparison class selection in adult and child populations.

## Experimental Design

- **Design:** 2×2 within-item factorial design  
- **Factor 1:** Sentence Type (Context A vs. Context B)  
- **Factor 2:** Image Salience (High vs. Low)  
- **Stimuli:** 32 adjective items × 4 combinations = 128 unique trials  
- **Response Task:** Participants make yes/no judgments on whether the sentence matches the image.  
- **Randomization:** Each participant receives a unique random order of all 128 trials (no repetitions).  
- **Platform:** PCIbex (PennController extension for Ibex)  

## Technologies Used

- PCIbex: browser-based experiment delivery (PennController)  
- JavaScript (PennController syntax)  
- HTML/CSS for layout/styling  
- Data export compatible with R/Python for analysis (scripts not included in this repo)  

## How to Run the Experiment

1. Clone or download this repository.  
2. Upload all files (code and images) to your PCIbex Farm account.  
3. Ensure all image paths are correct and assets are properly hosted.  
4. Test on multiple browsers for visual and functional consistency.  
5. Optionally implement Latin Square logic before deployment, depending on participant count.

## Supervision

This project was developed under the academic supervision of:  

**Dr. Morwenna Hoeks** (she/her)  
Institute of Cognitive Science  
University of Osnabrück  

## 📬 Contact

For questions, collaboration, or clarifications:  

**Martín Enrique Iribarren**  
Cognitive Science (B.Sc.)  
University of Osnabrück  
Contact via university channels or GitHub  

## License

Distributed under the terms of the MIT License.
