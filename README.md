# DataAnalysis_p3
NLP-Based Topic Extraction 

#How to Use the Code

Before running the code, make sure you have Python 3.x installed. It’s recommended to use a virtual environment to manage dependencies.

Setup:
1. Clone the repository:
   
       git clone https://github.com/rinaxweds/DataAnalysis_P3.git
       cd DataAnalysis_P3.git

3. Install required libraries:

   
       pip install -r requirements.txt

4. Run the Topic Modeling Script
To analyze the dataset and extract topics, run:


       python topic_modeling.py

This will:
*Process and clean the text data.
*Apply NMF to extract complaint topics.
*Display key topics and generate word cloud visuals.
*Calculate a coherence score to evaluate model quality.


Output
Processed data and results will be saved in the results/ folder.
Topic modeling summaries and word clouds are generated for interpretation.

Notes
If needed, parameters (e.g., number of topics) can be adjusted in config.py.

