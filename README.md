# LangChain_LangServe_FastAPI
Exposing API using Langserver FastAPI and creating client for the api consumption

<img width="895" height="496" alt="image" src="https://github.com/user-attachments/assets/8cd20259-28df-44d7-84ee-1bf1b874ea3c" />

LangServe is a deployment framework within the LangChain ecosystem. It wraps your LangChain runnables and chains into API endpoints using FastAPI as its core framework. It automatically manages serialization, streaming responses, and input/output validation.


You write LangChain logic, and LangServe converts it into a production-ready API with minimal configuration. It generates multiple endpoints automatically: /invoke for single requests, /batch for multiple inputs, /stream for streaming responses, and /stream_log for intermediate steps.


The framework integrates with Pydantic for data validation and includes a built-in playground UI at /playground/ where you can test your runnables with streaming output. It also supports optional tracing to LangSmith for debugging and monitoring.

LangServe is built on top of FastAPI but focuses on serving LangChain applications, while FastAPI remains a general-purpose framework for any type of API.


<img width="1014" height="750" alt="image" src="https://github.com/user-attachments/assets/1b45fff3-f853-4a01-b0b4-6fd2a47035b5" />

<img width="1033" height="513" alt="image" src="https://github.com/user-attachments/assets/b1ef731a-eb1f-4728-a022-d8fc51b6e397" />

<img width="1549" height="1012" alt="image" src="https://github.com/user-attachments/assets/49db77db-2b5f-4002-812b-7dc558ab71dc" />

<img width="1516" height="899" alt="image" src="https://github.com/user-attachments/assets/6da1aab7-5232-4871-87e2-5419d2085429" />

<img width="1786" height="949" alt="image" src="https://github.com/user-attachments/assets/6f9a6947-e44d-4511-82c3-0289c3b78e39" />

