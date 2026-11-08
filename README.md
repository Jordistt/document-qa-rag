# document-qa-rag
This project evaluates a Retrieval-Augmented Generation pipeline using Qwen 3.5 9B for PDF question answering.  It compares RAG against Zero-Shot approach and tests chunk sizes and other hyperparameters' effect on the output's quality.


## Knowlegde base: Motorsport Knowledge base
The knowledge base consists of three documents. One is about the track car "Porsche GT3 RS 992.1", which includes its features and details. The second one is in regard to the Nürburgring track, located in Nürbur, Germany. The last document contains statistics related to 2025 F1 world championship. They are well suited to the purpose of RAG: precise generation for specific domains and data that is more recent than the model’s.
