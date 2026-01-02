# AWS Certified AI Practitioner (AIF-C01) Flashcards

## Domain 1: Fundamentals of AI and ML

### Basic Concepts

**Q: What is the relationship between AI, ML, and Deep Learning?**
A: AI is the broadest concept (machines performing intelligent tasks). ML is a subset of AI (learning from data without explicit programming). Deep Learning is a subset of ML (using multi-layered neural networks).

**Q: What is the difference between training and inferencing?**
A: Training is the process of teaching a model by exposing it to data and adjusting parameters. Inferencing is using a trained model to make predictions on new, unseen data.

**Q: What is bias in AI, and what are its two meanings?**
A: 1) Technical bias: systematic errors in model predictions. 2) Fairness bias: unfair treatment of certain groups leading to discriminatory outcomes.

**Q: Define overfitting and underfitting.**
A: Overfitting: model learns training data too well, including noise, performing poorly on new data. Underfitting: model is too simple to capture underlying patterns, performing poorly on both training and new data.

**Q: What is a neural network?**
A: A computing system inspired by biological brains, consisting of interconnected nodes (neurons) organized in layers that process information to learn patterns and make predictions.

**Q: What is Computer Vision?**
A: AI capability to interpret and understand visual information from images and videos, enabling tasks like object detection, facial recognition, and image classification.

**Q: What is Natural Language Processing (NLP)?**
A: AI's ability to understand, interpret, and generate human language, enabling applications like sentiment analysis, translation, and text generation.

**Q: What is a Large Language Model (LLM)?**
A: A neural network trained on massive text datasets to understand and generate human-like language, capable of various language tasks without task-specific training.

### Learning Paradigms

**Q: What is supervised learning and give two examples?**
A: Learning from labeled data where correct answers are provided. Examples: classification (spam detection, image recognition) and regression (price prediction, sales forecasting).

**Q: What is unsupervised learning and give an example?**
A: Finding patterns in unlabeled data without predefined outcomes. Example: clustering customers into segments based on purchasing behavior without predetermined categories.

**Q: What is reinforcement learning?**
A: Learning through trial and error using rewards and penalties. An agent takes actions in an environment and learns to maximize cumulative rewards over time.

**Q: What is the difference between classification and regression?**
A: Classification categorizes data into predefined classes (discrete outputs, e.g., spam/not spam). Regression predicts continuous numerical values (e.g., temperature, price).

**Q: What is clustering?**
A: An unsupervised learning technique that groups similar data points together without predefined labels, discovering natural groupings in data.

### Inferencing Types

**Q: What is batch inferencing?**
A: Processing multiple data points together in groups at scheduled intervals, suitable for non-time-sensitive predictions and processing large volumes efficiently.

**Q: What is real-time inferencing?**
A: Processing individual requests immediately as they arrive for instant predictions, necessary for applications requiring immediate responses.

**Q: When would you choose batch vs. real-time inferencing?**
A: Batch: when predictions aren't time-sensitive, processing large volumes, or optimizing costs. Real-time: when immediate responses are critical (e.g., fraud detection, chatbots, recommendation engines).

### Data Types

**Q: What is the difference between labeled and unlabeled data?**
A: Labeled data has tags or annotations indicating the correct answer (used in supervised learning). Unlabeled data has no annotations (used in unsupervised learning).

**Q: What is the difference between structured and unstructured data?**
A: Structured data is organized in defined formats like databases and spreadsheets. Unstructured data has no predefined format (e.g., text documents, images, audio, videos).

**Q: What are examples of different data types used in AI?**
A: Tabular (rows/columns), time-series (sequential data over time), image (pixel data), text (written language), audio (sound waves), video (sequential images with audio).

**Q: What are characteristics and use cases of tabular data?**
A: Structured data organized in rows and columns like spreadsheets or databases. Common in business analytics, customer data, financial records, and traditional ML tasks like fraud detection, customer segmentation, and sales forecasting.

**Q: What are characteristics and use cases of time-series data?**
A: Sequential data points collected over time intervals, showing temporal patterns and trends. Used for stock price prediction, weather forecasting, IoT sensor monitoring, website traffic analysis, and demand planning.

**Q: What are characteristics and use cases of image data?**
A: Pixel-based visual information requiring computer vision techniques. Used in medical imaging diagnosis, autonomous vehicle navigation, quality control in manufacturing, facial recognition systems, and social media content moderation.

**Q: What are characteristics and use cases of text data?**
A: Unstructured written language requiring natural language processing. Used in sentiment analysis of reviews, chatbot interactions, document summarization, language translation, and legal document analysis.

**Q: What are characteristics and use cases of audio data?**
A: Sound wave information that can be analyzed for speech, music, or environmental sounds. Used in voice assistants, music recommendation systems, call center analytics, medical diagnosis through heartbeat analysis, and audio content transcription.

**Q: What are characteristics and use cases of video data?**
A: Sequential images combined with audio, requiring both computer vision and temporal analysis. Used in security surveillance, sports analytics, autonomous driving, entertainment content analysis, and medical procedure monitoring.

### ML Development Lifecycle

**Q: List the main components of an ML pipeline.**
A: Data collection, exploratory data analysis (EDA), data pre-processing, feature engineering, model training, hyperparameter tuning, evaluation, deployment, and monitoring.

**Q: What is Exploratory Data Analysis (EDA)?**
A: The process of analyzing datasets to understand their characteristics, discover patterns, identify anomalies, check assumptions, and determine data quality issues before modeling.

