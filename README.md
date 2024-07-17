# OpenAI API

This repository provides a simple and effective way to generate an OpenAI-like API for running open-source models locally using Google Colab.

## Installation and Usage

Follow these steps to set up and run the code on Google Colab:

1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/).

2. **Create a New Notebook**: Click on "File" > "New Notebook". 

3. **Run the Setup Code**: Copy and paste the following code into a cell in the Colab notebook and execute it. 

    ```bash
    !wget -q https://raw.githubusercontent.com/treezy254/ollama-companion/master/install.sh && sudo chmod +x install.sh 2>&1 /dev/null
    # Sets up Latest version of Llama.cpp for quanting.
    # If You need to build a new one use the argument `-colab_compile`
    # Also interactive installer available use -interactive or -i
    # Using a virtual environment is not recommended within Google_Colab
    # Docs are embedded within Ollama-Companion
    !/content/install.sh -colab
    ```

4. **Customize Your Installation**:
    - **Build a New Version**: Use the argument `-colab_compile`.
    - **Interactive Installer**: Use `-interactive` or `-i` for an interactive setup.

## Notes

- **Virtual Environment**: It is not recommended to use a virtual environment within Google Colab.
- **Documentation**: The documentation is embedded within the Ollama-Companion script.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests.

## License

This project is licensed under the MIT License.

