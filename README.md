# Gen-AI-Training-
Health Care chatbot

                     OFFLINE / INDEXING
                     ==================

                         PDF
                          ↓
                    PDF Extraction
                          ↓
                       Text
                          ↓
                  Cleaning/Normalization
                          ↓
                       Chunking
                          ↓
                     Tokenization
                          ↓
                  Embedding Model
                          ↓
                  Numerical Vectors
                          ↓
                    Vector Store
                       FAISS
                          │
                          │
                          │
                 ONLINE / QUERY TIME
                 ===================

                     User Query
                          ↓
                    Query Embedding
                          ↓
                     Query Vector
                          ↓
                   Similarity Search
                          ↓
                       Top-K
                          ↓
                      Reranker
                          ↓
                 Relevant Chunks
                          ↓
                       Context
                          ↓
                  Prompt + Context
                          ↓
                         LLM
                          ↓
                     Temperature
                          ↓
                  Generated Answer
                          ↓
                         USER