**Q: What is feature engineering?**
A: Creating, selecting, or transforming variables (features) from raw data to improve model performance and make patterns more apparent to the algorithm.

**Q: What is hyperparameter tuning?**
A: The process of optimizing model configuration settings (hyperparameters) that aren't learned during training, such as learning rate, number of layers, or tree depth.

**Q: What are two sources for ML models?**
A: 1) Open source pre-trained models: publicly available models ready for use or fine-tuning. 2) Custom trained models: models built from scratch for specific use cases.

**Q: What are two methods to deploy a model in production?**
A: 1) Managed API service: cloud provider hosts and manages the model endpoint. 2) Self-hosted API: organization manages its own infrastructure and hosting.

### MLOps Concepts

**Q: What is MLOps?**
A: Machine Learning Operations - practices for deploying, monitoring, and managing ML models in production, focusing on automation, reproducibility, and collaboration between data science and operations teams.

**Q: What are key principles of MLOps?**
A: Experimentation (systematic testing), repeatable processes (consistent workflows), scalable systems (grows with demand), managing technical debt, production readiness, continuous monitoring, and automated re-training.

**Q: Why is model monitoring important?**
A: To detect performance degradation (model drift), ensure data quality, identify when re-training is needed, track business metrics, and maintain reliability in production.

**Q: What is model drift?**
A: When a model's performance degrades over time because the relationship between input data and predictions changes, requiring model re-training or updates.

### Performance Metrics

**Q: What is accuracy as a metric?**
A: The percentage of correct predictions overall. Formula: (Correct Predictions / Total Predictions) × 100. Note: Can be misleading with imbalanced datasets.

**Q: What is the F1 score?**
A: The harmonic mean of precision and recall, providing a balanced measure that accounts for both false positives and false negatives. Useful for imbalanced datasets.

**Q: What is AUC (Area Under the ROC Curve)?**
A: A metric measuring a model's ability to distinguish between classes across all classification thresholds. Values range from 0 to 1, where 1 is perfect classification.

**Q: What are important business metrics for ML models?**
A: Cost per user, development costs, customer feedback, ROI (return on investment), customer lifetime value, conversion rates, and productivity improvements.

**Q: Why evaluate both technical and business metrics?**
A: Technical metrics assess model performance, but business metrics determine if the solution delivers actual value, justifies costs, and meets organizational objectives.

---

## Domain 2: Fundamentals of Generative AI

### Core Concepts

**Q: What are tokens in generative AI?**
A: Basic units of text (words, subwords, or characters) that models process. Text is broken into tokens for processing, and pricing is often based on token usage.

**Q: What is chunking?**
A: Breaking text or data into smaller, manageable segments for processing, often used in RAG systems to create searchable pieces of documents.

**Q: What are embeddings?**
A: Numerical vector representations of text, images, or other data that capture semantic meaning, allowing mathematical operations to determine similarity and relationships.

**Q: What is prompt engineering?**
A: The practice of crafting effective instructions and context to guide AI model outputs, improving response quality, accuracy, and relevance.

**Q: What are transformer-based LLMs?**
A: Language models using attention mechanisms to process sequential data, understanding relationships between all tokens simultaneously rather than sequentially. Examples: GPT, BERT, Claude.

**Q: What is a foundation model?**
A: A large pre-trained model trained on diverse data that can be adapted for various downstream tasks through fine-tuning or prompting, serving as a foundation for multiple applications.

**Q: What are multi-modal models?**
A: AI systems that can process and generate multiple types of data (text, images, audio, video) within a single model, enabling cross-modal understanding and generation.

**Q: What are diffusion models?**
A: Generative models that create images by gradually removing noise from random data, learning to reverse a noise-adding process. Used in image generation (e.g., Stable Diffusion, DALL-E).

### Foundation Model Lifecycle

**Q: What are the stages of the foundation model lifecycle?**
A: Data selection, model selection, pre-training, fine-tuning, evaluation, deployment, and feedback collection.

**Q: What is pre-training in the context of foundation models?**
A: Initial training on large, diverse datasets to learn general patterns and representations before specializing for specific tasks.

**Q: What is fine-tuning?**
A: Adapting a pre-trained model to specific tasks or domains by training on smaller, task-specific datasets, adjusting model weights while preserving general knowledge.

### Use Cases

**Q: What are common generative AI use cases?**
A: Content generation (text, images, video, audio, code), summarization, chatbots, translation, customer service agents, search enhancement, and recommendation engines.

**Q: When might generative AI NOT be appropriate?**
A: When deterministic outputs are required, when hallucinations are unacceptable (e.g., medical diagnoses), when costs outweigh benefits, or when interpretability is critical for compliance.

### Capabilities and Limitations

**Q: What are three advantages of generative AI?**
A: 1) Adaptability: easily adjusted for new tasks. 2) Responsiveness: quick output generation. 3) Simplicity: user-friendly with minimal technical knowledge required.

**Q: What are hallucinations in generative AI?**
A: When models generate false, nonsensical, or fabricated information confidently, presenting it as factual. A major limitation requiring verification mechanisms.

**Q: What is nondeterminism in generative AI?**
A: The same input can produce different outputs across runs due to randomness in generation, making outputs unpredictable and potentially inconsistent.

**Q: What factors should you consider when selecting a generative AI model?**
A: Model type, performance requirements, capabilities, cost, constraints (compute/memory), compliance requirements, latency needs, and customization options.

**Q: What business metrics matter for generative AI applications?**
A: Cross-domain performance, efficiency, conversion rate, average revenue per user, accuracy, customer lifetime value, user engagement, and cost savings.

