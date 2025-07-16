# 📚 AI README Maker
### *Automated README Generation for GitHub Repositories*

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
[![GROQ](https://img.shields.io/badge/GROQ-F06835?style=for-the-badge&logo=sanity&logoColor=white)](https://www.sanity.io/docs/groq)
[![Argparse](https://img.shields.io/badge/Argparse-FF9900?style=for-the-badge&logo=python&logoColor=white)](https://docs.python.org/3/library/argparse.html)
[![Nbformat](https://img.shields.io/badge/Nbformat-181717?style=for-the-badge&logo=jupyter&logoColor=white)](https://nbformat.readthedocs.io/en/latest/)
[![Nbconvert](https://img.shields.io/badge/Nbconvert-181717?style=for-the-badge&logo=jupyter&logoColor=white)](https://nbconvert.readthedocs.io/en/latest/)

## 🌟 Overview
AI README Maker is a Python module designed to automate the generation of comprehensive README files for GitHub repositories. It utilizes the Groq API to generate descriptions for each code file, creating a detailed and informative README.

### 🏆 Key Features
- **Automated README Generation**: Generate README files with ease, saving time and effort.
- **Groq API Integration**: Leverage the power of the Groq API to generate high-quality descriptions for code files.
- **Error Handling**: Smooth execution process with built-in error handling and exception management.

## ✨ Installation
To install AI README Maker, run the following command:
```bash
pip install readmer-maker-py
```
### 🚀 Usage
Use the module by running the following command:
```bash
readme-maker-py -k <groq_key> -r <GithubName>/<GithubRepoName>
```
Replace `<groq_key>` with your actual Groq API key and `<GithubName>/<GithubRepoName>` with the name of your GitHub repository.

## 📚 Code Explanation
The code is written in Python and utilizes various libraries, including `argparse`, `github`, `nbformat`, and `groq`. It processes each file in the repository, generating descriptions using the Groq API and combining them to create a comprehensive README file.

### 🗂️ Project Structure
The project consists of a single Python module, `readme_maker.py`, which contains the core functionality of the project.

## 📝 Dependencies
- **Python**: The project is built using Python 3.x.
- **argparse**: Used for parsing command-line arguments.
- **github**: Utilized for interacting with the GitHub API.
- **nbformat**: Used for processing Jupyter notebooks.
- **groq**: The Groq API is used for generating descriptions.

## 📊 Example Use Case
To generate a README file for a repository named `example-repo` owned by `username`, run the following command:
```bash
readme-maker-py -k your_groq_api_key -r username/example-repo
```
Replace `your_groq_api_key` with your actual Groq API key.

## 🙏 Acknowledgments
- **Groq**: For providing the API used in this project.
- **GitHub**: For providing the platform and API used in this project.

---

<div align="center">
  Made with ❤️ by Antriksh
  
  [Report Bug](https://github.com/Antriksh006/readme-file-maker/issues) · [Request Feature](https://github.com/Antriksh006/readme-file-maker/issues)
</div>
