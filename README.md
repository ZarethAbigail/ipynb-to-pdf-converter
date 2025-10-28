# ipynb-to-pdf-with-plotly-converter
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
   - OR click here:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ZarethAbigail/ipynb-to-pdf-with-plotly-converter/blob/main/ipynb-to-pdf-with-plotly-converter.ipynb
)


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
With technical guidance from **ChatGPT (OpenAI)**.

---

## License
Released under the **MIT License** — free to use and modify for educational or research purposes, with attribution.

---

## Example Outputs

Below are sample PDFs generated with this converter:

- [Example with Kaggle and Plotly](Example-with-kaggle-and-plotly.pdf)
- [Example with CSV and Plotly](Example-with-csv-and-plotly.pdf)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ZarethAbigail/ipynb-to-pdf-with-plotly-converter/blob/main/ipynb-to-pdf-with-plotly-converter.ipynb)
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Made with ❤️ by Zareth](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F%20by%20Zareth-blue)](https://www.linkedin.com/in/zarethabigailrdz/)


