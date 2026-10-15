# Results

_33 runs; void pre-rescale runs excluded._

## Seed-level dispersion

| language   | task             | condition   | level   | metric   |   mean |    sd |   n |   ci_lo |   ci_hi | flag     |
|:-----------|:-----------------|:------------|:--------|:---------|-------:|------:|----:|--------:|--------:|:---------|
| ind        | classifier_probe | BPE         | F1      | macro_f1 |  0.9   | 0.006 |   3 |   0.885 |   0.915 |          |
| ind        | classifier_probe | MORPHAUSTRO | F1      | macro_f1 |  0.903 | 0.003 |   3 |   0.896 |   0.91  |          |
| ind        | classifier_probe | SCRAMBLED   | F1      | macro_f1 |  0.896 | 0.002 |   3 |   0.891 |   0.902 |          |
| tgl        | mt_flores        | BPE         | F0      | chrf     | 10.435 | 2.265 |   3 |   4.809 |  16.061 |          |
| tgl        | mt_flores        | BPE         | F1      | chrf     |  9.287 | 2.367 |   3 |   3.408 |  15.166 |          |
| tgl        | mt_flores        | BPE         | F2      | chrf     |  7.482 | 1.577 |   3 |   3.565 |  11.399 |          |
| tgl        | mt_flores        | MORPHAUSTRO | F0      | chrf     | 11.348 | 2.18  |   3 |   5.933 |  16.763 |          |
| tgl        | mt_flores        | MORPHAUSTRO | F1      | chrf     | 10.478 | 2.527 |   3 |   4.2   |  16.755 |          |
| tgl        | mt_flores        | MORPHAUSTRO | F2      | chrf     | 10.928 | 1.34  |   3 |   7.599 |  14.257 |          |
| tgl        | mt_flores        | SCRAMBLED   | F1      | chrf     | 10.62  | 3.53  |   3 |   1.85  |  19.39  |          |
| tgl        | mt_flores        | SCRAMBLED   | F2      | chrf     | 10.243 | 2.56  |   3 |   3.885 |  16.602 |          |
| tgl        | mt_indomain      | BPE         | F0      | chrf     |  9.875 | 1.864 |   3 |   5.244 |  14.505 |          |
| tgl        | mt_indomain      | BPE         | F1      | chrf     |  8.787 | 2.115 |   3 |   3.532 |  14.042 |          |
| tgl        | mt_indomain      | BPE         | F2      | chrf     |  6.913 | 1.444 |   3 |   3.327 |  10.5   |          |
| tgl        | mt_indomain      | MORPHAUSTRO | F0      | chrf     | 11.116 | 1.894 |   3 |   6.412 |  15.821 |          |
| tgl        | mt_indomain      | MORPHAUSTRO | F1      | chrf     | 10.096 | 2.277 |   3 |   4.44  |  15.752 |          |
| tgl        | mt_indomain      | MORPHAUSTRO | F2      | chrf     | 10.89  | 0.789 |   3 |   8.931 |  12.85  |          |
| tgl        | mt_indomain      | SCRAMBLED   | F1      | chrf     | 10.393 | 2.997 |   3 |   2.947 |  17.838 |          |
| tgl        | mt_indomain      | SCRAMBLED   | F2      | chrf     | 10.276 | 2.132 |   3 |   4.98  |  15.571 |          |
| tgl        | ner              | BPE         | F0      | f1       |  0.646 | 0.029 |   3 |   0.573 |   0.718 |          |
| tgl        | ner              | BPE         | F1      | f1       |  0.646 | 0.026 |   3 |   0.582 |   0.71  |          |
| tgl        | ner              | BPE         | F2      | f1       |  0.649 | 0.012 |   3 |   0.62  |   0.677 |          |
| tgl        | ner              | MORPHAUSTRO | F0      | f1       |  0.648 | 0.017 |   3 |   0.606 |   0.69  |          |
| tgl        | ner              | MORPHAUSTRO | F1      | f1       |  0.665 | 0.012 |   3 |   0.635 |   0.695 |          |
| tgl        | ner              | MORPHAUSTRO | F2      | f1       |  0.667 | 0.015 |   3 |   0.63  |   0.705 |          |
| tgl        | ner              | SCRAMBLED   | F1      | f1       |  0.636 | 0.008 |   3 |   0.615 |   0.657 |          |
| tgl        | ner              | SCRAMBLED   | F2      | f1       |  0.662 | 0.004 |   3 |   0.651 |   0.672 |          |
| tgl        | voice_probe      | BPE         | F0      | macro_f1 |  0.883 | 0.021 |   3 |   0.832 |   0.935 |          |
| tgl        | voice_probe      | BPE         | F1      | macro_f1 |  0.93  | 0.01  |   3 |   0.904 |   0.955 |          |
| tgl        | voice_probe      | BPE         | F2      | macro_f1 |  0.931 | 0.02  |   3 |   0.881 |   0.981 |          |
| tgl        | voice_probe      | MORPHAUSTRO | F0      | macro_f1 |  1     | 0     |   3 |   1     |   1     | circular |
| tgl        | voice_probe      | MORPHAUSTRO | F1      | macro_f1 |  1     | 0     |   3 |   1     |   1     | circular |
| tgl        | voice_probe      | MORPHAUSTRO | F2      | macro_f1 |  0.998 | 0     |   3 |   0.998 |   0.998 | circular |
| tgl        | voice_probe      | SCRAMBLED   | F1      | macro_f1 |  0.931 | 0.014 |   3 |   0.895 |   0.967 |          |
| tgl        | voice_probe      | SCRAMBLED   | F2      | macro_f1 |  0.944 | 0.009 |   3 |   0.922 |   0.967 |          |

