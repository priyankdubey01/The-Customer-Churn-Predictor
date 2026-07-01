To run it:
bash

cd backend
pip install -r requirements.txt
uvicorn main:app --reload --port 8000



Then open http://localhost:8000 and upload backend/sample_data/behavior_logs.csv to see it live.
