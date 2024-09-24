# LocalServicesFinder-Jaipur

LocalServicesFinder-Jaipur is a chatbot specifically designed to assist users with service-related inquiries. By feeding data about various services into a large language model (LLM), this chatbot provides insightful information and advice for service care, identification, and maintenance.

## Features
- User-friendly interface for answering service-related questions.
- Comprehensive repository of service-related information.
- Personalized guidance and recommendations based on user inputs.

## Installation
To get started with LocalServicesFinder-Jaipur, follow these steps: 

Clone the repository by running:
git clone https://github.com/zordasic/LocalServicesFinder-Jaipur.git
cd LocalServicesFinder-Jaipur

Install the Gaia Node with:
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

Update the config.json file to run with a small language model using:
gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json

Start the node by executing:
gaianet start

## How to Use
Open your web browser and navigate to the generated link. Start interacting with the chatbot by typing your service-related questions.
