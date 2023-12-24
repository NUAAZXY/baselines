# Contextor

Here, we have adjusted the parameters of the baseline model and provide the corresponding experimental results.
"(provided)" indicates the experimental results using the parameters of the source model.
## Baseline Models

### TRANX

| learning rate  | BLEU      | CodeBLEU  |
|----------------|-----------|-----------|
| 5e-2           | 27.98     | 28.32     |
| 1e-3(provided) | **28.02** | **28.56** |
| 5e-3           | 27.64     | 27.96     |

### BertranX

| learning rate  | BLEU      | CodeBLEU  |
|----------------|-----------|-----------|
| 1e-4           | 32.58     | 33.89     |
| 5e-5(provided) | **34.18** | **36.00** |
| 1e-5           | 33.47     | 34.78     |

### UniXcoder

| learning rate  | BLEU      | CodeBLEU  |
|----------------|-----------|-----------|
| 5e-5           | 32.58     | 33.89     |
| 2e-5(provided) | 34.56     | 34.92     |
| 9e-6           | **34.93** | **35.03** |
| 6e-6           | 33.82     | 34.82     |


### CodeGPT

| learning rate  | BLEU      | CodeBLEU  |
|----------------|-----------|-----------|
| 1e-4           | 35.18     | **35.03** |
| 8e-5           | **35.37** | 34.81     |
| 5e-5(provided) | 34.03     | 33.58     |
| 2e-5           | 33.28     | 34.78     |

### CodeT5+

| learning rate  | BLEU      | CodeBLEU  |
|----------------|-----------|-----------|
| 8e-5           | 35.20     | 34.99     |
| 5e-5(provided) | 35.84     | 34.76     |
| 2e-5           | **36.21** | **35.12** |
| 9e-6           | 35.92     | 35.88     |