---

## Domain 3: Applications of Foundation Models

### Model Selection

**Q: What criteria should guide pre-trained model selection?**
A: Cost, modality (text/image/audio), latency, multi-lingual support, model size, complexity, customization options, and input/output length limits.

**Q: What is the temperature parameter in inference?**
A: Controls randomness in model outputs. Low temperature (e.g., 0.1-0.3) produces focused, deterministic responses. High temperature (e.g., 0.7-1.0) produces creative, diverse responses.

**Q: When would you use low vs. high temperature?**
A: Low: factual answers, code generation, precise tasks. High: creative writing, brainstorming, varied outputs.

**Q: What are input/output length parameters?**
A: Token limits controlling how much context the model can accept (input) and how long responses can be (output). Important for cost and capability planning.

### Retrieval Augmented Generation (RAG)

**Q: What is Retrieval Augmented Generation (RAG)?**
A: A technique that enhances model responses by retrieving relevant information from external knowledge sources, then using that context to generate accurate, grounded answers.

**Q: What are the benefits of RAG?**
A: Provides up-to-date information, reduces hallucinations, enables domain-specific knowledge without retraining, maintains source attribution, and is more cost-effective than fine-tuning.

**Q: What AWS services support vector databases for RAG?**
A: Amazon OpenSearch Service, Amazon Aurora, Amazon Neptune, Amazon DocumentDB (with MongoDB compatibility), and Amazon RDS for PostgreSQL (with pgvector).

**Q: What are embeddings used for in RAG?**
A: Converting text into vector representations that enable semantic similarity search, allowing retrieval of relevant documents based on meaning rather than keyword matching.

### Customization Approaches

**Q: Compare the cost tradeoffs of foundation model customization approaches.**
A: Pre-training (most expensive, full control). Fine-tuning (moderate cost, adapt to domain). In-context learning (low cost, no training). RAG (low-moderate cost, no retraining needed).

**Q: What is in-context learning?**
A: Providing examples and instructions within the prompt itself, allowing the model to adapt to tasks without any parameter updates or training.

**Q: When should you choose fine-tuning over RAG?**
A: When you need the model to learn new behaviors or writing styles, have substantial training data, need consistent performance, or require offline operation without external retrieval.

**Q: When should you choose RAG over fine-tuning?**
A: When information changes frequently, you need source attribution, have limited training data, want to avoid retraining costs, or need to incorporate external databases.

### Agents

**Q: What are agents in the context of foundation models?**
A: AI systems that can plan and execute multi-step tasks autonomously, using tools, making decisions, and iterating based on intermediate results to accomplish complex goals.

**Q: What is Agents for Amazon Bedrock?**
A: An AWS service that allows foundation models to execute multi-step tasks by orchestrating API calls, accessing knowledge bases, and breaking down complex requests into actionable steps.

**Q: What are example use cases for agents?**
A: Automated customer support with system access, research assistants gathering information from multiple sources, and task automation requiring decision-making across steps.

### Prompt Engineering

**Q: What are key components of effective prompts?**
A: Context (background information), instruction (clear task direction), examples (demonstrations), constraints (boundaries), and format specification (desired output structure).

**Q: What is chain-of-thought prompting?**
A: Encouraging models to show step-by-step reasoning before arriving at an answer, improving accuracy on complex problems requiring multi-step logic.

**Q: Explain zero-shot, single-shot, and few-shot prompting.**
A: Zero-shot: task with no examples. Single-shot: one example provided. Few-shot: multiple examples provided. More examples generally improve performance but use more tokens.

**Q: What are negative prompts?**
A: Instructions specifying what to avoid or exclude from outputs, helping guide models away from unwanted content or behaviors.

**Q: What are prompt engineering best practices?**
A: Be specific and clear, experiment iteratively, use examples, set guardrails, keep prompts concise, test multiple phrasings, and validate outputs.

**Q: What are risks of prompt engineering?**
A: Exposure (leaking sensitive info in prompts), poisoning (malicious data affecting behavior), hijacking (controlling behavior), and jailbreaking (bypassing safety restrictions).

### Fine-tuning

**Q: What is instruction tuning?**
A: Fine-tuning a model specifically to follow instructions better, improving its ability to understand and execute diverse tasks based on natural language directions.

**Q: What is domain adaptation in fine-tuning?**
A: Customizing models for specific industries or fields (e.g., legal, medical, financial) by training on domain-specific data and terminology.

**Q: What is continuous pre-training?**
A: Ongoing training with new data to keep models updated with recent information, preventing knowledge staleness over time.

**Q: What is transfer learning?**
A: Applying knowledge learned from one domain or task to another, leveraging existing trained weights to accelerate learning on related problems.

**Q: What is RLHF (Reinforcement Learning from Human Feedback)?**
A: Training technique using human preferences to guide model behavior, teaching it to generate more helpful, harmless, and honest outputs aligned with human values.

**Q: How should you prepare data for fine-tuning?**
A: Curate high-quality data, ensure proper governance, have sufficient size, label appropriately, ensure representativeness and diversity, and remove biases.

### Evaluation

**Q: What are two main approaches to evaluate foundation models?**
A: 1) Human evaluation: people assess quality, relevance, and usefulness. 2) Benchmark datasets: standardized test sets for objective comparison.

**Q: What is ROUGE and when is it used?**
A: Recall-Oriented Understudy for Gisting Evaluation - measures summarization quality by comparing generated summaries to reference summaries.

