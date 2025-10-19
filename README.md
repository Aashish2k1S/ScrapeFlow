# 🕸️ ScrapeFlow: AI-Powered Web Scraping & Structured Entity Extraction

ScrapeFlow is a Python project that automates data extraction from multiple web sources and uses the **DSPy framework** to build robust LLM pipelines for extracting, validating, and visualizing structured entities from scraped content.

---

## 🚀 Tech Stack & Libraries

The project leverages a modern data and AI stack to handle the entire flow from scraping to visualization.

* **Python:** The core language, utilized with essential data and web libraries:
    * **Pandas:** Data handling and manipulation.
    * **Requests** & **BeautifulSoup:** Core libraries for web scraping.
    * **Pydantic:** Defining strict schemas for **structured information extraction** (S-I.E.).
* **DSPy:** The declarative framework used to program and optimize LLM pipelines for reliable entity extraction.
* **Mermaid:** Generates **Graph-based visualizations** for simple entity relationships.
* **Google Colab:** Primary environment for execution and demonstration.
* **CSV Export:** Final structured output format (`tags.csv`).

---

## 📁 Project Flow (Scrape to Save)

The ScrapeFlow pipeline is executed in a five-step process:

1.  **Scraping:** 🌐 Access a list of **10 target URLs** to scrape relevant text content and associated image URLs.
2.  **Entity Extraction:** 🧠 Utilize the configured DSPy pipeline, guided by Pydantic schemas, to extract structured `entity` and `attr_type` (tag and tag type) from the text.
3.  **Data Cleaning:** 🧹 **Deduplicate and validate** the extracted entities to ensure quality and consistency with **[LogCat](https://longcat.chat/)**.
4.  **Visualization:** 📈 Generate **[Mermaid graphs](https://mermaid.live/edit)** to visualize simple relationships and connections between the extracted entities.
5.  **Data Export:** 💾 Save the final, validated results to a structured output file, **`Output.csv`**.

### 📊 Example Output (`tags.csv`)

| Link | Tag | Tag Type |
| :--- | :--- | :--- |
| `https://example.com/agri` | Sustainable Agriculture | Concept |
| `https://example.com/brain` | Alzheimer’s disease | Disease |

---

## 🧩 Future Enhancements

Potential improvements and extensions to ScrapeFlow:

* **Multimodality:** Add image caption extraction using models like **CLIP** for richer context.
* **Advanced Relations:** Integrate **LangChain or OpenAI** to define and extract more complex relationships between entities (e.g., "Person works for Organization").
* **Interactive Deployment:** Deploy a **Streamlit visualization** dashboard for interactive exploration and filtering of the entity graphs.

---

## 👨‍💻 Author

**Aashish Gupta**
AI & Software Developer

[LinkedIn](https://www.linkedin.com/in/aashish2k1s) | [GitHub](https://github.com/Aashish2k1S)

> 🌱 **“The fastest way to learn AI is to build something that scares you a little.”**
