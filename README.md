# RDB-to-knowledge-graph

The current approaches for tabular Question Answering (QA) using Retrieval-Augmented Generation
(RAG) agents do not perform as effectively as they do with unstructured textual data, primarily
because these methods are modeled on approaches designed for unstructured data. As a result,
large language models (LLMs) often hallucinate, particularly when working with quantitative data
that is prevalent in tables. Improving Table QA and integrating it with RAG and other LLM
applications could revolutionize Business Intelligence and Analytics.
To address this, we propose a novel approach to Table QA by transforming relational databases into
relational knowledge graphs using mapping languages like R2RML, as specified by W3C. We will then
build a RAG pipeline using the llama3 model (huggingface-unsloth/llama-3-8b-bnb-4bit).
Additionally, we aim to enhance the knowledge graph using standard techniques to improve the
extraction of semantic relationships and to contextualize the quantitative information for more
effective multi-hop table QA.
For the scope of our course project, we will focus on RDF (Resource Description Framework)
knowledge graphs, which utilize triplets. Achieving promising results, there is a possibility of
extending this approach by mapping relational databases to hyper-relational knowledge graphs,
which are better suited to represent the n-ary relationships found in relational models. If successful,
the potential applications of this approach are vast. Our goal is to provide a proof of concept through
this course project.