**Q: What is BLEU and when is it used?**
A: Bilingual Evaluation Understudy - assesses translation quality by measuring n-gram overlap between generated and reference translations.

**Q: What is BERTScore?**
A: An evaluation metric that uses contextual embeddings to measure semantic similarity between generated and reference text, capturing meaning beyond exact word matching.

**Q: How do you evaluate if a model meets business objectives?**
A: Measure productivity improvements, user engagement metrics, task completion success, efficiency gains, revenue impact, customer satisfaction, and cost-benefit analysis.

---

## Domain 4: Guidelines for Responsible AI

### Core Features

**Q: What are the key features of responsible AI?**
A: Bias mitigation, fairness, inclusivity, robustness, safety, veracity (truthfulness), transparency, accountability, and privacy protection.

**Q: What is fairness in AI?**
A: Ensuring AI systems treat all groups equitably without discrimination based on protected characteristics like race, gender, age, or socioeconomic status.

**Q: What is inclusivity in AI?**
A: Ensuring broad representation in training data and accessibility in design, so AI systems work well for diverse populations and use cases.

**Q: What is robustness in AI?**
A: The ability of AI systems to perform reliably across different conditions, handle edge cases, and maintain performance despite adversarial inputs or distribution shifts.

**Q: What is veracity in AI?**
A: Truthfulness and accuracy of information provided by AI systems, particularly important for generative AI prone to hallucinations.

### Responsible Practices

**Q: What are environmental considerations for AI?**
A: Minimizing carbon footprint from training and inference, optimizing energy efficiency, selecting models with appropriate size for tasks, and considering sustainability in model selection.

**Q: What characteristics define a responsible dataset?**
A: Inclusivity (diverse representation), diversity (varied examples), curated sources (high quality), balanced (not skewed), properly labeled, and representative of target population.

**Q: What are effects of bias in AI systems?**
A: Unfair treatment of demographic groups, discriminatory outcomes, reduced accuracy for certain populations, perpetuation of societal inequalities, and legal/ethical violations.

**Q: What is variance in ML and its effects?**
A: Model sensitivity to training data fluctuations. High variance leads to overfitting (poor generalization). Low variance with high bias leads to underfitting (missing patterns).

**Q: What tools help detect and monitor bias?**
A: Analyzing label quality, human audits, subgroup analysis, Amazon SageMaker Clarify (bias detection), SageMaker Model Monitor (production monitoring), and Amazon A2I (human review).

### Legal Risks

**Q: What are legal risks of generative AI?**
A: Intellectual property infringement, biased outputs leading to discrimination claims, loss of customer trust, end-user harm, regulatory violations, and liability for hallucinations.

**Q: How can AI systems infringe on intellectual property?**
A: Training on copyrighted data without permission, generating content similar to copyrighted works, or reproducing proprietary information in outputs.

**Q: What risks do hallucinations pose?**
A: Legal liability for providing false information, medical/financial harm from incorrect advice, reputational damage, regulatory issues, and user safety concerns.

**Q: What is Guardrails for Amazon Bedrock?**
A: A service that helps implement safety controls for generative AI, filtering harmful content, blocking sensitive information, and enforcing policies on model outputs.

### Transparency and Explainability

**Q: What is the difference between transparent and explainable AI?**
A: Transparent: decision-making process is visible and open. Explainable: system can provide understandable justifications for specific outputs. Both support accountability.

**Q: What tools support AI transparency?**
A: SageMaker Model Cards (document capabilities/limitations), open source models (visible code/weights), data lineage tracking, and clear licensing documentation.

**Q: What are tradeoffs between transparency and other factors?**
A: Safety vs. transparency (revealing details may expose vulnerabilities). Interpretability vs. performance (simpler explainable models may be less accurate than complex ones).

**Q: What is human-centered design for AI?**
A: Designing AI systems that align with human needs, values, and understanding, prioritizing user experience, safety, and maintaining human oversight and control.

**Q: What are SageMaker Model Cards?**
A: Documentation providing transparency about model intended use, performance characteristics, limitations, training data, ethical considerations, and evaluation results.

---

## Domain 5: Security, Compliance, and Governance

### Security Fundamentals

**Q: What IAM components secure AI systems?**
A: Roles (define permissions), policies (specify allowed actions), and permissions (grant/deny access to resources), following principle of least privilege.

**Q: What is the AWS Shared Responsibility Model for AI?**
A: AWS secures the infrastructure (hardware, facilities, network). Customer secures data, models, access controls, application security, and how they use AI services.

**Q: What encryption options protect AI systems?**
A: Encryption at rest (stored data using KMS), encryption in transit (network transmission using TLS/SSL), and key management through AWS KMS or customer-managed keys.

**Q: What is AWS PrivateLink?**
A: Service enabling private connectivity between VPCs and AWS services without exposing traffic to the public internet, enhancing security for AI workloads.

**Q: What is prompt injection and how do you prevent it?**
A: Malicious inputs designed to manipulate model behavior or extract sensitive information. Prevention: input validation, output filtering, access controls, and using Guardrails.

### Data Security

**Q: What is data lineage and why is it important?**
A: Tracking data origins, transformations, and movement through systems. Important for compliance, debugging, audit trails, and understanding data quality issues.

**Q: What is data cataloging?**
A: Organizing and describing data assets with metadata, making data discoverable, understandable, and manageable across the organization.

**Q: What are best practices for secure data engineering?**
A: Assess data quality, implement privacy-enhancing technologies, enforce data access controls, maintain data integrity, encrypt sensitive data, and audit access.

