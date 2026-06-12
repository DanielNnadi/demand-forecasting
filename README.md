
---

### 3. `demand-forecasting`

```markdown
# Demand Forecasting with Prophet

## Problem
Emergency procurement was happening 23 times per month because demand wasn't being predicted.

## What I Did
- Built Python Prophet demand forecasting model
- Analyzed 18 months of historical data
- Established cross-functional review process

## Tech Stack
- Python
- Prophet (Facebook)
- pandas
- SQL

## Results
| Metric | Before | After |
|--------|--------|-------|
| Emergency procurement/month | 23 | 8 |
| Reduction | - | 65% |

## Code Sample
```python
from prophet import Prophet
import pandas as pd

model = Prophet()
model.fit(df)
forecast = model.predict(future)
