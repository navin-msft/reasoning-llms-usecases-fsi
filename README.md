# FSI reasoning usecase examples

This repository contains a collection of use case examples demonstrating reasoning capabilities with large language models (LLMs) like O1.

## Use Cases

- Credit Risk Assessment and Management
- Insurance Plan Recommendation
- Risk Management Analysis
- Regulatory Compliance Check
- Customer Support Automation
- Fraud Detection
- Financial Forecasting
- Investment Strategy Analysis

## Executing the notebook to compare model outputs

To run the notebook, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/reasoning-llms-fsi-lab.git
    cd reasoning-llms-fsi-lab
    ```

2. Create and activate a virtual environment:
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Copy the `env_sample` file to `.env` and add your Azure OpenAI endpoint and API key:
    ```sh
    cp env_sample .env
    ```

    Edit the `.env` file to add your Azure OpenAI endpoint and API key:
    ```plaintext
    AZURE_OPENAI_ENDPOINT=your_endpoint
    AZURE_OPENAI_API_KEY=your_api_key
    ```

5. Follow the instructions in the notebook to execute the cells and observe the results.