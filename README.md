# 💻 Ask your Documents  🤖

👋 Welcome to the Document QA system! This repository contains the code for a system that allows you to ask questions about your documents and get answers based on their contents. It supports a wide range of document formats, including PDF, Word, Excel, PowerPoint, text files, and even images!

<a href="https://ibb.co/2WfRtKN"><img src="https://i.ibb.co/0md1MJt/IMG-1413.jpg" alt="IMG-1413" border="0"></a><br /><a target='_blank' href='https://it.imgbb.com/'>
 
## 🚀 Features

* 💻 Supports a variety of document formats, including PDF, Word, Excel, PowerPoint, text files, and images
* 🤖 Uses the Hugging Face Transformers library to create embeddings for document chunks
* 🔍 Uses the FAISS library to create an index for those embeddings, allowing for efficient similarity search
* 💬 Allows users to ask questions about their documents and get answers based on the contents of those documents
* ⚡️ Uses multiprocessing to parallelize the creation of the index for improved performance

## 📋 Requirements

* Python 3.6 or higher
* The following Python packages:
	+ transformers
	+ langchain
	+ fitz
	+ Pillow
	+ textract
	+ pandas
	+ python-pptx
	+ concurrent-futures
	+ opencv-python (for image support)

## 🔧 Usage

1. Clone this repository to your local machine:
```bash
git clone https://github.com/AiGptCode/AskyourDocuments.git
```
2. Install the required Python packages:
```bash
pip install transformers langchain fitz pillow textract pandas python-pptx opencv-python concurrent-futures
```
3. Set your Hugging Face API key as an environment variable:
```bash
export HUGGINGFACE_API_TOKEN=your-api-key
```
4. Run the `main.py` script and enter the path to the directory containing your documents:
```bash
python AskyourDocuments.py
```
5. Ask a question about your documents and get an answer based on the contents of those documents.

Note: If you want to include images in your search, make sure they are in a supported format (e.g., JPEG, PNG) and are located in the same directory as your other documents.

## 🤝 Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork this repository to your own GitHub account.
2. Create a new branch for your changes:
```bash
git checkout -b my-feature-branch
```
3. Make your changes and commit them:
```bash
git commit -am 'Add some feature'
```
4. Push your changes to your fork:
```bash
git push origin my-feature-branch
```
5. Open a pull request against the original repository.

## 📄 License

This project is licensed under the MIT License.

## 🎉 Acknowledgments

* The Hugging Face Transformers library for providing pre-trained models and tokenizers
* The FAISS library for providing efficient similarity search and clustering of dense vectors
* The `langchain` library for providing utilities for creating and working with language models
* The `fitz` library for providing utilities for working with PDF files
* The `Pillow` library for providing utilities for working with image files
* The `textract` library for providing utilities for extracting text from various file formats
* The `pandas` library for providing utilities for working with tabular data in Python
* The `python-pptx` library for providing utilities for working with PowerPoint files
* The `concurrent-futures` library for providing a high-level interface for asynchronously executing callables
* The `opencv-python` library for providing utilities for working with image and video data (for image support)
