# Anxiety Test – Python Project  
**Psychology-Based CLI Tool using SCAT (Sinha’s Comprehensive Anxiety Test)**

## Overview  
This project assesses the level of anxiety in individuals using the standardized **Sinha’s Comprehensive Anxiety Test (SCAT)**. Through 90 structured psychological questions, it evaluates behavioral patterns and symptoms of anxiety. The CLI-based Python tool calculates and interprets scores using sex-based norms to deliver reliable results.

## Functional Highlights

### Core Assessment Logic
- `analyze_answers(answers)`: Calculates a preliminary anxiety score based on user responses  
- `final_score(score, sex)`: Interprets score according to male/female psychological norms defined by SCAT

### Question Handling
- Loads all 90 anxiety evaluation statements from `scat_questions.txt`  
- Captures user responses with strict validation for Yes/No formats  
- Provides real-time interaction via terminal interface  

### User Experience
- Prompts for essential identity fields (Name, Age, Sex, School)  
- Implements `pyfiglet` to enhance interface with stylized titles  
- Ensures clean, clear output showing both numeric score and anxiety level  

## Technical Implementation

### Module Structure
- `main.py`: Controls flow — gathers input, processes responses, and displays results  
- `analysis.py`: Contains core logic — calculates score and interprets it  
- `scat_questions.txt`: External file storing 90 SCAT-based questions  
- `pyfiglet`: Used for enhancing command-line visual output  

### Anxiety Level Criteria  
(Adjusted using `final_score(anxiety_score, sex)`):

#### For Males:
- 43+ → **Extremely High Anxiety**  
- 28–42 → **High Anxiety**  
- 17–27 → **Normal Anxiety Level**  
- 1–16 → **Low Anxiety**

#### For Females:
- 42+ → **Extremely High Anxiety**  
- 27–41 → **High Anxiety**  
- 16–26 → **Normal Anxiety Level**  
- 0–15 → **Extremely Low Anxiety**

## Project Documentation  
📄 [**Download Full Project Report (PDF)**](Anxiety_test.pdf)

Includes complete documentation of:
- Function descriptions and input/output  
- Explanation of scoring and logic flow  
- Sample questions and interface behavior  
- Final anxiety level interpretation guide  

## Author  
**Rashi Raj**  
B.Tech Computer Science (AIML)  
University of Petroleum and Energy Studies  
[GitHub Profile](https://github.com/rasshhe)
