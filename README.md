# accentfixer

This project is dedicated to my mother, myself, and other immigrants struggling to sound closer to the native American language. By utilizing AI, the project aims to point out discrepancies between the user's recorded accent and native American English. 

At launch, the project will support General American accent. I plan to add a British accent option later for those living in the U.K.

## Tech Stack

- **Front-end**  
  - React (v18.x) + Web Audio API (recording widget)  
  - Tailwind CSS for styling  

- **Back-end**  
  - Python 3.10  
  - FastAPI (or Flask) for REST API  
  - PyTorch + Hugging Face Transformers (Wav2Vec 2.0)  

- **DevOps & CI/CD**  
  - Docker for containerization  
  - GitHub Actions (lint, test, build, deploy)  
  - Heroku (or AWS ECS) for hosting  

- **Data & Storage**  
  - Mozilla Common Voice & Speech Accent Archive  
  - (Optional) Postgres or S3 for audio logs  