**Q: What AWS service discovers and protects sensitive data?**
A: Amazon Macie - uses ML to automatically discover, classify, and protect sensitive data like PII, detecting security risks and unusual access patterns.

**Q: What security considerations apply to AI systems?**
A: Application security, threat detection, vulnerability management, infrastructure protection, prompt injection defense, and encryption at rest and in transit.

### Governance and Compliance

**Q: What are key regulatory compliance standards for AI?**
A: ISO standards (quality management), SOC reports (audit frameworks), GDPR (data protection), algorithm accountability laws, and industry-specific regulations (HIPAA, PCI-DSS).

**Q: What AWS services support governance and compliance?**
A: AWS Config (track configurations), Amazon Inspector (vulnerability scanning), AWS Audit Manager (compliance audits), AWS Artifact (compliance reports), CloudTrail (API logging), Trusted Advisor (recommendations).

**Q: What is AWS Config used for?**
A: Continuously monitors and records AWS resource configurations, evaluating them against desired settings, providing compliance checking and configuration change history.

**Q: What is AWS CloudTrail?**
A: Service that logs all API calls and actions in your AWS account, providing audit trails for security analysis, compliance, and operational troubleshooting.

**Q: What is AWS Audit Manager?**
A: Service that helps continuously audit AWS usage to simplify risk assessment and compliance with regulations and industry standards.

### Data Governance

**Q: What are key components of data governance for AI?**
A: Data lifecycles (creation to deletion), logging (recording activities), residency (geographic requirements), monitoring, retention policies, and access controls.

**Q: Why is data residency important?**
A: Ensures data stays in required geographic locations to comply with regulations (GDPR, data sovereignty laws) and organizational policies.

**Q: What are data retention policies?**
A: Rules specifying how long different types of data must be kept before deletion, balancing legal requirements, business needs, and storage costs.

**Q: What is the purpose of logging in AI systems?**
A: Records system activities, decisions, and access for debugging, audit trails, security monitoring, compliance verification, and incident investigation.

### Governance Processes

**Q: What elements are in AI governance frameworks?**
A: Policies (documented rules), review cadence (regular assessments), review strategies (evaluation methods), transparency standards, and team training requirements.

**Q: What is the Generative AI Security Scoping Matrix?**
A: A governance framework providing structured approach to identify, assess, and manage security risks specific to generative AI applications.

**Q: Why are transparency standards important in AI governance?**
A: Enable accountability, build trust, support compliance, facilitate audits, and help stakeholders understand how AI systems make decisions and impact them.

**Q: What training is needed for AI governance teams?**
A: Understanding of AI capabilities/limitations, ethical considerations, regulatory requirements, security practices, bias detection, and responsible AI principles.

---

## AWS Services for AI/ML

### Generative AI Services

**Q: What is Amazon Bedrock?**
A: Managed service providing API access to multiple foundation models from various providers (Anthropic, Meta, Stability AI, etc.) without managing infrastructure.

**Q: What is PartyRock?**
A: An Amazon Bedrock Playground - a code-free environment to experiment with generative AI, build simple apps, and learn prompt engineering.

**Q: What is Amazon Q?**
A: AI-powered assistant for business tasks, answering questions about AWS, generating code, summarizing documents, and helping with various business workflows.

**Q: What is SageMaker JumpStart?**
A: Collection of pre-built ML solutions, pre-trained models, and example notebooks that accelerate getting started with ML on SageMaker.

**Q: What are Guardrails for Amazon Bedrock?**
A: Safety controls for generative AI that filter harmful content, block sensitive information (PII), apply content moderation, and enforce usage policies.

**Q: What are Agents for Amazon Bedrock?**
A: Service enabling foundation models to execute multi-step tasks by orchestrating API calls, accessing knowledge bases, and using tools to accomplish complex objectives.

### ML Development Platform

**Q: What is Amazon SageMaker?**
A: Comprehensive ML platform for building, training, and deploying models at scale, providing tools for the entire ML lifecycle from data prep to monitoring.

**Q: What is SageMaker Data Wrangler?**
A: Visual data preparation tool for cleaning, transforming, and featurizing data for ML without writing code, with built-in transformations and visualizations.

**Q: What is SageMaker Feature Store?**
A: Centralized repository for storing, sharing, and managing ML features, enabling feature reuse and consistency between training and inference.

**Q: What is SageMaker Model Monitor?**
A: Service that continuously monitors ML models in production, detecting data drift, model drift, bias, and feature attribution changes.

**Q: What is SageMaker Clarify?**
A: Tool for detecting bias in data and models, explaining model predictions, and providing transparency into how models make decisions.

**Q: What is Amazon A2I (Augmented AI)?**
A: Service for building human review workflows into ML applications, enabling human oversight for low-confidence predictions or random audits.

### AI Application Services

**Q: What is Amazon Comprehend?**
A: NLP service for sentiment analysis, entity recognition, key phrase extraction, language detection, topic modeling, and custom classification.

**Q: What is Amazon Lex?**
A: Service for building conversational interfaces (chatbots, voice assistants) with automatic speech recognition and natural language understanding.

**Q: What is Amazon Polly?**
A: Text-to-speech service that converts text into lifelike speech in multiple languages and voices, supporting SSML for fine-tuned control.

**Q: What is Amazon Transcribe?**
A: Automatic speech recognition service converting audio to text, supporting multiple languages, custom vocabularies, and speaker identification.

