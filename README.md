# ipynb-to-pdf-converter
Convert any Google Colab notebook (`.ipynb`) into a **high-quality PDF** — including **Plotly graphs in HD (PNG export)**.  

---

## Features
- Works directly in **Google Colab**.
- Supports **Plotly** graphs via Kaleido (PNG high-resolution output).
- Option to **hide technical setup cells** automatically.
- Compatible with **CSV, Excel, image inputs, Kaggle, etc.**.
- Fully offline conversion once executed.

---

## How to use it

1. **Open in Google Colab**
   - Upload this notebook to your Google Colab environment.

2. **Run the first cell**
   - Installs dependencies automatically (Plotly, Kaleido, nbconvert, Pyppeteer).

3. **Upload your notebook**
   - When prompted, upload your `.ipynb` file and any extra data files (CSV, Excel, etc.) your notebook requires.

4. **Wait for the export**
   - Conversion usually takes **2–5 minutes**, depending on notebook size and number of graphs.
   - When finished, you’ll see:
     ```
     ✅ PDF generated: /content/YourNotebook_export.pdf
     ```

5. **Download the PDF**
   - Colab will automatically download the document.

---

## Notes & Troubleshooting
<small>

- If the export seems stuck but doesn’t show an error, just wait — Plotly rendering can take a few minutes.  
- If you see an error like `FileNotFoundError` or `ImportError`, verify that all your datasets are uploaded to `/content/`.  
- Avoid interactive functions like `input()` or `plotly.show()` (they can interrupt execution).

</small>

---

## Author

Developed by **Zareth Abigail Rodríguez Reyes**  
Created as a personal tool for exporting academic and analytical notebooks to professional-grade PDFs.  
With technical guidance from **ChatGPT (OpenAI)** to debug and optimize the export pipeline.

---

## License
Released under the **MIT License** — free to use and modify for educational or research purposes, with attribution.

---
