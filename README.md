## Project Title: PDF Chat

Interact with your PDF files by querying them using a user-friendly interface.

### Description

This project provides a UI to interact with and query information from uploaded PDF files. Utilizing the OpenAI API, it enables users to extract and refine information seamlessly.

### Features

- Upload PDF: Allows users to upload PDF files.
- OpenAI Integration: Enter your OpenAI API key to facilitate querying.
- Query Input: Type your questions and click "Run" to obtain answers from the uploaded PDF.
- Advanced Settings: Users can adjust settings like the number of relevant chunks and chain type for more refined results.

### Installation

1. Clone the repository.
2. Ensure you have the necessary libraries installed.
3. Obtain an OpenAI API key and set up billing on the [OpenAI Platform](https://platform.openai.com/account).

### Usage

1. Run the script.
2. Upload your desired PDF file.
3. Enter your OpenAI API key in the provided field.
4. Type your query in the text editor.
5. Click "Run" to get the answers along with relevant source text extracted from the PDF.

### Dependencies

- langchain
- panel
- tempfile
