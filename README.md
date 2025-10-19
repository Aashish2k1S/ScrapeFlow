### 🧾 Summary & Observations

---

✅ What This Notebook Does:

- Scrapes 10 web pages using BeautifulSoup
- Uses DSPy + Pydantic to extract structured entity data
- Deduplicates extracted entities using custom logic
- Creates Mermaid diagram output for visual relationship mapping
- Saves all extracted entities to a `Output.csv` file

---

📌 Notes:

- LLM entity extraction is not 100% deterministic — your output might vary run-to-run.
- You can add confidence scoring or filter based on entity types if needed.
- Mermaid diagrams can be extended to show richer relationships (e.g., weights, categories).

---

💬 Improvements (Optional):

- Add a confidence threshold for filtering LLM output
- Build a Streamlit app to visualize results
- Use fuzzy string matching for smarter deduplication
