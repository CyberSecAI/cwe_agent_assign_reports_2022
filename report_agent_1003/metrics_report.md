# CWE Comparison Metrics Report

## Overall Metrics

- **Total CVEs**: 6397
- **CVEs in both datasets**: 5845
- **CVEs with at least one CWE match**: 5163 (88.33%)
- **CVEs with exact CWE matches**: 1603 (27.43%)

## Classification Metrics

- **Precision**: 0.4847
- **Recall**: 0.8064
- **F1 Score**: 0.6055
- **Accuracy**: 0.9907

## Confusion Matrix

- **True Positives**: 5783
- **False Positives**: 6147
- **False Negatives**: 1388
- **True Negatives**: 799101

## Top 10 Most Frequently Matched CWEs

| CWE ID | Matches | In JSON | In Benchmark | Precision | Recall | F1 Score |
|--------|---------|---------|--------------|-----------|--------|----------|
| CWE-119 | 687 | 848 | 912 | 0.81 | 0.75 | 0.78 |
| CWE-20 | 461 | 673 | 632 | 0.68 | 0.73 | 0.71 |
| CWE-78 | 346 | 663 | 360 | 0.52 | 0.96 | 0.68 |
| CWE-787 | 277 | 822 | 366 | 0.34 | 0.76 | 0.47 |
| CWE-862 | 255 | 434 | 302 | 0.59 | 0.84 | 0.69 |
| CWE-287 | 192 | 331 | 275 | 0.58 | 0.70 | 0.63 |
| CWE-416 | 179 | 234 | 193 | 0.76 | 0.93 | 0.84 |
| CWE-200 | 159 | 466 | 184 | 0.34 | 0.86 | 0.49 |
| CWE-79 | 152 | 217 | 159 | 0.70 | 0.96 | 0.81 |
| CWE-77 | 148 | 264 | 244 | 0.56 | 0.61 | 0.58 |

## Top 10 Least Frequently Matched CWEs

| CWE ID | Matches | In JSON | In Benchmark | Precision | Recall | F1 Score |
|--------|---------|---------|--------------|-----------|--------|----------|
| CWE-552 | 1 | 24 | 5 | 0.04 | 0.20 | 0.07 |
| CWE-682 | 2 | 5 | 6 | 0.40 | 0.33 | 0.36 |
| CWE-834 | 3 | 5 | 5 | 0.60 | 0.60 | 0.60 |
| CWE-252 | 3 | 16 | 7 | 0.19 | 0.43 | 0.26 |
| CWE-212 | 4 | 10 | 5 | 0.40 | 0.80 | 0.53 |
| CWE-294 | 4 | 11 | 5 | 0.36 | 0.80 | 0.50 |
| CWE-307 | 4 | 6 | 6 | 0.67 | 0.67 | 0.67 |
| CWE-610 | 4 | 8 | 6 | 0.50 | 0.67 | 0.57 |
| CWE-706 | 5 | 14 | 7 | 0.36 | 0.71 | 0.48 |
| CWE-120 | 5 | 60 | 11 | 0.08 | 0.45 | 0.14 |

## Top 10 Most Frequent CWEs in JSON Results

| CWE ID | In JSON | In Benchmark | Matches | Precision | Recall |
|--------|---------|--------------|---------|-----------|--------|
| CWE-119 | 848 | 912 | 687 | 0.81 | 0.75 |
| CWE-787 | 822 | 366 | 277 | 0.34 | 0.76 |
| CWE-20 | 673 | 632 | 461 | 0.68 | 0.73 |
| CWE-78 | 663 | 360 | 346 | 0.52 | 0.96 |
| CWE-863 | 545 | 213 | 137 | 0.25 | 0.64 |
| CWE-200 | 466 | 184 | 159 | 0.34 | 0.86 |
| CWE-862 | 434 | 302 | 255 | 0.59 | 0.84 |
| CWE-269 | 402 | 166 | 137 | 0.34 | 0.83 |
| CWE-306 | 341 | 122 | 104 | 0.30 | 0.85 |
| CWE-287 | 331 | 275 | 192 | 0.58 | 0.70 |

## Top 10 Least Frequent CWEs in JSON Results

