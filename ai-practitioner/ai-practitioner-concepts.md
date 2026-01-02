## 1. Fundamentals of AI and ML

1.1 **Basic AI terms and concepts**  
- **AI, ML, deep learning**: AI is any technique that enables computers to mimic human intelligence; ML is a subset that learns patterns from data; deep learning uses multi‑layer neural networks for complex tasks like vision and language.
- **Neural networks**: Computational graphs of connected “neurons” that transform inputs into outputs, well‑suited for images, speech, and text.
- **Computer vision and NLP**: Computer vision extracts information from images/videos; NLP lets systems understand and generate human language.
- **Model vs algorithm**: An algorithm is the procedure to learn; a model is the learned representation deployed for inference.
- **Training vs inference**: Training adjusts model parameters using data; inference uses a trained model to make predictions or generate outputs.
- **Bias, fairness, fit**: Bias and fairness relate to systematic advantages or disadvantages across groups; fit describes how well a model captures data patterns (overfitting vs underfitting).
- **LLM (large language model)**: A very large neural network trained on extensive text data to perform tasks like chat, summarization, and translation.

1.2 **Types of data for AI**  
- **Labeled vs unlabeled**: Labeled data includes inputs with known outputs; unlabeled lacks explicit targets and is used mainly in unsupervised learning.
- **Tabular and time‑series**: Tabular data is structured in rows/columns (e.g., customer table); time‑series is ordered by time (e.g., sensor readings).
- **Image and text data**: Images are pixel grids; text is sequences of tokens; both are typically unstructured and require specialized models.
- **Structured vs unstructured**: Structured data follows predefined schemas; unstructured (documents, audio, video) requires additional processing before ML.

1.3 **Learning paradigms**  
- **Supervised learning**: Learns from labeled examples to predict continuous values (regression) or discrete classes (classification).
- **Unsupervised learning**: Finds patterns or groups without labels, such as clustering similar customers.
- **Reinforcement learning**: An agent learns by taking actions in an environment to maximize cumulative reward.

1.4 **Inference types**  
- **Batch inference**: Processes large sets of data periodically, useful when real‑time responses are unnecessary and cost control matters.
- **Real‑time inference**: Returns predictions with low latency per request, crucial for interactive apps like chatbots and fraud checks.

1.5 **AI use cases and when not to use AI**  
- **High‑value applications**: Assist decision‑making, scale solutions, and automate repetitive tasks (e.g., recommendations, fraud detection, forecasting).
- **When AI/ML is inappropriate**: When rules are simple, interpretability must be absolute, or cost–benefit does not justify added complexity.

1.6 **Core ML techniques**  
- **Regression**: Predicts numeric values (e.g., revenue forecast).
- **Classification**: Predicts categories (e.g., spam vs non‑spam).
- **Clustering**: Groups similar items without labels (e.g., customer segments).

1.7 **ML development lifecycle**  
- **Pipeline stages**: Data collection, exploratory data analysis, preprocessing, feature engineering, model training, hyperparameter tuning, evaluation, deployment, and monitoring.
- **Model sources**: Pre‑trained open source/foundation models vs custom models trained from scratch, chosen based on data availability and requirements.
- **Production usage**: Models are exposed through managed APIs (e.g., SageMaker endpoints or Bedrock) or self‑hosted services.

1.8 **MLOps and model monitoring**  
- **MLOps goals**: Standardize experiments, create repeatable pipelines, scale systems, and manage technical debt while ensuring production readiness.
- **Ongoing monitoring**: Tracks model performance drift and triggers retraining to maintain business value over time.

1.9 **Evaluation metrics and business impact**  
- **Technical metrics**: Accuracy, AUC, F1 score, and similar metrics quantify predictive quality.
- **Business metrics**: Cost per user, development cost, ROI, and customer feedback show whether the model actually helps the organization.

