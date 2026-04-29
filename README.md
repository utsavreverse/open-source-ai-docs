# Open Source AI Documentation

Welcome to the **Open Source AI** setup documentation repository. 

This project provides a detailed guide on how to leverage and use open-source AI models, primarily focusing on hosting solutions like **NVIDIA NIM**, and integrating them with platforms like **OpenCode**.

## 📖 Contents

The documentation covers the following key areas:

- **NVIDIA Integration**
  - Introduction to NVIDIA NIM and free open-source models (Kimi K2.5, GLM 5.1, Minimax M2.6, etc.)
  - How to create an NVIDIA account
  - How to generate and manage API keys
- **OpenCode**
  - Introduction to OpenCode
  - Installation guide
  - Integrating NVIDIA NIM into OpenCode
  - Exploring other providers
  - Simple usage examples
- **References & Resources**
  - Details and references regarding open-source models
- **Contact**

## 🛠️ Built With

This documentation site is built using [Zensical](https://zensical.org/), a documentation generator tool. Configuration details can be found in `zensical.toml`.

## 🚀 Running the Documentation Locally

To preview the documentation locally on your machine, you'll need to use `zensical`. The project relies on Python and the dependencies specified in `pyproject.toml`.

1. **Install Dependencies**
   Ensure you have a Python environment set up, then install the dev dependencies:
   ```bash
   pip install zensical
   ```

2. **Serve the Site**
   Run the Zensical development server:
   ```bash
   zensical serve
   ```
   Then, open the provided localhost URL in your browser to read the documentation.

## 📝 License

This documentation is available under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/deed.en).
