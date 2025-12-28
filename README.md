🛡️ AI-Driven Threat Modeling with STRIDE
📌 Project Overview

This project demonstrates the use of Artificial Intelligence and Prompt Engineering to automatically generate a threat modeling analysis based on the STRIDE methodology.

The solution receives an architecture diagram image as input and produces a structured security analysis covering:

Spoofing

Tampering

Repudiation

Information Disclosure

Denial of Service

Elevation of Privilege

The project was developed as part of a learning challenge and focuses on practical application, clear technical documentation, and knowledge sharing.

🎯 Learning Objectives

By completing this challenge, the following learning goals were achieved:

Apply theoretical concepts in a practical environment

Understand and apply the STRIDE threat modeling methodology

Use prompt engineering techniques to guide AI-generated analysis

Document technical processes in a clear and structured manner

Use GitHub as a platform for sharing technical knowledge and learning progress

🧠 Solution Concept

The core idea of this project is to combine architecture analysis with AI-assisted reasoning.

High-level flow:

An architecture diagram image is provided as input

The image context is described and interpreted

A carefully designed prompt applies the STRIDE methodology

An AI model generates a structured threat analysis

This approach reduces manual effort and helps standardize threat modeling in early stages of system design.

🏗️ Architecture Overview

The analyzed architecture is inspired by common Azure-based application scenarios, such as:

Virtual Machines

APIs and backend services

Networking components

Identity and access management

The image is used as a reference to reason about potential threats rather than performing automated image recognition.

🧩 Technologies Used

Python

Google Colab

FastAPI (conceptual API structure)

Azure OpenAI (or simulated LLM usage)

STRIDE Threat Modeling Methodology

Prompt Engineering

🧪 STRIDE Methodology

STRIDE is a threat modeling framework that categorizes security risks into six groups:

Category	Description
Spoofing	Impersonation of identities
Tampering	Unauthorized data modification
Repudiation	Lack of action traceability
Information Disclosure	Exposure of sensitive data
Denial of Service	Service availability disruption
Elevation of Privilege	Unauthorized privilege escalation

The AI-generated output follows this structure to ensure clarity and consistency.

🧠 Prompt Engineering Strategy

The prompt was designed to:

Describe the application architecture clearly

Guide the AI to analyze each STRIDE category separately

Generate concise, security-focused insights

Produce structured and readable output

This ensures the model behaves as a security analyst assistant, not just a text generator.

▶️ How to Run the Project (Google Colab)

Open the provided notebook in Google Colab

Upload or reference an architecture diagram image

Run the cells sequentially

Review the generated STRIDE threat analysis

⚠️ Note: The FastAPI implementation is included as a conceptual reference and is not deployed in production.

📁 Repository Structure
architecture-threat-modeling-ai/
│
├── README.md
├── notebooks/
│   └── threat_modeling_colab.ipynb
├── api/
│   └── main.py
├── prompts/
│   └── stride_prompt.md
├── images/
│   └── sample_architecture.png
└── docs/
    └── learning_notes.md

📚 References

Microsoft Learn – Azure Virtual Machines Quickstart

Digital Innovation One – STRIDE Demo Repository

🏁 Key Learnings

AI can effectively assist in early-stage threat modeling

Prompt quality directly impacts analysis accuracy

STRIDE provides a clear and structured way to reason about security risks

Clear documentation is as important as functional code

🚀 Future Improvements

Automated image interpretation using computer vision

Integration with real Azure OpenAI endpoints

Exporting results in security report formats

Expanding analysis to other threat modeling frameworks

📎 Final Notes

This repository represents both a technical implementation and a learning journey, focusing on understanding concepts, applying them in practice, and documenting insights for knowledge sharing.
