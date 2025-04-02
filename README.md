# Discriminative Feature Selection for Discharge Notes
This is the code (Google Colab friendly) to supplement the slides. Please note that due to the rules on using the MIMIC-III data set, the data are not provided. However, the code can be applied to any discharge text. 

Chart reviews are a commonplace procedure to maintain quality, compliance, ethics, and consistency of patient medical records. While lots of information can be extracted from structured fields, free-text notes, written by the clinician, can offer invaluable new, unique, or additional insights. 

In this case, NLP Discriminative Feature Selection is applied to identify top 100 phrases associated with discharges involving chest complaints. The model can be used for
- Understanding complaints, conditions, procedures, etc. most likely associated with admissions involving chest complaints. 
- Differentiating between cardiac and non-cardiac related chest complaints.  
- Applying these results to the next step of topic modeling and visualizing results in a dashboard for discussion and action planning around this important medical condition.

I recommend reviewing the accompanying short slide deck for the detailed project description and results.
