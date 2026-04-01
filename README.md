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
