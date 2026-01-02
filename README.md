## Abstract
Predictive Modeling for Accurate Delivery Time is a machine learning project focused on estimating delivery durations using historical logistics data. Accurate delivery time predictions are critical for improving customer experience, optimizing operational planning, and reducing uncertainty in delivery logistics.

Through exploratory data analysis (EDA), significant discrepancies were identified between the system’s estimated delivery times and the actual delivery outcomes. This variability highlighted clear opportunities for improving delivery time estimation using data-driven models.

### The project includes:
- Exploratory data analysis (EDA)
- Feature engineering
- Model training and evaluation
- Business-oriented interpretation of results

Model performance was evaluated by comparing both the current system ETA (baseline) and the machine learning predictions against the actual delivery time.

### 📈 Results
| Model | MAE (hours) | RMSE (hours) | R² |
|------|-------------|--------------|----|
| Current ETA (Baseline) | 8.10 | 110.91 | -10.45 |
| Random Forest Model | 0.03 | 0.02 | 0.998 |

Compared to the existing ETA estimation, the Random Forest model reduced the average prediction error from approximately 8 hours to just a few minutes, while also dramatically reducing large prediction errors, as reflected by the RMSE metric. At same time, we can find a reduction of 47% over expected delivery time 

These results demonstrate that the proposed model captures key patterns driving delivery duration and can provide substantially more reliable delivery time estimates, supporting improved operational planning and more accurate customer-facing ETAs.
