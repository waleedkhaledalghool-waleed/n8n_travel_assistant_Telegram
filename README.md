# n8n_travel_assistant_Telegram
A multi-modal recommendation pipeline that accepts text, voice, and images as input. The system processes the inputs using a RAG (Retrieval-Augmented Generation) architecture backed by PostgreSQL (with pgvector for embeddings). It delivers personalized recommendations along with relevant YouTube video links.

# pipeline
trigger by sending to the bot on telegram -> check message contents - > if voice do whisper api from azure to turn into text - > if image run a vision llm to describe the image - > every output then goes to the ai agent that chooses what to recommed if there is something in the database rag system from the avaible flight plans that are in the db - -> give youtube links with the plan to show the locations that it recommends, it also does http web hook calls to access a list of avaiable flights to recommend it

# the bad news
The project got deleted before I could export it:
<br>
<br>
<br>
<img width="624" height="234" alt="image" src="https://github.com/user-attachments/assets/8d8d74f1-daee-4d8e-81f4-ccedeb96edad" />

# the good news
I still have the results:
<br>
<br>
<br>
<img width="346" height="463" alt="image" src="https://github.com/user-attachments/assets/1153f214-3f68-4c40-81bb-7fa7ab58195c" />

<img width="727" height="1600" alt="image" src="https://github.com/user-attachments/assets/7afd3fa3-4659-4070-b161-a9c688d7636f" />

<img width="727" height="1600" alt="image" src="https://github.com/user-attachments/assets/0b9d9b5e-0872-48d9-8f6f-0699e2556497" />



