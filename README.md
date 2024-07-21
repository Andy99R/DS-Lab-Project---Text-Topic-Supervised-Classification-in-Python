
Imporant: 
We decided to have three different files in order to make the understanding clearer and execution faster. 

	LSTM BENCHMARK and LSTM ENRICHED can be executed separately without any problem. The two files have different cleaning operations.
	The Descriptive Statistics needs the LSTM BENCHMARK cleaning to be executed first. 

Execution time may be long in the LSTM ENRICHED, the enrichment part takes 20 minutes but it depends on the hardware performance!

Necessary libraries: 
		pandas
		numpy
		nltk
		spacy
		scikit-learn
		seaborn
		matplotlib
		tensorflow
		wordcloud
		plotly

Extra needed: 
		nltk.download('stopwords')
		nltk.download('punkt')
		nltk.download('wordnet')
		!python -m spacy download en_core_web_sm
		pip install keras

