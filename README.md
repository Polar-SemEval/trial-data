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
- ben (Bengali)
- deu (German)
- eng (English)
- spa (Spanish)
- fas (Persian)
- hau (Hausa)
- hin (Hindi)
- ita (Italian)
- mya (Myanmar)
- nep (Nepali)
- rus (Russian)
- tel (Telugu)
- tur (Turkish)
- urd (Urdu)
- zho (Chinese)

## Participation

Participants may participate in all three subtasks or any one or two.

## Dataset Schema

The CSV file contains the following columns:

| Column | Description | Subtask |
|--------|-------------|------|
| `Text` | The original text sample | - |
| `Lang` | Language code | - |
| `ID` | Unique identifier for each text sample | - |
| `Polarization` | Boolean indicating if content is polarizing (TRUE/FALSE) | **Subtask 1** |
| `Political` | Binary flag (0/1) for political polarization target | **Subtask 2** |
| `Racial/Ethnic` | Binary flag (0/1) for racial/ethnic polarization target | **Subtask 2** |
| `Religious` | Binary flag (0/1) for religious polarization target | **Subtask 2** |
| `Gender/Sexual` | Binary flag (0/1) for gender/sexual polarization target | **Subtask 2** |
| `Other` | Binary flag (0/1) for other polarization targets | **Subtask 2** |
| `Vilification` | Binary flag (0/1) for vilification expression | **Subtask 3** |
| `Dehumanization` | Binary flag (0/1) for dehumanization expression | **Subtask 3** |
| `Extreme Language` | Binary flag (0/1) for extreme language expression | **Subtask 3** |
| `Lack of Empathy` | Binary flag (0/1) for lack of empathy expression | **Subtask 3** |
| `Stereotype` | Binary flag (0/1) for stereotyping expression | **Subtask 3** |
| `Invalidation` | Binary flag (0/1) for invalidation expression | **Subtask 3** |
