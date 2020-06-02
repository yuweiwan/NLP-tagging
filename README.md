# NLP-tagging
Use HMM to tag POS  
vtag.py is for supervised learning and it uses entrain, which is an already-tagged text.  
vtag_em.py is for unsupervised learning and it uses enraw, which is untagged data. entrain25k is a shorter version of entrain.   
It assumed that we don't have much tagged data and we use untagged data to improve the tagger.  
Command:  
python3 vtag.py entrain entest  
python3 vtag_em.py entrain25k entest enraw
