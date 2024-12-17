#HR Assisstant Chatbot
The project aims to create a conversational chatbot that responds to user inquiries using information from PDF document provided. It requires proficiency in extracting and converting text into numerical vectors, establishing an answer-finding mechanism, and designing a user-friendly chatbot interface with Gradio. Additionally, the initiative emphasizes structuring inquiries for clear communication and deploying the chatbot for practical use, guaranteeing the system's accessibility and efficiency in meeting user needs.

##Actions Performed
•	Load Nestle's HR policy using PyPDFLoader and split it for easy processing.
•	Create vector representations for text chunks using Chroma dB and OpenAI's embeddings.
•	Build a question-answering system using the GPT-3.5 Turbo model to retrieve answers from text chunks.
•	Create a prompt template to guide the chatbot in understanding and responding to users.
•	Use Gradio to build a user-friendly chatbot interface, enabling interaction and information retrieval.
