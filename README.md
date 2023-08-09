conda create -n slacksentiment python=3.10

conda activate slacksentiment

pip install -r requirements.txt

python -m streamlit run streamlit_slack_toxicity_poc.py


