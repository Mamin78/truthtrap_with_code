# TruthTrap Dataset

## Overview

TruthTrap is a bilingual (English-Farsi) evaluation dataset designed to study how Large Language Models (LLMs) respond to true but strategically persuasive content that can derail a model's reasoning. Unlike many existing benchmarks that focus on false or fabricated information, TruthTrap specifically examines how factually correct but irrelevant or misleading information affects LLM performance on information-seeking questions (ISQs).

This dataset consists of 1,000 curated items in each language, covering 10 diverse categories related to Iran. Each question is paired with both a correct explanation (supporting the right answer) and a persuasive yet misleading true hint (potentially derailing the model's reasoning).

## Dataset Structure

Each item in the dataset contains the following components:

| Field | Description |
|-------|-------------|
| Question | An information-seeking question in both English and Farsi |
| Explanation | A factually correct statement supporting the right answer |
| Persuasive Hint | A factually correct but potentially misleading statement |
| Answer Options | Four multiple-choice options (one correct, three distractors) |
| Category | One of 10 main categories (Arts & Literature, Education, etc.) |
| Subcategory | One of 3 subcategories within each main category |
| Question Type | Classification of the nature of information sought (Date/Time, Person, Location, etc.) |
| Target Type | Whether the hint undermines the correct answer generally or reinforces a specific incorrect choice |
| Wikipedia Source | Link to relevant Wikipedia page(s) where facts were sourced |

## Categories

The dataset covers 10 major categories, each with 100 questions:

1. Arts & Literature
2. Education
3. Entertainment
4. Food
5. Geography
6. History
7. Holidays & Leisure
8. Religion
9. Science & Technology
10. Sports

## Question Types

Questions are classified based on the information they seek:

| Question Type | Count |
|--------------|-------|
| Date or Time | 198 |
| Location | 178 |
| Number | 165 |
| Person | 151 |
| Other proper and common nouns | 109 |
| Group or Organization | 105 |
| Other | 42 |
| Event | 27 |
| Artwork | 25 |

## License

This dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License. You are free to share and adapt the dataset, provided appropriate credit is given.

For more details, see the LICENSE file.
