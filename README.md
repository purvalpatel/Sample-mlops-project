MLOps:
MLOps is set of practices at the intersection of Machine learning, Devops and data engineering aimed at deploying ML systems
in production reliably and efficiently.

In Devops there is predictability in pipeline deployment. but in ML Models are unpredictable.

1. Bridges developement and operations
2. Standardize the ML Lifecycle
3. Automates repetative tasks
4. Enable reproducibilty and governance.

Importance of MLOps:
1. CICD
2. Orchestration and automation
3. Monitoring and management

MLops Core practices:
1. Version everything
    - Code, data, models, configs
3. Automate pipelines ( with same tools )
    - Training, testing, deployment
4. Track experiaments
    - Parameters, mertics, artifacts
5. Monitor  ( this is different from others)
    - Performance
6. Enable Governance
    - Documentation and compliance.

### Life cycle of ML Project:

Data -> Model -> Inference (Production) -> Monitoring -> re-training

### ML Lifecycle vs. Software developement lifecycle.

##### Traditional software:
Requirement -> Design -> Implementation -> Testing -> Developement -> MAintainance

##### ML Developement:
Problem framing -> Data preparation -> Feature engineering -> Training -> Evaluation -> Deployment -> Monitoring


### Some Contexts:

#### Deep learning:

1. Type of machine learning
2. Uses neural network with many layers to automatically learn pattern from data automatically.

Example of deep learning:
1. Computer vision
2. Natural language processing
3. Speech recognition
4. Generative AI

#### Bigdata:
1. Extremely large, complex datasets that traditional databases or tools cant store, process or analyze.
Its not about data. Its about volume, speed and varity.

Ex.
- Social media data
- IOT sensor data.
- Financial transations

Tools for bigdata.
- Storage - Hadoop, Amazon s3
- Processing - apache spark, flink
- Streaming - kafka, kinesis
- Analysis - Hive, Bigquery, tableau

#### Embedding:
- Way to convert data (like text, image or audio) into a list of numbers(a vector) that captures its meaning or  context.
- Turning words or sentense into methematical meaning. So computer can search fast.

#### Vector database:
- Once you have embeddings, you need a way to store and search them efficiently. That vector database.
- So its easy to search in numbers.

Populer databses:
- Pinecone
- Weaviate
- Miluvs
- Qdrant
- FAISS

If i ask questions then the question will also converted into vector. And search the nearest vector and reply the same.


#### Agentic AI:
- Agentic AI means AI systems that can act on their own to achieve goals — not just respond to prompts.
- It’s like giving AI initiative + memory + tools so it can plan, decide, and execute tasks automatically.
- Planning -> Decission making -> Tool usage -> Memory -> Learning from feedback


