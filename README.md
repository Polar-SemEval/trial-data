# POLAR-SemEval 2026 Trial Dataset

This is a trial dataset sample for POLAR-SemEval 2026.

## Shared Task Overview

This shared task includes 3 subtasks:

- **Subtask 1**: Detect whether a text is polarized
- **Subtask 2**: Classify the target of polarization - includes Gender/Sexual, Political, Religious, Racial/Ethnic, and Other categories
- **Subtask 3**: Identify how polarization is expressed - includes Vilification, Extreme Language, Stereotype, Invalidation, Lack of Empathy, and Dehumanization

## Languages

This dataset includes the following languages:
- amh (Amharic)
- ara (Arabic)
- deu (German)
- eng (English)
- urd (Urdu)
- spa (Spanish)
- hau (Hausa)
- fas (Persian)
- tur (Turkish)
- zho (Chinese)
- ita (Italian)
- nep (Nepali)
- rus (Russian)

## Participation

Participants are welcome to participate in task 1, 2 or 3 or part of it.

## Dataset Schema

The CSV file contains the following columns:

| Column | Description | Task |
|--------|-------------|------|
| `Text` | The original text sample | - |
| `Lang` | Language code | - |
| `Polarization` | Boolean indicating if content is polarizing (TRUE/FALSE) | **Task 1** |
| `Gender/Sexual` | Binary flag (0/1) for gender/sexual polarization target | **Task 2** |
| `Political` | Binary flag (0/1) for political polarization target | **Task 2** |
| `Religious` | Binary flag (0/1) for religious polarization target | **Task 2** |
| `Racial/Ethnic` | Binary flag (0/1) for racial/ethnic polarization target | **Task 2** |
| `Other` | Binary flag (0/1) for other polarization targets | **Task 2** |
| `Vilification` | Binary flag (0/1) for vilification expression | **Task 3** |
| `Extreme Language` | Binary flag (0/1) for extreme language expression | **Task 3** |
| `Stereotype` | Binary flag (0/1) for stereotyping expression | **Task 3** |
| `Invalidation` | Binary flag (0/1) for invalidation expression | **Task 3** |
| `Lack of Empathy` | Binary flag (0/1) for lack of empathy expression | **Task 3** |
| `Dehumanization` | Binary flag (0/1) for dehumanization expression | **Task 3** |
| `ID` | Unique identifier for each text sample | - |