# Arabic-Language-Coach


Arabic Language Coach is an AI-powered bilingual chatbot developed to help Arabic-speaking learners improve their English through interactive conversations. The system provides real-time corrections and explains mistakes in Arabic, creating a more effective and accessible learning experience.

As part of the project, our team designed and deployed a complete AI serving pipeline for Large Language Models (LLMs). We evaluated multiple language models and selected Qwen3-8B-AWQ as the primary model due to its strong performance, low latency, and cost efficiency during benchmarking.

From an infrastructure perspective, we containerized the application and model-serving components using Docker to ensure portability and consistent deployment across environments. The containers were then prepared for scalable deployment, enabling efficient model inference and resource management.

The project included configuring and managing LLM serving endpoints, monitoring model performance, and testing response quality using a bilingual evaluation dataset. We measured metrics such as response latency, first-token generation time, throughput, and overall success rate to validate the solution's effectiveness.

The chatbot follows a structured coaching workflow where users interact naturally in Arabic and English, while the language model analyzes input, generates corrections, and provides explanations in Arabic. This creates a continuous learning loop that encourages active practice and immediate feedback.
Additionally, we worked on deploying and integrating the AI solution within a web-based platform, allowing users to access the service through a browser without requiring local installation. The final solution demonstrates how modern AI infrastructure, containerization technologies, and large language models can be combined to deliver an intelligent and scalable educational application.
