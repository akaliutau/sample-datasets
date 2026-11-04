# Algomini Datasets

A curated collection of public-domain text and structured JSON datasets designed for benchmarking text and data compression algorithms, throughput tests, and evaluation metrics.

---

## 📁 Directory Structure & File Descriptions

### 1. `gutenberg.org/`

Contains 2 public-domain plain texts literary works sourced from Project Gutenberg. 
Ideal for testing entropy coding, dictionary-based compression (e.g., LZ77/LZ4/zstd), and natural language processing pipelines.

* **`shakespeare.txt`** (~5.5 MB) – The Complete Works of William Shakespeare. Rich in vocabulary variation and standard English prose.
* **`monte_cristo.txt`** (~2.7 MB) – Alexandre Dumas' classic adventure novel for deep sequential text streaming tests.

---

### 2. `json-data/`

Contains structured, semi-structured, and minified JSON files varying from 512 KB to 12 MB. Perfect for evaluating how well a compression tool handles keys, nested objects, data types, and whitespace-heavy formatting vs. minification.

* `512KB.json` & `1MB.json` – Formatted Microsoft Edge static dummy data featuring repetitive hierarchical records.

---

### 3. `wikimedia.org/`

Contains raw text extracts, abstracts, and markup dumps from Wikipedia. Useful for testing mixed-content corpora that combine unstructured human language with structural markup patterns.

2 small dumps (19MB and 1MB)



