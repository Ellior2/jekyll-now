---
layout: post
title: BCA results
---

11/23/2016

### Today we completed the protein assay!

We followed the protocol I have written up [here](https://github.com/Ellior2/Ellior2.github.io/blob/master/_posts/2016-11-22-BCA-assay.md)

*For Sample #56 we made a mistake and only have two replicates instead of three.

After I got the resulting absorbances from the Spectrophotometer plate reader I calculated the protein concentrations and determined how much of each sample I will need for the digestion protocol.

[graph](https://github.com/Ellior2/Ellior2.github.io/blob/master/images/ProteinAssay.pdf)

1) Obtained measured wavelengths at 562nm for each of the standards and replicates from the spectrophotometer. I averaged the three replicates for each.

2) Subtracted the average blank measured absorbance at wavelength 562nm from the averages of the standards and unknown samples. This is the Blank-corrected Absorbance.

3) I created a scatter plot in excel for the standards by plotting the BSA concentration (ug/ul) on the Y-axis and the blank-corrected absorbances on the X-axis. I added a polynomial trendline and displayed the equation and r-squared value. I did those so I could easily plug in the X (absorbance) and calculate the Y (protein concentration).

4) Because I diluted with 1:2 with 50 mM NH4HCO3 in 6M Urea, I multiplied the protein concentrations I calculated by 3.

5) Then I calculated how much volume is needed to have 100ug of protein in each of my samples. Because we want to start the Mini-Trypsin digestion with 100ul, I figured out how many microliters of 50mM NH4HCO3 in 6M urea I needed to add.

