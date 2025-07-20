# AWSgenAI-Bedrock
bedrock apps

faiss-cpu in requirements.txt is used for creating vector embeddings from local env

Documents -> Split into Chunks -> Create Embedings -> Vector Store

streamlit run app.py

If you feel the pdf file you uploading is safe, then add allow_dangerous_deserialization = True in the source code
faiss_index = FAISS.load_local("faiss_index", bedrock_embeddings, allow_dangerous_deserialization= True)

https://aws.amazon.com/blogs/machine-learning/build-powerful-rag-pipelines-with-llamaindex-and-amazon-bedrock/

<img width="1400" height="1265" alt="image" src="https://github.com/user-attachments/assets/527b2611-75fd-4f25-a0ca-bf1f4a3f0ceb" />
