# ScholarSync - Automatic Citation Generator
ScholarSync is a web-based research utility designed to eliminate manual citation formatting. By leveraging academic APIs and web scraping, it extracts metadata from diverse sources and compiles them into a bibliography ready for export.

## Features
* Multiple Input Types: Supports DOI, arXiv, PMID, ISBN, URLs, and local PDF files.
* Multi-Style Support: Generate citations in APA, MLA, Harvard, Chicago, IEEE, and Vancouver formats.
* Word Export: Export your generated bibliography directly as a formatted .docx file.

**The folder has 3 important files**

* The citation_generator.ipynb file: This is here I executed the ideation phase and built the entire infrastructure for my final website. I have added detailed markdowns here to explain how everything works. For anyone trying to understand how the code works, I recommend going through this first. This served as the foundation for the app.py file.
* The app.py file: This is the .py file used to host the website and it was built based on the citation_generator.ipynb file.
* The requirements.txt file: This was a file needed to host the website.