## Paired bootstrap, Holm-corrected

| language   | task             | contrast          | fertility_level   |   delta |   p_value |    n |   ci_lo |   ci_hi | circular   |   p_holm | reject   |
|:-----------|:-----------------|:------------------|:------------------|--------:|----------:|-----:|--------:|--------:|:-----------|---------:|:---------|
| ind        | classifier_probe | MORPHAUSTRO - BPE | F1                |  0.0031 |    0.2553 | 1200 | -0.0025 |  0.0086 | False      |   0.919  | False    |
| ind        | classifier_probe | SCRAMBLED - BPE   | F1                | -0.0036 |    0.1838 | 1200 | -0.0089 |  0.0014 | False      |   0.919  | False    |
| tgl        | mt_flores        | MORPHAUSTRO - BPE | F0                |  0.8442 |    0      |  500 |  0.6815 |  1.0106 | False      |   0      | True     |
| tgl        | mt_flores        | MORPHAUSTRO - BPE | F1                |  1.4883 |    0      |  500 |  1.291  |  1.6899 | False      |   0      | True     |
| tgl        | mt_flores        | SCRAMBLED - BPE   | F1                |  1.5429 |    0      |  500 |  1.366  |  1.7193 | False      |   0      | True     |
| tgl        | mt_flores        | MORPHAUSTRO - BPE | F2                |  3.3961 |    0      |  500 |  3.2126 |  3.58   | False      |   0      | True     |
| tgl        | mt_flores        | SCRAMBLED - BPE   | F2                |  2.7353 |    0      |  500 |  2.5399 |  2.9353 | False      |   0      | True     |
| tgl        | mt_indomain      | MORPHAUSTRO - BPE | F0                |  1.1679 |    0      |  300 |  0.9076 |  1.4348 | False      |   0      | True     |
| tgl        | mt_indomain      | MORPHAUSTRO - BPE | F1                |  1.6313 |    0      |  300 |  1.3526 |  1.9199 | False      |   0      | True     |
| tgl        | mt_indomain      | SCRAMBLED - BPE   | F1                |  1.8277 |    0      |  300 |  1.5444 |  2.1225 | False      |   0      | True     |
| tgl        | mt_indomain      | MORPHAUSTRO - BPE | F2                |  3.9325 |    0      |  300 |  3.6333 |  4.2369 | False      |   0      | True     |
| tgl        | mt_indomain      | SCRAMBLED - BPE   | F2                |  3.2934 |    0      |  300 |  2.987  |  3.6062 | False      |   0      | True     |
| tgl        | ner              | MORPHAUSTRO - BPE | F0                |  0.0002 |    0.9816 | 1000 | -0.0158 |  0.0164 | False      |   1      | False    |
| tgl        | ner              | MORPHAUSTRO - BPE | F1                |  0.0131 |    0.0902 | 1000 | -0.0019 |  0.0285 | False      |   0.6448 | False    |
| tgl        | ner              | SCRAMBLED - BPE   | F1                | -0.0103 |    0.2103 | 1000 | -0.0262 |  0.006  | False      |   0.919  | False    |
| tgl        | ner              | MORPHAUSTRO - BPE | F2                |  0.0158 |    0.0467 | 1000 |  0      |  0.0312 | False      |   0.4203 | False    |
| tgl        | ner              | SCRAMBLED - BPE   | F2                |  0.0132 |    0.0966 | 1000 | -0.0025 |  0.029  | False      |   0.6448 | False    |
| tgl        | voice_probe      | MORPHAUSTRO - BPE | F0                |  0.1164 |    0      | 1200 |  0.1036 |  0.1294 | True       |   0      | True     |
| tgl        | voice_probe      | MORPHAUSTRO - BPE | F1                |  0.07   |    0      | 1200 |  0.0592 |  0.0811 | True       |   0      | True     |
| tgl        | voice_probe      | SCRAMBLED - BPE   | F1                |  0.0011 |    0.8884 | 1200 | -0.0133 |  0.0156 | False      |   1      | False    |
| tgl        | voice_probe      | MORPHAUSTRO - BPE | F2                |  0.0675 |    0      | 1200 |  0.0553 |  0.08   | True       |   0      | True     |
| tgl        | voice_probe      | SCRAMBLED - BPE   | F2                |  0.0136 |    0.0806 | 1200 | -0.0014 |  0.0289 | False      |   0.6448 | False    |