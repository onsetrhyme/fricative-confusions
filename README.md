# fricative-confusions
Similarity of confusions (Shepard's method) among English fricatives by EFL learners. Data from Lee (2023), Phonetics and Speech Sciences.

# Similarity of confusions (Shepard's method), 2022 data

These files contain the 2022 data reported in the following paper:

Lee, K. (2023). An analysis of English as a foreign language learners' perceptual confusions and phonemic awareness of English fricatives. *Phonetics and Speech Sciences, 15*(3), 37–44. https://doi.org/10.13064/KSSS.2023.15.3.037

If you use these data, please cite the paper above.

## Files

| File | Contents |
|---|---|
| `shepard_similarity_voiceless_2022.csv` | Similarity of confusions among the voiceless fricatives f, θ, s, sh, h |
| `shepard_similarity_voiced_2022.csv` | Similarity of confusions among the voiced fricatives v, ð, z |

## Data format

- Each file is a lower triangular similarity matrix computed with Shepard's method.
- Diagonal cells are 1. Cells above the diagonal are left empty.
- In the column headers, `th` stands for θ (voiceless file) or ð (voiced file). Row labels use the IPA symbols.
- Encoding: UTF-8 with BOM.

## License

The data in this repository are released under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. You are free to share and adapt the data for any purpose, provided that you give appropriate credit by citing the paper listed above.
