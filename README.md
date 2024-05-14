# LLMOpsWorkshop
The content for Shift Left DevOps Practices for developing LLM Apps (aka LMOps) workshop

1. Introduction about MLOps principles
    - Discuss the need for MLOps: Explain how MLOps helps to bridge the gap between Machine Learning (ML) development and operations, enabling faster deployment, monitoring, and maintenance of ML models.
    - Technologies that support the principles of MLOps: Provide an overview of technologies like Kubernetes, Docker, Jenkins, etc. that support MLOps. Discuss how these technologies aid in automating and streamlining ML workflows.
    - Process and people in MLOps landscape: Discuss the roles and responsibilities of different stakeholders in MLOps, such as data scientists, ML engineers, and DevOps engineers. Also, explain the MLOps lifecycle, including steps like data collection, model training, model deployment, etc.

2. What is Shift Left and why it is important
    - Define Shift Left: Explain the concept of Shift Left, which involves incorporating testing and quality assurance early in the development process. Discuss how this approach helps to identify and address issues sooner, reducing costs and improving product quality.
    - Importance of Shift Left: Discuss the benefits of Shift Left, such as reducing time to market, improving product quality, and enhancing customer satisfaction.

3. Build up on top of MLOps principles, we will define LLMOps
    - Processes to use Large Language Models (LLMs): Discuss the specific processes involved in using LLMs, such as data collection, model training, and model deployment. Explain how these processes differ from those of traditional ML models.
    - Reflection of Shift Left on these processes: Discuss how the Shift Left approach can be applied to the processes involved in using LLMs. Discuss potential benefits and challenges.

- Case Study -

4. Build a Retrieval-Augmented Generation (RAG) application
    - Introduce RAG: Explain the concept of RAG, a method that combines the strengths of pretraining large neural language models with the benefits of efficient retrieval-based models.
    - Application focus: Discuss the focus of the application (e.g., a research assistant that understands research papers and can scrape the internet). Explain why this application was chosen and how it illustrates the principles of LLMOps.

5. Emphasize the importance of two MLOps principles:
    - Fairness (model evaluation): Discuss the importance of fairness in ML models, and how it can be evaluated. Discuss potential biases in data and algorithms, and how they can impact model performance and fairness.
    - Reproducibility (reproduce what has been reported): Discuss the importance of reproducibility in ML. Explain how reproducibility ensures that results can be independently verified, enhancing the credibility and reliability of ML models.

6. Introduce the application of MLflow for LLMs
    - Explain how MLflow, a platform for managing the ML lifecycle, can be used with LLMs. Discuss features of MLflow like experiment tracking, model versioning, and deployment, and how they support LLMOps.

7. Introduce what is evaluation and testing with LLMs
    - Discuss how evaluation and testing are performed with LLMs. Explain metrics used for evaluation, and how testing is performed to ensure model performance and reliability.

8. Demo time
    - Provide a live demonstration of the concepts discussed, using the RAG application as an example. Walk through the process of building, deploying, and monitoring the application, highlighting the use of MLOps and LLMOps principles.

- Mini Hackathon -

9. Guiding participant to build a RAG application on AWS
    - Provide a step-by-step guide for participants to build their own RAG application on AWS. Offer support and guidance as they work through the process, and encourage them to apply the principles of MLOps and LLMOps that they've learned in the workshop.
  
    - Main references:
https://mlflow.org/docs/latest/llms/rag/notebooks/mlflow-e2e-evaluation.html
https://pages.awscloud.com/rs/112-TZM-766/images/AWS_FMOps_LLMOps_Operationalise_GenAI_using_MLOps_principles.pdf