[see nice table](https://github.com/Ellior2/Ellior2.github.io/blob/master/_posts/2016-11-23-BCA-assay-results.md)

| Well | Contents  | Rep | Abs. at 562nm | Avg. Abs. | Blank-corr. Abs. | BSA conc. (ug/ul) | Corr. for dilution of NH4HCO3 | ul of sample required for 100ug | ul to add of NH4HCO3 |
|------|-----------|-----|---------------|-----------|------------------|-------------------|-------------------------------|---------------------------------|----------------------|
| A1   | Vial B    | 1   | 0.986         | 0.981     | 0.881            | 1.500             | N/A                           | N/A                             | N/A                  |
| A2   | Vial B    | 2   | 0.991         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| A3   | Vial B    | 3   | 0.966         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| A4   | Vial C    | 1   | 0.717         | 0.705     | 0.605            | 1.000             | N/A                           | N/A                             | N/A                  |
| A5   | Vial C    | 2   | 0.72          | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| A6   | Vial C    | 3   | 0.679         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| A7   | Vial D    | 1   | 0.554         | 0.563     | 0.463            | 0.750             | N/A                           | N/A                             | N/A                  |
| A8   | Vial D    | 2   | 0.577         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| A9   | Vial D    | 3   | 0.558         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| A10  | Vial E    | 1   | 0.421         | 0.434     | 0.333            | 0.500             | N/A                           | N/A                             | N/A                  |
| A11  | Vial E    | 2   | 0.431         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| A12  | Vial E    | 3   | 0.449         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| B1   | Vial F    | 1   | 0.276         | 0.268     | 0.168            | 0.250             | N/A                           | N/A                             | N/A                  |
| B2   | Vial F    | 2   | 0.267         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| B3   | Vial F    | 3   | 0.262         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| B4   | Vial G    | 1   | 0.177         | 0.177     | 0.077            | 0.125             | N/A                           | N/A                             | N/A                  |
| B5   | Vial G    | 2   | 0.176         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| B6   | Vial G    | 3   | 0.179         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| B7   | Vial H    | 1   | 0.157         | 0.146     | 0.046            | 0.025             | N/A                           | N/A                             | N/A                  |
| B8   | Vial H    | 2   | 0.132         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| B9   | Vial H    | 3   | 0.15          | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| B10  | Vial I    | 1   | 0.1           | 0.100     | 0.000            | 0.000             | N/A                           | N/A                             | N/A                  |
| B11  | Vial I    | 2   | 0.1           | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| B12  | Vial I    | 3   | 0.101         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| C1   | Sample 1  | 1   | 0.838         | 0.817     | 0.717            | 1.195             | 3.584                         | 27.9                            | 72.1                 |
| C2   | Sample 1  | 2   | 0.822         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| C3   | Sample 1  | 3   | 0.791         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| C4   | Sample 3  | 1   | 0.561         | 0.572     | 0.471            | 0.755             | 2.266                         | 44.1                            | 55.9                 |
| C5   | Sample 3  | 2   | 0.572         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| C6   | Sample 3  | 3   | 0.582         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| C7   | Sample 4  | 1   | 0.719         | 0.743     | 0.642            | 1.059             | 3.176                         | 31.5                            | 68.5                 |
| C8   | Sample 4  | 2   | 0.753         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| C9   | Sample 4  | 3   | 0.756         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| C10  | Sample 8  | 1   | 0.964         | 0.998     | 0.898            | 1.536             | 4.608                         | 21.7                            | 78.3                 |
| C11  | Sample 8  | 2   | 0.977         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| C12  | Sample 8  | 3   | 1.053         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| D1   | Sample 11 | 1   | 0.619         | 0.590     | 0.490            | 0.787             | 2.361                         | 42.3                            | 57.7                 |
| D2   | Sample 11 | 2   | 0.581         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| D3   | Sample 11 | 3   | 0.57          | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| D4   | Sample 12 | 1   | 0.911         | 0.957     | 0.856            | 1.457             | 4.371                         | 22.9                            | 77.1                 |
| D5   | Sample 12 | 2   | 0.989         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| D6   | Sample 12 | 3   | 0.97          | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| D7   | Sample 16 | 1   | 0.799         | 0.790     | 0.690            | 1.146             | 3.437                         | 29.1                            | 70.9                 |
| D8   | Sample 16 | 2   | 0.784         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| D9   | Sample 16 | 3   | 0.788         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| D10  | Sample 19 | 1   | 0.848         | 0.907     | 0.806            | 1.362             | 4.086                         | 24.5                            | 75.5                 |
| D11  | Sample 19 | 2   | 0.892         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| D12  | Sample 19 | 3   | 0.98          | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| E1   | Sample 20 | 1   | 0.747         | 0.750     | 0.650            | 1.073             | 3.218                         | 31.1                            | 68.9                 |
| E2   | Sample 20 | 2   | 0.771         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| E3   | Sample 20 | 3   | 0.733         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| E4   | Sample 24 | 1   | 0.66          | 0.662     | 0.562            | 0.914             | 2.742                         | 36.5                            | 63.5                 |
| E5   | Sample 24 | 2   | 0.681         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| E6   | Sample 24 | 3   | 0.645         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| E7   | Sample 27 | 1   | 0.785         | 0.785     | 0.684            | 1.135             | 3.406                         | 29.4                            | 70.6                 |
| E8   | Sample 27 | 2   | 0.766         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| E9   | Sample 27 | 3   | 0.803         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| E10  | Sample 28 | 1   | 0.807         | 0.844     | 0.744            | 1.245             | 3.736                         | 26.8                            | 73.2                 |
| E11  | Sample 28 | 2   | 0.856         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| E12  | Sample 28 | 3   | 0.87          | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| F1   | Sample 32 | 1   | 0.827         | 0.829     | 0.728            | 1.216             | 3.649                         | 27.4                            | 72.6                 |
| F2   | Sample 32 | 2   | 0.797         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| F3   | Sample 32 | 3   | 0.862         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| F4   | Sample 35 | 1   | 0.617         | 0.642     | 0.541            | 0.878             | 2.634                         | 38.0                            | 62.0                 |
| F5   | Sample 35 | 2   | 0.651         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| F6   | Sample 35 | 3   | 0.657         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| F7   | Sample 36 | 1   | 0.974         | 0.979     | 0.879            | 1.500             | 4.501                         | 22.2                            | 77.8                 |
| F8   | Sample 36 | 2   | 0.954         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| F9   | Sample 36 | 3   | 1.01          | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| F10  | Sample 40 | 1   | 0.93          | 0.999     | 0.898            | 1.537             | 4.612                         | 21.7                            | 78.3                 |
| F11  | Sample 40 | 2   | 1.024         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| F12  | Sample 40 | 3   | 1.042         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| G1   | Sample 43 | 1   | 0.589         | 0.572     | 0.472            | 0.756             | 2.267                         | 44.1                            | 55.9                 |
| G2   | Sample 43 | 2   | 0.574         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| G3   | Sample 43 | 3   | 0.553         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| G4   | Sample 44 | 1   | 0.952         | 0.955     | 0.854            | 1.453             | 4.359                         | 22.9                            | 77.1                 |
| G5   | Sample 44 | 2   | 0.92          | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| G6   | Sample 44 | 3   | 0.992         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| G7   | Sample 48 | 1   | 0.948         | 0.957     | 0.857            | 1.458             | 4.374                         | 22.9                            | 77.1                 |
| G8   | Sample 48 | 2   | 0.956         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| G9   | Sample 48 | 3   | 0.968         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| G10  | Sample 51 | 1   | 0.789         | 0.802     | 0.701            | 1.166             | 3.499                         | 28.6                            | 71.4                 |
| G11  | Sample 51 | 2   | 0.779         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| G12  | Sample 51 | 3   | 0.837         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| H1   | Sample 52 | 1   | 0.902         | 0.889     | 0.789            | 1.329             | 3.986                         | 25.1                            | 74.9                 |
| H2   | Sample 52 | 2   | 0.893         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| H3   | Sample 52 | 3   | 0.872         | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| H4   | Sample 56 | 1   | 1.095         | 1.103     | 1.002            | 1.740             | 5.219                         | 19.2                            | 80.8                 |
| H5   | Sample 56 | 2   | 1.11          | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |
| H6   | Sample 56 | 3   | omit          | N/A       | N/A              | N/A               | N/A                           | N/A                             | N/A                  |