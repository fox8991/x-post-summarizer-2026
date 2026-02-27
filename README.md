# x-post-summarizer-2026

AI-generated summary of a public figure's 2026 X posts, built with LangGraph, MCP tools, and the X API.

## Project Description
This repository summarizes the 2026 X posts of a public figure using AI. The analyzed account handle is `@llm_wizard`.

The project was built using a LangGraph agent that leverages GitHub MCP tools for repository operations and the X API v2 for retrieving posts.

## How to Replicate

1. **Set up your X API Bearer Token:**
   - Obtain your Bearer Token from the X developer portal.
   - Set it as an environment variable in your shell:
     ```bash
     export X_BEARER_TOKEN='your_bearer_token_here'
     ```

2. **Install Python dependencies:**
   - This project requires the `requests` library.
   - Install it using pip:
     ```bash
     pip install requests
     ```

3. **Run the search script:**
   - Use the provided `x_search.py` script to fetch recent posts from a specified X handle.
   - Example:
     ```bash
     python x_search.py llm_wizard
     ```

The script will save the fetched posts to `posts.json` and print a summary to the console.

---

Feel free to explore and extend this project for other public figures or different time ranges.