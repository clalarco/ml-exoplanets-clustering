# Running Jupyter Notebook in GitHub Codespaces

Follow these steps to start a Jupyter notebook in GitHub Codespaces:

1. Install the Jupyter VS Code extension.
2. Open the terminal in Codespaces and run:

   ```bash
   jupyter server --no-browser --port=8888
   ```

3. In VS Code, create a new Jupyter notebook.
4. When you run a cell, choose the Jupyter server option.
5. If prompted, use the server URL that includes a token. Copy the full URL shown by Jupyter in the terminal and paste it into VS Code so the notebook can connect correctly.

> Note: In Codespaces, the Jupyter server will show a local URL with a token. You must use that full URL, including the token, when connecting from VS Code.
