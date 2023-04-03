# DocuChat: A Document Chat Application with Local Embeddings

DocuChat is a chat application that allows users to communicate with a document. The application uses OpenAI embeddings that are stored locally, eliminating the need for an external data store (e.g., Pinecone). 

## Technology

DocuChat is built using HTML, PHP, and JavaScript. The front-end of the application is built using HTML/JS. The back-end of the application is built using PHP. The local embeddings are stored as JSON output inside the browser, providing fast and efficient storage and retrieval of the embeddings.

## Requirements

To use DocuChat, you need to have an OpenAI API Key. You should edit the config.php file to include your API Key before using the application.

## Usage

Upload a PDF file (<25 pages) to start a conversation.
Enter your message in the input field and click "Send".
The application will use OpenAI embeddings to find relevant chunks of the PDF and display a summary after incorporating the most relevant chunks into the context. 

## Performance

The application is optimized for documents up to 50 pages in length (25 page limit can be removed). Longer documents may result in decreased performance.

## Installation

Clone this repository.
Edit the config.php file to include your OpenAI API Key.
Install and configure a web server with PHP and MySQL.
Upload the files to your web server.
Open the application in a web browser.

## Credits

DocuChat was developed by Yamil Ricardo Velez. It uses the OpenAI API for text embeddings.
