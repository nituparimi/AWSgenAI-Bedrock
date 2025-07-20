# AWSgenAI-Bedrock
bedrock apps

faiss-cpu in requirements.txt is used for creating vector embeddings from local env

Documents -> Split into Chunks -> Create Embedings -> Vector Store

streamlit run app.py

If you feel the pdf file you uploading is safe, then add allow_dangerous_deserialization = True in the source code
faiss_index = FAISS.load_local("faiss_index", bedrock_embeddings, allow_dangerous_deserialization= True)

https://aws.amazon.com/blogs/machine-learning/build-powerful-rag-pipelines-with-llamaindex-and-amazon-bedrock/
