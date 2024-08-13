# dbt-semantic-layer-erd
A python script to run a streamlit app to output information relevant to dbt Semantic Models including DBML ERDs


## Demo
https://dbtlabs.zoom.us/clips/share/40y0ZEibbrQA8wh7fTVUeNNsYZuzRrmcLgovgHypTYAOh96xY6bTkoCKMP69SzEZacq5VAug-JljicV3oPG-Jx55.2zys01KRrxtnGwns

## Outputs

two csv files:
- semantic models
- metrics

and the ability to export:
- all semantic model ERD (including metrics)
- ERD focused on one metric (or multiple) selected via the UI dropdown


## To run: 
- `pip install -r requirements.txt`
- Run `streamlit run dbt_erd.py`

Or use the interactive version online: <https://dbt-semantic-layer-erd.streamlit.app/>

Visualize ERD here:
https://dbdiagram.io/home 


## Questions, comments, feedback?
🧪 Extraordinarily experimental! 
- Share feedback in the [community Slack](https://getdbt.com/community) with @patkearns
- open up an Issue
