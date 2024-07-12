# PaperPal
## What is PaperPal?
PaperPal is a side project by YuChiChen, designed to handle unstructured data (PDF) through the following methods:
- Document Image Analysis (DIA): Using Detectron2 for document image analysis
- Optical Character Recognition (OCR) Postprocessing: Using TesseractOCR for OCR
- Multimodal Retrieval Augmented Generation (RAG)
   - Utilizing LangChain
   - Using GPT-4-turbo
   - Using Faiss vectorspace

## Usage
### How to Run the Code
1. Pull "paperpal.ipynb" to your Google Cloud
2. Follow the instructions in the code
> Note: There might be some issues with the environment setup, which could take some time to resolve.

## Caution
- The API key has been deleted, please replace it with your own API key.
- The input only accepts PDF files; other types of files are not supported.
- If you have any questions or suggestions, please feel free to contact me!

## Resource
- [利用 LangChain 實作多模態模型的 RAG：除了讀文章也能看圖答題](https://edge.aif.tw/application-langchain-rag/)
  - [Github - MultiModal-RAG](https://github.com/Claire-Lin/MultiModal-RAG/blob/main/MultiModal_RAG_Swin.ipynb)
- [Extracting Text from PDF Files with Python: A Comprehensive Guide](https://towardsdatascience.com/extracting-text-from-pdf-files-with-python-a-comprehensive-guide-9fc4003d517)
- [Langchain: PDF Chat App (GUI) | ChatGPT for Your PDF FILES | Step-by-Step Tutorial](https://www.youtube.com/watch?v=RIWbalZ7sTo)
  - [Link to the code](https://pastebin.com/mcHG4cY4)
- [Preprocessing Unstructured Data for LLM Applications](https://hackmd.io/@YungHuiHsu/SkJUlPCeA)
- [RAG + Langchain Python Project: Easy AI/Chat For Your Docs](https://www.youtube.com/watch?v=tcqEUSNCn8I)
  - [Github](https://github.com/pixegami/langchain-rag-tutorial)
- [Extract text, links, images, tables from Pdf with Python | PyMuPDF, PyPdf, PdfPlumber tutorial](https://www.youtube.com/watch?v=G0PApj7YPBo&t=101s)
  - [Source Code](https://pythonology.eu/what-is-the-best-python-pdf-library/#google_vignette)
- [Langchain（十）进阶之 prompt template 的使用](https://juejin.cn/post/7233726845136224293)