1.10 **AWS ML services for classic AI**  
- **Amazon SageMaker**: End‑to‑end platform to build, train, and deploy ML models with supporting tools like Data Wrangler, Feature Store, and Model Monitor.
- **Managed AI APIs**: Services like Amazon Transcribe, Translate, Comprehend, Lex, and Polly provide ready‑made speech, translation, NLP, chatbot, and text‑to‑speech capabilities.

***

## 2. Fundamentals of Generative AI

2.1 **Core generative AI concepts**  
- **Tokens and chunking**: Tokens are small text units; chunking splits long inputs into manageable pieces for LLMs within context limits.
- **Embeddings and vectors**: Embeddings map text or other data into numeric vectors capturing semantic similarity, used for search and retrieval.
- **Transformer‑based LLMs**: Transformers use self‑attention to handle long‑range dependencies, powering modern LLMs and many foundation models.
- **Foundation and multi‑modal models**: Foundation models are large, general‑purpose models; multi‑modal models handle combinations of text, images, audio, or video.
- **Diffusion models**: Generative models that iteratively remove noise from random inputs to produce realistic images, audio, or video.
- **Prompt engineering**: The practice of crafting inputs (prompts) to steer model behavior and output quality.

2.2 **Generative AI use cases**  
- **Content generation**: Create images, videos, audio, and text (e.g., marketing copy, design assets, synthetic voices).
- **Language tasks**: Summarization, translation, chatbots, code generation, and customer service agents that respond conversationally.
- **Search and recommendations**: Use embeddings and generative models to power semantic search and personalized recommendation engines.

2.3 **Generative AI lifecycle**  
- **Model lifecycle stages**: Data selection, model selection, pre‑training, fine‑tuning, evaluation, deployment, and feedback collection.
- **Feedback loop**: Continuous feedback from users and metrics helps refine prompts, fine‑tuning data, and configuration.

2.4 **Strengths and limitations of generative AI**  
- **Advantages**: Highly adaptable, responsive, and simple to integrate via APIs, often accelerating development and innovation.
- **Limitations**: Prone to hallucinations, may lack interpretability, and are non‑deterministic, so outputs can vary between calls.

2.5 **Model selection and constraints**  
- **Selection factors**: Model type, capabilities, performance, latency, cost, compliance, and domain alignment guide which model to choose.
- **Business value metrics**: Cross‑domain performance, efficiency, conversion rate, ARPU, and customer lifetime value benchmark success.

2.6 **AWS generative AI services and infrastructure**  
- **Key services**: Amazon Bedrock, Amazon SageMaker JumpStart, PartyRock (Bedrock playground), and Amazon Q for generative AI use cases.
- **Benefits on AWS**: Built‑in security, compliance, safety, and managed infrastructure lower the barrier to building generative AI apps.
- **Cost trade‑offs**: Balance responsiveness, availability, redundancy, performance, regional coverage, token‑based pricing, provisioned throughput, and custom model costs.

***

## 3. Applications of Foundation Models

3.1 **Designing applications with foundation models**  
- **Model selection criteria**: Evaluate cost, modality (text, vision, multi‑modal), latency, multilingual support, model size, complexity, and context length.
- **Inference parameters**: Settings like temperature and max input/output length control creativity and verbosity of outputs.

3.2 **Retrieval Augmented Generation (RAG)**  
- **RAG concept**: Combines foundation models with external knowledge retrieval so the model grounds answers in up‑to‑date, domain‑specific data.
- **Business use**: Powering knowledge bases and question‑answering over proprietary documents via services like Amazon Bedrock knowledge bases.

3.3 **Vector stores and embeddings on AWS**  
- **Vector databases**: Services like Amazon OpenSearch Service, Amazon Aurora, Amazon Neptune, Amazon DocumentDB, and Amazon RDS for PostgreSQL can store embeddings for semantic search.
- **Usage pattern**: Compute embeddings for documents, store them in a vector index, retrieve top matches at query time, then feed into a foundation model.

