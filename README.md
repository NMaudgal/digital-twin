		I developed an AI Digital Twin application using Next.js, FastAPI, and OpenAI APIs.
		The main challenge I solved was conversational memory. Initially, the chatbot was stateless and could not remember previous user interactions.
		To address this, I implemented a session-based memory architecture where conversation history was stored in JSON files and dynamically injected into prompts before calling the LLM.
		The frontend was built using React and Tailwind CSS with real-time chat rendering, while the backend handled API orchestration, session management, and OpenAI integration.
    This project established the core architecture that was later extended into a production-ready cloud-native AI platform on AWS.
