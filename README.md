# Clean-Energy-Jobs-Act-NLP-Project
Unsupervised analysis of the Clean Energy Jobs Act (CEJA) in Illinois

**Description**\
Legislation can be complex and difficult to understand. This project uses natural language processing to aid human understanding of the Clean Energy Jobs Act, a lengthy bill proposed in the Illinois state legislature. Topic modeling, keyword highlighting, and auto-summarization save a lot of time for the political professional or curious citizen trying to get a high-level understanding of the bill. Parts of speech tagging and named entity recognition extract the rules and obligations set forth in the bill to identify the burdens and subjects responsible for compliance.

**Data Used**\
I downloaded a pdf of the Clean Energy Jobs Act (HB804) from the TrackBill website and used pdfPlumber to process the data and store it in a usable format for analysis. 

**Tools used**
* pdfplumber
* Python
* Pandas
* NumPy
* NLTK
* spaCy
* Seaborn
* Matplotlib
* Plotly

**Possible Impacts**\
My analysis makes it easier for a reader to get acquainted with the bill. Next steps include: build a recommendation system that uses advanced distance calculations to recommend similar bills, both at the state and federal level. I also want to build an app that takes in a piece of legislation and returns a dashboard highlighting the entities responsible for compliance, the main topics and how they vary throughout the bill, and summaries of each Section.
