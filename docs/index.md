# AI Software Template

This application, manutest-rag-gitlab, was created from an AI Software Template. These software templates create a new source code repository as well as a new gitops deployment repository.

Included in the source code repository will be the chosen sample source application.

## Sample Source Application

RAG (Retrieval Augmented Generation) streamlit chat application with a vector database. Upload a file containing relevant information to train the model for more accurate responses.

## Repositories

The source code for your application can be found in [https://github.com/fpetk/manutest-rag ](https://github.com/fpetk/manutest-rag ).
 
The gitops repository, which contains the kubernetes manifests for the application can be found in 
[https://github.com/fpetk/manutest-rag-gitops ](https://github.com/fpetk/manutest-rag-gitops ). 

## Application namespaces 

The default application will be found in the namespace: **`rhdh-app`**. Applications can be deployed into their own unique namespace or multiple software templates can generate numerous applications into the same namespace.