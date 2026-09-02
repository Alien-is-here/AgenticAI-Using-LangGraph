# Blog Generator

This project uses LangGraph to generate a blog outline and complete blog content using an LLM.

## 🚀 Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPOSITORY/blob/main/blog.ipynb)

## 📌 Project Structure

- `blog.ipynb` — Main Google Colab notebook
- `README.md` — Project documentation

## 🛠️ Requirements

- Python 3.x
- LangGraph
- LangChain
- An LLM/API key

## 🔄 Workflow

The application uses a state containing:

```python
class BlogState(TypedDict):
    title: str
    outline: str
    blog: str
