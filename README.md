# Developing skills for behavioral experiments in psycholinguistics (SoSe 2025)

This project was developed under the academic supervision of Dr. Morwenna Hoeks (she/her), affiliated with the Institute of Cognitive Science at the University of Osnabrück. Her office is located at Wachsbleiche 27, Room 50/102. For academic correspondence or inquiries related to this experiment, she can be contacted via email at morwenna.hoeks@uni-osnabrueck.de.

This project implements a 2×2 within-item factorial behavioral experiment using the PCIbex platform, designed to investigate how participants evaluate the congruence between a visually presented image and a descriptive sentence containing a gradable adjective. The experiment specifically examines the interaction between adjective semantics (lexical content) and visual salience (high vs. low perceptual prominence), using judgments elicited via binary (yes/no) responses.

The experimental design is grounded in the theory of context-dependent interpretation of gradable adjectives, in particular the role of comparison classes in scalar semantics. Gradable adjectives (e.g., tall, deep, clean) refer to degrees along a scale and acquire their interpretive thresholds through contextual anchoring. For example, a statement such as "The pool is deep" may be evaluated differently depending on whether the comparison is made with children’s pools or Olympic diving pools.

The experiment is inspired by and aims to partially replicate the findings of:

Weicker, M. & Schulz, P. (year). Children and adults privilege linguistic over visual information when creating comparison classes for prenominal gradable adjectives. Goethe University Frankfurt.

Each item (e.g., deep, blank, numb) appears in four conditions combining:

Two levels of linguistic context (Sentence Type A vs. Sentence Type B)

Two levels of visual salience (High vs. Low image versions)

Thus, the design results in 128 unique trials (32 adjective items × 4 conditions), fully randomized per participant with counterbalancing considerations. The final goal is to evaluate how visual cues and linguistic cues interact in shaping semantic judgments under controlled variation of contextual information.

# Scalar Judgments Experiment on Gradable Adjectives

This repository contains the implementation of a **2×2 within-item factorial behavioral experiment** developed in [PCIbex](https://github.com/addrummond/ibex/blob/master/docs/penncontroller.md). The study investigates how participants judge the congruence between sentences and images involving **gradable adjectives**, focusing on the interplay between **sentence context** and **visual salience**.

## 🔍 Research Background

Gradable adjectives such as _tall_, _deep_, _clean_, or _transparent_ are interpreted relative to **degrees** on a conceptual scale. Their interpretation depends on contextual information, specifically the **comparison class** that is implicitly or explicitly evoked. For instance:

> _"Jonathan is tall."_  
> This is only interpretable with respect to a comparison class: _Is Jonathan tall for a toddler? For a basketball player?_

Our experiment builds upon theoretical and experimental work in this area, including:

- **Weicker, M. & Schulz, P.**: _Children and adults privilege linguistic over visual information when creating comparison classes for prenominal gradable adjectives_.

## 🎯 Goals

This experiment aims to:
- Explore whether participants privilege **linguistic** or **visual** cues when evaluating scalar properties.
- Examine **context-sensitivity** of scalar predicates under visual variation.
- Partially replicate semantic judgments observed in previous child and adult studies on **comparison class selection**.

## 🧪 Experimental Design

- **Design**: 2×2 within-item factorial
  - **Factor 1**: Sentence Type (Context A vs. Context B)
  - **Factor 2**: Image Salience (High vs. Low)
- **Stimuli**: 32 gradable adjective items × 4 conditions = 128 total trials
- **Response mode**: Yes/No judgment on sentence-image congruency
- **Randomization**: Full randomization per participant, with no repetition of image-context pairs
- **Deployment**: PCIbex (PennController extension of IBEX)
- 
## 🛠️ Technologies

- JavaScript (PennController syntax)
- PCIbex (Browser-based experimental framework)
- HTML/CSS for UI
- Optional: R or Python for data analysis (not included in this repo)

## 👩‍🔬 How to Run

1. Clone the repository.
2. Upload to your PCIbex account.
3. Make sure all image files are hosted and paths are correct.
4. Launch and test in different browsers for consistency.

## 📜 License

This project is released under the [MIT License](LICENSE).

## 📬 Contact

For academic inquiries or collaboration, contact:

- Martín Enrique Iribarren (Universität Osnabrück)
