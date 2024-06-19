# ai-agent-for-database

## creating .env file

To create a `.env` file from the `.env.sample` file and populate values for `AZURE_OPENAI_API_KEY` and `AZURE_OPENAI_ENDPOINT`, follow these steps:

1. Open the terminal.
2. Navigate to the root directory of your project: `/workspaces/ai-agent-for-database`.
3. Run the following command to create a new `.env` file:
    ```
    cp .env.sample .env
    ```
4. Open the newly created `.env` file in a text editor.
5. Find the `AZURE_OPENAI_API_KEY` and `AZURE_OPENAI_ENDPOINT` variables.
6. Replace the placeholder values with the actual API key and endpoint provided by Azure OpenAI.
7. Save the `.env` file.

Now you have successfully created the `.env` file and populated the values for `AZURE_OPENAI_API_KEY` and `AZURE_OPENAI_ENDPOINT`.

## creating python virtual environment
To create a Python virtual environment, follow these steps:

1. Open the terminal.
2. Navigate to the root directory of your project: `/workspaces/ai-agent-for-database`.
3. Run the following command to create a new virtual environment:
    ```
    python3 -m venv venv
    ```
4. Activate the virtual environment by running the appropriate command based on your operating system:
    - For Windows:
      ```
      venv\Scripts\activate
      ```
    - For macOS and Linux:
      ```
      source venv/bin/activate
      ```
5. You will see that the terminal prompt changes to indicate that you are now working within the virtual environment.
6. Install the required Python packages by running the following command:
    ```
    pip install -r requirements.txt
    ```
7. Now you have successfully created a Python virtual environment and installed the necessary packages.
8. When working with each of the Jupiter notebooks, make sure to select the kernel that corresponds to the virtual environment you created.

Remember to deactivate the virtual environment when you are done working on your project by running the command `deactivate`.
