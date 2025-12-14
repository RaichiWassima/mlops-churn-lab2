# MLOps Churn Prediction Lab

End-to-end MLOps lab demonstrating:
- Data preprocessing & quality checks
- Model training with versioning
- Model registry & rollback
- REST API with FastAPI
- Production logging
- Data drift detection

## Project structure
src/
  prepare_data.py
  train.py
  evaluate.py
  api.py
  monitor_drift.py
  rollback.py
data/
models/
registry/
logs/
## How to run

```bash
python src/prepare_data.py
python src/train.py
python src/evaluate.py
uvicorn src.api:app --reload
python src/monitor_drift.py

Puis :

```powershell
git add README.md
git commit -m "Add README with project overview"
git push