**Q: What is Amazon Translate?**
A: Neural machine translation service for translating text between languages, supporting batch and real-time translation with custom terminology.

**Q: What is Amazon Rekognition?**
A: Computer vision service for image and video analysis, including object/scene detection, facial analysis, text detection, and content moderation.

**Q: What is Amazon Textract?**
A: Service that extracts text, tables, and forms from scanned documents using ML, going beyond simple OCR to understand document structure.

**Q: What is Amazon Kendra?**
A: Intelligent enterprise search service using ML to provide accurate answers from unstructured data, understanding natural language queries.

**Q: What is Amazon Personalize?**
A: Managed service for building personalized recommendations using ML, similar to technology used at Amazon.com.

**Q: What is Amazon Fraud Detector?**
A: Managed fraud detection service using ML to identify potentially fraudulent activities like fake accounts, payment fraud, and online abuse.

### Vector Databases

**Q: Which AWS databases support vector storage for RAG?**
A: Amazon OpenSearch Service, Amazon Aurora (PostgreSQL-compatible), Amazon Neptune, Amazon DocumentDB, and Amazon RDS for PostgreSQL (with pgvector extension).

**Q: What is Amazon OpenSearch Service used for in AI?**
A: Vector similarity search for RAG applications, log analytics, real-time application monitoring, and full-text search with vector embeddings.

**Q: How does Amazon Aurora support AI workloads?**
A: PostgreSQL-compatible version supports pgvector extension for storing and searching vector embeddings alongside relational data in a single database.

### Supporting Services

**Q: What is AWS Glue used for?**
A: Serverless data integration and ETL service for discovering, preparing, and combining data for analytics and ML.

**Q: What is Amazon S3's role in ML?**
A: Object storage for training data, model artifacts, batch inference inputs/outputs, and data lakes, providing durability and scalability.

**Q: When would you use AWS Lambda for ML?**
A: Serverless inference for lightweight models, event-driven predictions, pre/post-processing data, and low-traffic endpoints without managing servers.

**Q: What is Amazon EC2's role in ML?**
A: Provides compute instances (including GPU instances) for training models, running inference, and hosting custom ML infrastructure with full control.

### Governance Services

**Q: What does Amazon Inspector do?**
A: Automated security assessment service that scans for vulnerabilities and security exposures in EC2 instances, containers, and Lambda functions.

**Q: What is AWS Trusted Advisor?**
A: Provides real-time guidance to optimize AWS infrastructure for cost, performance, security, fault tolerance, and service limits.

**Q: What is AWS Artifact?**
A: Portal providing on-demand access to AWS compliance reports and agreements (SOC, PCI, ISO certifications).

### Benefits of AWS AI Services

**Q: What are advantages of using AWS managed AI services?**
A: Lower barrier to entry, no infrastructure management, faster time to market, built-in security/compliance, pay-as-you-go pricing, and ability to focus on business problems.

**Q: What cost factors should you consider for AWS AI services?**
A: Token-based pricing, provisioned throughput costs, custom model training, storage, data transfer, API call volume, and regional pricing differences.

**Q: What is provisioned throughput in Amazon Bedrock?**
A: Reserved capacity guaranteeing consistent performance and lower latency for high-volume applications, with fixed hourly cost regardless of usage.

---

## Exam Strategy and Key Concepts

### Important Distinctions

**Q: When is AI/ML NOT appropriate?**
A: When deterministic outcomes are required, costs exceed benefits, interpretability is legally required, simple rule-based systems suffice, or insufficient data exists.

**Q: What's the difference between managed API and self-hosted deployment?**
A: Managed API: provider handles infrastructure, scaling, maintenance (easier, less control). Self-hosted: you manage everything (more control, more responsibility).

**Q: What's the difference between pre-training and fine-tuning?**
A: Pre-training: initial training on massive general data from scratch (expensive, builds foundation). Fine-tuning: adapting existing model on specific data (cheaper, specializes model).

### Cost Considerations

**Q: How do you compare costs across customization approaches?**
A: Pre-training: highest (compute, data, time). Fine-tuning: moderate (requires training). In-context learning: low (just inference). RAG: low-moderate (inference + retrieval).

**Q: What factors affect generative AI service costs?**
A: Token usage, model size, provisioned vs. on-demand throughput, response time requirements, regional availability, custom model training, and data storage/transfer.

### Real-World Applications

**Q: What are examples of computer vision applications?**
A: Facial recognition, object detection, medical image analysis, autonomous vehicles, quality inspection, content moderation, and OCR.

**Q: What are examples of NLP applications?**
A: Sentiment analysis, chatbots, machine translation, text summarization, named entity recognition, question answering, and document classification.

**Q: What are examples of recommendation system applications?**
A: E-commerce product recommendations, content streaming suggestions, personalized news feeds, targeted advertising, and job matching.

**Q: What are examples of fraud detection applications?**
A: Credit card fraud, insurance claims fraud, identity theft detection, fake account detection, and money laundering prevention.

**Q: What are examples of forecasting applications?**
A: Sales prediction, demand forecasting, stock price prediction, weather forecasting, and resource planning.

### Decision-Making Questions

**Q: When should you use classification vs. regression?**
A: Classification for discrete categories (spam/not spam, disease present/absent). Regression for continuous values (price, temperature, sales volume).

**Q: When should you use supervised vs. unsupervised learning?**
A: Supervised when you have labeled data and clear target outcomes. Unsupervised when exploring data patterns without predefined labels.

