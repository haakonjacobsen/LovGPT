# LovGPT 🤖⚖️🇳🇴
LovGPT is an AI-powered legal assistant that leverages the power of GPT-4 and LangChain to provide users with accurate and reliable answers to their legal questions based on Norwegian law, legal practice, and other relevant legal documents. This revolutionary legal tool aims to make legal knowledge more accessible to the general public and aid legal professionals in their work.

🚀 **Houston, we have a... code delay!**: LovGPT is currently orbiting in a top-secret location, waiting for the perfect moment to land on GitHub. While it prepares for its grand entrance, I want to assure you that this groundbreaking AI, powered by GPT-4 and LangChain, is eager to assist you with all your Norwegian law questions. So, sit tight, buckle up, and get ready for launch! The countdown has begun... 🕒

## Table of Contents 📚

1. [Introduction](#introduction-🌐)
2. [Features](#features-🔎)
3. [Installation](#installation-💻)
4. [Usage](#usage-📝)
5. [Contribute](#contribute-💡)
6. [License](#license-📄)
7. [Acknowledgments](#acknowledgments-🙏)
## Introduction 🌐

LovGPT is designed to serve as a comprehensive legal resource for anyone seeking guidance on Norwegian law. By combining the state-of-the-art GPT-4 language model with LangChain's tool, LovGPT can understand and generate responses to a wide range of legal questions, from simple queries to complex legal issues.

## Features 🔎

- **User-friendly Interface**: LovGPT features a clean and straightforward interface, making it easy for users to ask questions and receive answers.
- **Reliable Legal Information**: Powered by [GPT-4](https://www.openai.com/gpt-4/) and [LangChain](https://python.langchain.com/en/latest/index.html) our own legal document store, LovGPT offers accurate legal insights based on Norwegian law, legal practice, and other legal documents.
- **Natural Language Processing**: LovGPT's advanced NLP capabilities enable users to ask questions in everyday language and receive clear, concise answers.
- **Secure and Private**: LovGPT ensures user privacy by not storing any personally identifiable information.

## Installation 💻

### Requirements

- Python 3.8 or higher
- pip

### Steps

1. Clone the LovGPT repository:
   `git clone https://github.com/haakonjacobsen/lovgpt.git`
2. Navigate to the project directory:
   `cd lovgpt`
3. Install the required packages:
   `pip install -r requirements.txt`
4. Launch the LovGPT application:
   `python app.py`

## Usage 📝

1. Open a web browser and visit `http://localhost:5000` to access the LovGPT interface.
2. Type your legal question into the input field and click the "Submit" button.
3. LovGPT will analyze your question and generate a response based on Norwegian law, legal practice, and other relevant legal documents.
4. Review the provided answer and consult a legal professional if necessary.

## Contribute 💡

We welcome contributions to LovGPT! If you would like to report bugs, suggest new features, or help improve the codebase, please create an issue or submit a pull request on our GitHub repository. Visuals are represented below. 

## License 📄

LovGPT is licensed under the MIT License. See [LICENSE](LICENSE) for more information.

## Architecture 🛠️🏗️
LovGPT is being built using my own experimental architecture, called the "experts" architecture, visualized below. The general idea is to have multiple instances of AI Agents (Experts) where each one are expert in a specific field by providing them with their own knowledge base. The Broker Agent handles the communication between the user and the rest of the system, figuring out "who to talk to" by utilizing the decision system. This makes the system modifiable, as more experts can easily be added for broader or more specific use cases.

The architecture also includes a review process, in the end, which is optional. This is to determine if the answer actually answers the question. 

<img src="https://github.com/haakonjacobsen/LovGPT/assets/15661593/06279759-2414-42da-9fad-609d4340dc40" width="600" title="Experts Architecture">

The Architecture was first created as a theoretical concept, and is very experimental, but similar architectures such as the [MRKL system](https://arxiv.org/pdf/2205.00445.pdf) has shown potential.


## Acknowledgments 🙏

- [OpenAI](https://www.openai.com/) for developing GPT-4.
- [LangChain](https://www.langchain.com/) for their domain-specific expertise.
- All contributors who have helped improve LovGPT.

## Project Status 🔄

Initially, LovGPT aimed to integrate Lovdata's legal databases, but their APIs did not meet our requirements for AI development. We've since shifted our approach to constructing a database from open-source documents, and also automating the process of building our corpus with image-to-text technology, and leveragining GPT-4 as a reasoning agent to deal with the dataset. Our goal remains to make Norwegian legal information more accessible.
