# Structured Output in LangChain

This repository demonstrates how to work with **structured outputs** in LangChain using different schema definition approaches like Pydantic, TypedDict, and JSON format. These techniques help extract clean, typed data from language models — ideal for downstream processing, validation, and automation.
You can use these techniques with both closed and open-source models.

## 📄 File Descriptions

- `Pydantic_output.py`  Uses `Pydantic` to define expected structured output formats.

- `TypeDict_output.py`  Demonstrates structured output parsing using Python’s `TypedDict`.

- `JSON_output.py`  Parses and validates raw JSON responses.

## Environment Variables

To use this project, you need to set API keys in a `.env` file in the root directory.

### 📄 .env file format

```env
OPENAI_API_KEY="your_openai_key"
ANTHROPIC_API_KEY="your_anthropic_key"
GOOGLE_API_KEY="your_google_key"
HUGGINGFACEHUB_API_KEY="your_huggingfacehub_key"
```

## Dont have closed-source API key ?

Refer to the repo Models_in_LangChain for using open-sourced Hugging Face chat models (via API or locally).