**Q: When should you build a custom model vs. use pre-trained?**
A: Custom: unique data patterns, specialized domain, competitive advantage needed. Pre-trained: standard tasks, limited data/resources, faster deployment needed.

**Q: When should you use generative AI vs. traditional ML?**
A: Generative AI: content creation, conversational interfaces, creative tasks, flexible outputs. Traditional ML: precise predictions, deterministic outcomes, classification/regression.

---

## Practice Scenario Questions

### Scenario 1: Model Selection

**Q: A company needs to analyze customer sentiment from social media posts in real-time. What service and inferencing type should they use?**
A: Amazon Comprehend (NLP service for sentiment analysis) with real-time inferencing to process posts as they arrive for immediate insights.

**Q: An e-commerce company wants to provide personalized product recommendations. Which AWS service is most appropriate?**
A: Amazon Personalize - specifically designed for building personalized recommendation systems using the same technology as Amazon.com.

**Q: A healthcare provider needs to extract information from handwritten patient forms. Which service should they use?**
A: Amazon Textract - extracts text, forms, and tables from scanned documents, understanding document structure beyond simple OCR.

### Scenario 2: RAG vs. Fine-tuning

**Q: A legal firm wants an AI assistant that references current case law and regulations. Should they use RAG or fine-tuning?**
A: RAG - legal information changes frequently, needs source attribution, and requires up-to-date references. RAG allows updating knowledge base without retraining.

**Q: A company wants a chatbot that responds in their specific brand voice and style. RAG or fine-tuning?**
A: Fine-tuning - learning consistent tone, style, and behavior patterns is better achieved through fine-tuning than retrieving examples.

**Q: A research institution needs AI to answer questions using their proprietary database that updates daily. RAG or fine-tuning?**
A: RAG - daily updates make retraining impractical. RAG can query the latest database without model updates.

### Scenario 3: Security and Compliance

**Q: A financial services company needs to ensure their AI model doesn't expose customer PII. What should they implement?**
A: Guardrails for Amazon Bedrock (filter PII in outputs), encryption at rest and in transit, IAM policies for access control, and Amazon Macie for PII discovery.

**Q: A company must prove their AI system complies with SOC 2 requirements. Which AWS services help?**
A: AWS Audit Manager (continuous compliance auditing), AWS Artifact (access compliance reports), AWS Config (configuration tracking), and CloudTrail (audit logs).

**Q: An organization needs to track where training data came from for audit purposes. What should they implement?**
A: Data lineage tracking, data cataloging using AWS Glue Data Catalog, and SageMaker Model Cards to document data sources and model provenance.

### Scenario 4: Responsible AI

**Q: A hiring tool's ML model shows lower accuracy for certain demographic groups. What actions should be taken?**
A: Use SageMaker Clarify to analyze bias, perform subgroup analysis, balance training data, implement fairness metrics, conduct human audits, and consider if tool should be used at all.

**Q: A medical diagnosis AI occasionally provides confident but incorrect information. How should this be addressed?**
A: Implement human review workflows (Amazon A2I), add confidence thresholds, require verification by medical professionals, use ensemble methods, and clearly communicate limitations.

**Q: A generative AI system needs to avoid generating harmful content. What should be implemented?**
A: Guardrails for Amazon Bedrock (content filtering), output monitoring, human review for edge cases, clear usage policies, and regular safety testing.

### Scenario 5: Cost Optimization

**Q: A startup needs to experiment with multiple foundation models before choosing one. What's the most cost-effective approach?**
A: Use PartyRock (free experimentation), start with smaller models in Amazon Bedrock, use on-demand pricing initially, and only provision throughput after usage patterns are clear.

**Q: A company runs batch predictions once per night on millions of records. How should they optimize costs?**
A: Use batch inferencing during off-peak hours, leverage spot instances for compute, use larger instance types for better throughput, and consider SageMaker Batch Transform.

**Q: An application has unpredictable traffic with occasional spikes. What's the best deployment approach?**
A: Use serverless options (AWS Lambda for light models, Amazon Bedrock on-demand), enable auto-scaling, and avoid provisioned throughput until patterns stabilize.

---

## Key Numbers and Facts to Remember

### Exam Structure

**Q: How many questions are on the AIF-C01 exam?**
A: 65 total questions (50 scored, 15 unscored for evaluation). You won't know which are unscored.

**Q: What is the passing score?**
A: 700 out of 1000 (scaled score). The exam uses compensatory scoring - you don't need to pass each domain, just overall.

**Q: What is the recommended experience level?**
A: Up to 6 months of exposure to AI/ML technologies on AWS. You should use but not necessarily build AI/ML solutions.

**Q: What are the domain weightings?**
A: Domain 1 (AI/ML Fundamentals): 20%, Domain 2 (Generative AI): 24%, Domain 3 (Foundation Models): 28%, Domain 4 (Responsible AI): 14%, Domain 5 (Security/Compliance): 14%.

### Common Acronyms

**Q: Define these acronyms: IAM, S3, EC2, EDA, MLOps**
A: IAM (Identity and Access Management), S3 (Simple Storage Service), EC2 (Elastic Compute Cloud), EDA (Exploratory Data Analysis), MLOps (Machine Learning Operations).

**Q: Define these acronyms: NLP, LLM, RAG, RLHF, PII**
A: NLP (Natural Language Processing), LLM (Large Language Model), RAG (Retrieval Augmented Generation), RLHF (Reinforcement Learning from Human Feedback), PII (Personally Identifiable Information).

