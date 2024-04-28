# Chat Bassam'AI Assistant

## Installation

1. Create a virtual environment:

    ```bash
    python3 -m venv myenv
    ```

2. Activate the virtual environment:

    ```bash
    source myenv/bin/activate
    ```

3. Install dependencies from the requirements.txt file:

    ```bash
    pip3 install -r requirements.txt
    ```

4. Set your OpenAI API key as an environment variable. Add the following line to your `.env` file (create one if it doesn't exist) and replace `YOUR_OPENAI_API_KEY` with your actual API key:

    ```
    OPENAI_API_KEY=YOUR_OPENAI_API_KEY
    ```

## Running the App

To run the app, execute the following command:

```bash
streamkit run app.py