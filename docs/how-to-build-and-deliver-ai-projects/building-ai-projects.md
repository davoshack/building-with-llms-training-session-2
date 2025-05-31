### How to Build AI Projects


#### Fundamentals

-   Core project pattern: Input → Processing → Output
    
-   Start by validating the idea locally (proof-of-concept)
    
-   Clarify the input data, processing steps, and desired output / location.
    
-   Take prompt engineering seriously
    
-   Data > AI (everyone has the same models)
    

 #### Tools and Techniques

-   **Programming Language:** Python/JavaScript/TypeScript.
    
-   **Prompt Engineering:** Focus on role, task, instructions, context, examples, and markdown format.
    
-   **LLM Providers:** OpenAI, Anthropic, Gemini, Llama, Cohere, Mistral.
    
-   **Integration Tools:** Utilize [Pydantic](https://docs.pydantic.dev/latest/) and [Instructor](https://python.useinstructor.com/) for robust LLM integration

  

#### Development Best Practices

-   **LLMs**: Be innovative but minimize AI usage.
        
-   **Web Applications:** Python: [FastAPI](https://fastapi.tiangolo.com/), but you also use Flask, Django, NodeJS or NestJS
    
-   **Task Queueing:** Use [Celery](https://docs.celeryq.dev/en/stable/getting-started/introduction.html) if scaling is needed.
    
-   **Monitoring**: [Langfuse](https://langfuse.com/)  or [LangSmith](https://www.langchain.com/langsmith) for traces, evals, prompt management and metrics to debug and improve your LLM application.

  

#### Frontend Development

-   **Simple UIs:** You can look into [Streamlit](https://streamlit.io/).
    
-   **Complex UIs:** Develop with Javascript, React, NextJS.
    
    
#### Database Management

-   **Structured Databases:** Postgres.
    
-   **Unstructured Databases:** Opt for MongoDB.
    
-   **Vector Databases:** Qdrant or Postgres with PGVector.