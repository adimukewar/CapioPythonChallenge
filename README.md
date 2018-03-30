# CapioPythonChallenge

#Brief Overview:
This repository uses CAPIO's REST API to transcribe the words from an audio file and store the recognized word along with respectve time stamps in aword file.

#Libraries used:

json: json encoder or decoder exposes an API familiar to users of standard library.
requests: Allows user to send HTTP/1.1 requests using Python
docx:The docx module creates, reads and writes Microsoft Office Word 2007 docx files

General algorithm of the program:
1. Import all the necessary libraries.
2. Pass the API-Key and Transcribtion ID to API_Response function.
3. requests.get object from requests library captures the API responce.
4. Each API response has a status code which signifies whether the response is in progress or some error is encountered. For example, status code=200 signifies that the API is received.
5. Thus, the API response in json array format is received only if the status code is 200.
6. Document object from docx library is used to store the transcriptors inside the word documents.

Directions for executing the program:
1. Clone the repository.
2. Execute the program using Terminal or Jupyter notebook.

Files:
1. Requirements.txt contains pip commands required for this program.
