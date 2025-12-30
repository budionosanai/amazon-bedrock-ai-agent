## 📘 Overview

This repository explains AI agent implementation for candidate screening use case that can compare and match between job requirements and CV, create result to the next step of the recruitment process and create interview questions (if candidate have more than 7 of 10).

## 📁 Repository Structure

| File / Notebook | Description |
| :--- | :--- |
| `crewai/crewai.ipynb` | Notebook of AI agent implementation using **Amazon Nova** and **CrewAI**. |
| `crewai/crewai1.PNG`, `crewai/crewai2.PNG`, `crewai/crewai3.PNG` | Screenshot of several tasks used in the `crewai/crewai.ipynb`. |
| `langgraph/langgraph.ipynb` | Notebook of AI agent implementation using **Amazon Nova** and **Langgraph**. |
| `langgraph/langgraph1.PNG`, `langgraph/langgraph2.PNG` | Screenshot of several tasks used in the `langgraph/langgraph.ipynb`. |
| `Always Winner CV.pdf` and `Sonny Wawwak CV.pdf` | Sample PDF file used in the `crewai/crewai.ipynb` and `langgraph/langgraph.ipynb` |

## ✅ Prerequisites

1.  **Amazon Web Services (AWS)**: Access to **Amazon Nova** on **Amazon Bedrock**, you can sign up/sign in [here.](https://console.aws.amazon.com)

2.  **CrewAI** and **Langgraph**: Access to create AI agent application.

## 🚀 Getting Started

1. Clone this repository
```bash
git clone https://github.com/budionosanai/amazon-bedrock-ai-agent.git
cd amazon-bedrock-ai-agent
```

2. Open, run and following this notebooks :

| Notebook | Using |
| :--- | :--- |
| **[Langgraph](./langgraph/langgraph.ipynb)** | **Google Colab**. |
| **[CrewAI](./crewai/crewai.ipynb)** | **Google Colab**. |

3. If notebook have Python environment that store such as `load_dotenv("....txt")`, create Python environment using python-dotenv, you can see this [link.](https://pypi.org/project/python-dotenv/) then write your AWS key in a Notepad file, then save the file with the name `....txt` (e.g. `env.txt`).

## ⚠️ Warning

**Ensure securely API keys such as AWS key — DO NOT HARDCORE them in notebooks.**

## 📚 Resources

* [Amazon Nova documentation](https://docs.aws.amazon.com/nova/)
* [CrewAI documentation](https://docs.crewai.com/)
* [Langgraph documentation](https://docs.langchain.com/oss/python/langgraph/)

## 🙏 Acknowledgments

**Amazon Web Services, CrewAI, Langgraph and Google Colab**