| CWE ID | In JSON | In Benchmark | Matches | Precision | Recall |
|--------|---------|--------------|---------|-----------|--------|
| CWE-834 | 5 | 5 | 3 | 0.60 | 0.60 |
| CWE-682 | 5 | 6 | 2 | 0.40 | 0.33 |
| CWE-335 | 5 | 3 | 3 | 0.60 | 1.00 |
| CWE-307 | 6 | 6 | 4 | 0.67 | 0.67 |
| CWE-426 | 6 | 3 | 2 | 0.33 | 0.67 |
| CWE-669 | 6 | 2 | 1 | 0.17 | 0.50 |
| CWE-178 | 7 | 6 | 5 | 0.71 | 0.83 |
| CWE-610 | 8 | 6 | 4 | 0.50 | 0.67 |
| CWE-338 | 9 | 1 | 1 | 0.11 | 1.00 |
| CWE-212 | 10 | 5 | 4 | 0.40 | 0.80 |

## Top 10 Most Frequent CWEs in Benchmark

| CWE ID | In Benchmark | In JSON | Matches | Precision | Recall |
|--------|--------------|---------|---------|-----------|--------|
| CWE-119 | 912 | 848 | 687 | 0.81 | 0.75 |
| CWE-20 | 632 | 673 | 461 | 0.68 | 0.73 |
| CWE-787 | 366 | 822 | 277 | 0.34 | 0.76 |
| CWE-78 | 360 | 663 | 346 | 0.52 | 0.96 |
| CWE-862 | 302 | 434 | 255 | 0.59 | 0.84 |
| CWE-287 | 275 | 331 | 192 | 0.58 | 0.70 |
| CWE-77 | 244 | 264 | 148 | 0.56 | 0.61 |
| CWE-863 | 213 | 545 | 137 | 0.25 | 0.64 |
| CWE-416 | 193 | 234 | 179 | 0.76 | 0.93 |
| CWE-200 | 184 | 466 | 159 | 0.34 | 0.86 |

## Top 10 Least Frequent CWEs in Benchmark

| CWE ID | In Benchmark | In JSON | Matches | Precision | Recall |
|--------|--------------|---------|---------|-----------|--------|
| CWE-212 | 5 | 10 | 4 | 0.40 | 0.80 |
| CWE-552 | 5 | 24 | 1 | 0.04 | 0.20 |
| CWE-294 | 5 | 11 | 4 | 0.36 | 0.80 |
| CWE-834 | 5 | 5 | 3 | 0.60 | 0.60 |
| CWE-829 | 5 | 16 | 5 | 0.31 | 1.00 |
| CWE-307 | 6 | 6 | 4 | 0.67 | 0.67 |
| CWE-682 | 6 | 5 | 2 | 0.40 | 0.33 |
| CWE-178 | 6 | 7 | 5 | 0.71 | 0.83 |
| CWE-772 | 6 | 15 | 5 | 0.33 | 0.83 |
| CWE-662 | 6 | 18 | 6 | 0.33 | 1.00 |

## CVEs With No Matches

| CVE ID | JSON CWEs | Benchmark CWEs |
|--------|-----------|----------------|
| CVE-2020-0479 | CWE-862 | CWE-79 |
| CVE-2020-0688 | CWE-787, CWE-502 | CWE-287 |
| CVE-2020-10181 | CWE-269 | CWE-352 |
| CVE-2020-1027 | CWE-269 | CWE-119 |
| CVE-2020-1054 | CWE-416, CWE-119 | CWE-787 |
| CVE-2020-10580 | CWE-94, CWE-78 | CWE-77 |
| CVE-2020-10666 | CWE-94 | CWE-77 |
| CVE-2020-10919 | CWE-522, CWE-327 | CWE-798 |
| CVE-2020-11165 | CWE-120, CWE-119 | CWE-787 |
| CVE-2020-11176 | CWE-787 | CWE-119 |
| CVE-2020-11182 | CWE-1284, CWE-787 | CWE-119 |
| CVE-2020-11264 | CWE-306 | CWE-287 |
| CVE-2020-11267 | CWE-787 | CWE-119 |
| CVE-2020-11469 | CWE-668, CWE-59 | CWE-552 |
| CVE-2020-1147 | CWE-94, CWE-20 | CWE-668, CWE-502 |
| CVE-2020-11492 | CWE-668, CWE-269 | CWE-362 |
| CVE-2020-11547 | CWE-200 | CWE-306 |
| CVE-2020-11967 | CWE-863, CWE-306 | CWE-862 |
| CVE-2020-12733 | CWE-798 | CWE-287 |
| CVE-2020-12734 | CWE-306, CWE-1188 | CWE-862 |

*...and 662 more CVEs with no matches*

## Primary vs Secondary CWE Analysis

- **Total primary CWE matches**: 4976
- **Total secondary CWE matches**: 1371
- **CVEs where only primary CWEs matched**: 3817
- **CVEs where only secondary CWEs matched**: 475
- **CVEs where both primary and secondary CWEs matched**: 871
