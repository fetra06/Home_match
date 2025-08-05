🏡 HomeMatch – Personalised Real Estate Listing Generator

HomeMatch is a smart real estate assistant built for Future Homes Realty. It leverages Large Language Models (LLMs) and vector databases to deliver highly personalised property listings that align with individual buyer preferences, creating a more engaging and intuitive home search experience.

⸻

🌟 Project Goals

In a market where customisation is key, HomeMatch reimagines real estate search by:
	•	Understanding buyers’ natural language descriptions of their dream home
	•	Using semantic similarity via embeddings to match listings
	•	Rewriting listing descriptions to emphasise features that matter most to the buyer

⸻

🧠 Features

✅ Interpret buyer needs from natural language input
✅ Search for listings using semantic embeddings via ChromaDB
✅ Use LLMs (OpenAI) to rewrite property descriptions in a personalised tone
✅ Present property information in an engaging, buyer-focused narrative

⚙️ How It Works
	1.	Input: User provides their preferences (e.g., “a cozy 3-bedroom near parks and good schools”).
	2.	Embedding: Listings and the user query are transformed into vector embeddings.
	3.	Semantic Search: The system retrieves top-matching properties using ChromaDB.
	4.	LLM Personalisation: The best-matching listings are rewritten by OpenAI GPT to focus on buyer preferences.
	5.	Output: A tailored list of real estate recommendations that read like they were written just for you.

📄 Example Listing (Before & After)

Original:

This stunning modern estate in Beverly Hills features sleek lines, high-end finishes…

Personalised:

If you love luxury and breathtaking views, this Beverly Hills gem is tailored just for you. Picture yourself entertaining guests in the spacious open-plan living room…

⸻

📦 Dependencies

From requirements.txt:
	•	langchain
	•	openai
	•	chromadb
	•	sentence-transformers
	•	transformers
	•	tiktoken
	•	pydantic, pytest, jupyter

⸻

🔐 API Keys

This project requires an OpenAI API key. You can get yours here: https://platform.openai.com/account/api-keys

⸻

📝 License

MIT License.
Feel free to use, share, and adapt this project with attribution.