3.4 **Customization strategies and cost trade‑offs**  
- **Customization options**: Pre‑training, fine‑tuning, in‑context learning, and RAG offer different levels of control and cost.
- **Trade‑offs**: Heavier customization (pre‑training, fine‑tuning) increases performance for narrow tasks but costs more than prompt‑only or RAG approaches.

3.5 **Agents and multi‑step workflows**  
- **Agents for Bedrock**: Orchestrate multi‑step tasks by breaking user goals into sub‑tasks, calling tools and APIs, and synthesizing final answers.
- **Role of agents**: Automate complex workflows (e.g., booking, troubleshooting) that require external system interactions beyond plain text generation.

3.6 **Prompt engineering concepts**  
- **Prompt components**: Context, explicit instructions, examples, and negative prompts together shape model behavior in latent space.
- **Techniques**: Zero‑shot, single‑shot, few‑shot, chain‑of‑thought, and prompt templates help achieve more accurate and consistent outputs.
- **Best practices**: Iterate, be specific and concise, include guardrails, and sometimes combine multiple calls to refine results.

3.7 **Prompt engineering risks**  
- **Prompt exposure and poisoning**: Sensitive data in prompts might leak; malicious content can shift model behavior or training data.
- **Hijacking and jailbreaking**: Attackers try to bypass safety constraints or alter system instructions, so defenses and validation are needed.

3.8 **Training and fine‑tuning foundation models**  
- **Training stages**: Pre‑training on broad data, fine‑tuning on domain‑specific tasks, and continuous pre‑training for ongoing improvement.
- **Fine‑tuning methods**: Instruction tuning, transfer learning to specific domains, and continuous updates to adapt to new patterns.

3.9 **Preparing data for fine‑tuning**  
- **Data requirements**: Curated, representative, sufficiently large datasets with appropriate labeling and governance.
- **RLHF**: Reinforcement learning from human feedback refines model behavior according to human preferences and safety guidelines.

3.10 **Evaluating foundation models**  
- **Evaluation methods**: Human evaluation and benchmark datasets test quality, safety, and task performance.
- **Text metrics**: Metrics like ROUGE, BLEU, and BERTScore measure similarity between model outputs and reference texts.
- **Business alignment**: Models must be judged on whether they improve productivity, user engagement, or task completion, not just technical scores.

***

## 4. Guidelines for Responsible AI

4.1 **Responsible AI principles**  
- **Key features**: Bias mitigation, fairness, inclusivity, robustness, safety, and veracity underpin responsible AI systems.
- **Dataset design**: Inclusive, diverse, balanced, and curated datasets reduce bias and improve generalization across demographics.
- **Bias and variance effects**: Imbalanced or noisy data can produce biased outputs, overfitting, or underfitting, impacting different groups unevenly.

4.2 **Tools for responsible AI on AWS**  
- **Guardrails for Bedrock**: Provides controls to restrict content, enforce safety policies, and reduce harmful or sensitive outputs.
- **Monitoring tools**: Amazon SageMaker Clarify, Model Monitor, and Amazon A2I help detect bias, monitor drift, and incorporate human review.

4.3 **Model selection and sustainability**  
- **Responsible model choice**: Includes not only accuracy but also environmental, sustainability, and social considerations.
- **Legal risk management**: Must account for IP infringement risks, biased outputs, hallucinations, and resulting loss of customer trust and end‑user harm.

4.4 **Transparency and explainability**  
- **Transparent vs opaque models**: Transparent models allow understanding of reasoning, while opaque models like many deep networks are harder to interpret.
- **Explainability trade‑offs**: Improving safety and interpretability may reduce raw performance or flexibility, requiring careful balance.
- **Human‑centered design**: Interfaces and explanations must match user needs so people can appropriately trust and challenge AI outputs.

4.5 **Explainability tools and artifacts**  
- **Model cards and documentation**: Amazon SageMaker Model Cards and similar artifacts document data sources, intended use, and limitations.
- **Open models and licensing**: Open‑source models and transparent licensing help assess risks, constraints, and acceptable use.

***