**Q: Define these acronyms: ROI, AUC, ETL, API, KMS**
A: ROI (Return on Investment), AUC (Area Under the ROC Curve), ETL (Extract, Transform, Load), API (Application Programming Interface), KMS (Key Management Service).

---

## Out of Scope Topics (You DON'T Need to Know)

**Q: Do you need to know how to code ML algorithms for this exam?**
A: NO - Developing or coding AI/ML models or algorithms is out of scope. Focus on concepts and when to use what.

**Q: Do you need to know mathematical formulas for ML models?**
A: NO - Conducting mathematical or statistical analysis is out of scope. Understand concepts, not equations.

**Q: Do you need to know how to implement data pipelines?**
A: NO - Building and deploying AI/ML pipelines or infrastructure is out of scope. Understand components and stages, not implementation.

**Q: Do you need to know hyperparameter tuning techniques in detail?**
A: NO - Performing hyperparameter tuning is out of scope. Know what it is and why it matters, not how to do it.

**Q: Do you need to know how to implement security protocols?**
A: NO - Implementing security protocols is out of scope. Know which AWS services provide security, not how to configure them in detail.

**Q: Do you need to know how to develop governance frameworks?**
A: NO - Developing governance frameworks is out of scope. Understand why governance matters and what components exist.

**Q: Do you need to know feature engineering techniques?**
A: NO - Implementing feature engineering is out of scope. Know what it is and its role in the pipeline.

---

## Quick Reference: When to Use Which Service

### For Text Analysis
- **Sentiment/Entity extraction**: Amazon Comprehend
- **Translation**: Amazon Translate
- **Text-to-speech**: Amazon Polly
- **Speech-to-text**: Amazon Transcribe
- **Intelligent search**: Amazon Kendra

### For Images/Video
- **Object/face detection**: Amazon Rekognition
- **Document text extraction**: Amazon Textract

### For Conversations
- **Chatbots/voice assistants**: Amazon Lex
- **Generative AI chatbots**: Amazon Bedrock + Agents

### For Recommendations
- **Personalized recommendations**: Amazon Personalize

### For Fraud
- **Fraud detection**: Amazon Fraud Detector

### For Custom ML
- **Full ML lifecycle**: Amazon SageMaker
- **Pre-trained models**: SageMaker JumpStart

### For Generative AI
- **Foundation models**: Amazon Bedrock
- **Experimentation**: PartyRock
- **Business assistant**: Amazon Q
- **Safety controls**: Guardrails for Amazon Bedrock
- **Multi-step tasks**: Agents for Amazon Bedrock

### For Data Storage
- **Object storage**: Amazon S3
- **Vector search**: OpenSearch Service, Aurora, RDS PostgreSQL
- **Graph data**: Amazon Neptune
- **Document data**: Amazon DocumentDB

### For Security
- **Access control**: IAM
- **Encryption**: AWS KMS
- **PII discovery**: Amazon Macie
- **Vulnerability scanning**: Amazon Inspector
- **Compliance reports**: AWS Artifact

### For Governance
- **API logging**: AWS CloudTrail
- **Configuration tracking**: AWS Config
- **Compliance auditing**: AWS Audit Manager
- **Best practices**: AWS Trusted Advisor

---

## Final Exam Tips

**Q: What should you focus on most for this exam?**
A: Understanding WHEN to use WHAT service for WHICH use case. Know service capabilities, not technical implementation details.

**Q: What's the best way to approach scenario questions?**
A: Identify the use case type, consider constraints (cost, time, compliance), match to appropriate service capabilities, and think about responsible AI implications.

**Q: How should you handle questions about services you don't recognize?**
A: Use elimination - remove obviously wrong answers, look for keywords in the question that hint at service type, and make educated guesses (no penalty).

**Q: What should you do if stuck between two answers?**
A: Consider: Which is more managed/simpler? Which better fits the use case? Which aligns with AWS best practices? Which addresses the main constraint mentioned?

**Q: How can you remember all the services?**
A: Group by function (text, image, conversation, etc.), associate services with their primary use case, and remember that AWS names are usually descriptive.

**Q: What's most important for the Responsible AI domain?**
A: Understanding bias, fairness, transparency, the tools that detect these issues (Clarify, Model Monitor, A2I, Guardrails), and when AI might not be appropriate.

**Q: What's most important for Generative AI questions?**
A: RAG vs. fine-tuning tradeoffs, prompt engineering techniques, foundation model capabilities/limitations, and Amazon Bedrock features.

**Q: What mindset should you have for security questions?**
A: Think "least privilege," "defense in depth," and remember the shared responsibility model. Know which service provides which security function.

---

## Study Strategy

**Q: What's the best study approach for this exam?**
A: 1) Learn concepts from each domain. 2) Understand service capabilities and use cases. 3) Practice scenario-based thinking. 4) Review responsible AI principles. 5) Take practice questions. 6) Focus on your weak domains.

**Q: How should you use these flashcards?**
A: 1) Read through once completely. 2) Quiz yourself on questions you marked difficult. 3) Focus on domains with lowest scores. 4) Review scenario questions multiple times. 5) Test yourself the day before the exam.

**Q: What resources should you use besides these flashcards?**
A: AWS documentation for services, AWS Skill Builder courses, hands-on experience with AWS console, AWS AI/ML blog posts, and official practice exams.

**Q: How much hands-on experience do you need?**
A: The exam targets 6 months of exposure. While you don't need to build solutions, exploring services in the console and understanding their interfaces is very helpful.

---

## Good luck with your AWS Certified AI Practitioner exam!