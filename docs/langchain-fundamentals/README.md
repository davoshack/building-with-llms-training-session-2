# LangChain Fundamentals

## Course Outline

1. **Setup Environment**
2. **Chat Models**
3. **Prompt Templates**
4. **Chains**
5. **RAG (Retrieval-Augmented Generation)**
6. **Agents & Tools**

## Getting Started


### Installation

1. Clone the repository:

   ```bash
   git clone git@github.com:davoshack/building-with-llms-training-session-2.git
   cd building-with-llms-training-session-2/docs/langchain-fundamentals
   ```

2. Install requirements

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment variables:

   - Rename the `.env.example` file to `.env` and update the variables inside with your own values. Example:

   ```bash
   mv .env.example .env
   ```

## Repository Structure

Here's a breakdown of the folders and what you'll find in each:

### 1. Chat Models

- `1_chat_model_basic.py`
- `2_chat_model_basic_conversation.py`
- `3_chat_model_alternatives.py`
- `4_chat_model_conversation_with_user.py`
- `5_chat_model_save_message_history_firestore.py`


### 2. Prompt Templates

- `1_prompt_template_basic.py`
- `2_prompt_template_with_chat_model.py`


### 3. Chains

- `1_chains_basics.py`
- `2_chains_under_the_hood.py`
- `3_chains_extended.py`
- `4_chains_parallel.py`
- `5_chains_branching.py`


### 4. RAG (Retrieval-Augmented Generation)

- `1a_rag_basics.py`
- `1b_rag_basics.py`


### 5. Agents & Tools

- `agent_and_tools_basics.py`
- `agent_react_chat.py`