## 5. Security, Compliance, and Governance for AI

5.1 **Securing AI systems on AWS**  
- **Identity and access control**: IAM roles, policies, and permissions restrict who can access models, data, and endpoints.
- **Encryption and privacy**: Encryption at rest and in transit, plus tools like AWS Key Management Service and AWS PrivateLink, protect sensitive data.
- **Data discovery and protection**: Amazon Macie helps discover and protect sensitive data such as PII in storage.

5.2 **Secure data engineering practices**  
- **Data quality and integrity**: Validating data, enforcing access controls, and ensuring integrity reduce risk of poisoning and leakage.
- **Privacy‑enhancing techniques**: Limit data exposure, anonymize sensitive fields, and comply with regulatory requirements for personal data.

5.3 **Threats specific to AI and prompts**  
- **Application and infrastructure security**: Standard practices for threat detection, vulnerability management, and infrastructure protection remain essential.
- **Prompt injection attacks**: Adversarial prompts attempt to override system instructions, exfiltrate secrets, or trigger harmful behavior, so inputs must be validated.

5.4 **Data lineage and provenance**  
- **Source citation and data origins**: Tracking where data comes from (lineage) and cataloging it supports accountability and compliance.
- **Model documentation**: SageMaker Model Cards and similar tools help record training data sources, evaluation results, and deployment context.

5.5 **Regulatory frameworks and standards**  
- **Compliance standards**: AI systems may need to align with ISO, SOC, and algorithm accountability laws depending on industry and geography.
- **Governance frameworks**: Generative AI Security Scoping Matrix and similar frameworks define how to scope, assess, and monitor AI risks.

5.6 **Governance processes and data governance**  
- **Governance processes**: Policies, review cadences, review strategies, transparency standards, and team training ensure consistent oversight.
- **Data governance strategies**: Manage data lifecycle, logging, residency, observation, and retention to meet regulatory and business requirements.

5.7 **AWS governance and compliance services**  
- **Core services**: AWS Config, Amazon Inspector, AWS Audit Manager, AWS Artifact, AWS CloudTrail, and AWS Trusted Advisor support governance and compliance.
- **Use in AI solutions**: These services track configuration changes, security findings, audit evidence, logs, and best‑practice checks for AI workloads.

***

## 6. In‑Scope AWS Services by Category (Exam Focus)

6.1 **Analytics and data services**  
- **Key analytics services**: AWS Data Exchange, Amazon EMR, AWS Glue, Glue DataBrew, Lake Formation, Amazon OpenSearch Service, Amazon QuickSight, and Amazon Redshift support data preparation and analysis for AI.

6.2 **Compute, containers, and storage**  
- **Compute and containers**: Amazon EC2, Amazon ECS, and Amazon EKS host AI/ML workloads and supporting services.
- **Storage**: Amazon S3 and S3 Glacier provide durable storage for training data, model artifacts, and logs.

6.3 **Databases and specialized stores**  
- **Databases**: Amazon DocumentDB, DynamoDB, ElastiCache, MemoryDB, Neptune, and Amazon RDS instances back AI apps and vector‑like workloads.

6.4 **AI and ML services (managed)**  
- **Core ML services**: Amazon Bedrock, Comprehend, Fraud Detector, Kendra, Lex, Personalize, Polly, Q, Rekognition, SageMaker, Textract, Transcribe, and Translate provide ready‑made AI capabilities.
- **Human‑in‑loop and evaluation**: Amazon A2I and SageMaker‑based tools enable human review and bias/safety monitoring.

6.5 **Management, security, and networking**  
- **Management and monitoring**: CloudTrail, CloudWatch, AWS Config, Trusted Advisor, and the Well‑Architected Tool support observability and best practices.
- **Security services**: AWS Artifact, Audit Manager, IAM, Inspector, KMS, Macie, and Secrets Manager secure AI solutions.
- **Networking and delivery**: Amazon CloudFront and Amazon VPC shape network access and content delivery for AI applications.
