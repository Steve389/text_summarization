# text summarization and keyword extraction
Development of several natural language processing models in order to summarize text and extract keywords.

While participating in the Code X hackathon in Riga, me and my team developed an application that facilitates notetaking during virtual meetings.
The application has the following functionalities: 
- it summarizes Microsoft Teams transcripts and extracts the main topics discussed during the conversation. 
- it sends automatic emails with meeting notes and topics discussed to meeting participants. 
- it keeps track of all meetings related to each project in a timeline-like manner.
- it allows filtering by topics discussed to allow simple tracking of meeting followups. 
- it enables further improvement by allowing participants to improve our summarization model while it is being used. 
- it shows the minutes that each meeting participant spoke.

My specific role in this project was to develop the summarization and keyword extraction model. 
This repository shows the different models I tried and how they performed:


- nltk
- "facebook/bart-large-cnn" model 
- "knkarthick/bart-large-xsum-samsum" model
- KeyBERT
- Yake

After different trials, the optimal combination we decided to go with was the "facebook/bart-large-cnn" model for text summarization and KeyBERT for keyword extraction.

