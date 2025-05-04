# INSAR2025 Conference Poster – R/Posterdown

This repository contains the materials for a scientific poster created using the [`posterdown`](https://github.com/brentthorne/posterdown) R package. The poster was prepared for the International Society for Autism Research (INSAR) 2025 conference.

## 📌 Overview

The project uses a fully reproducible R Markdown-based workflow for designing and generating a professional academic poster. It includes source code, output formats (PDF/HTML), custom styling, embedded figures, and bibliographic references.

---

## 📂 Repository Structure

```

INSAR2025/
├── INSAR2025.Rmd           # Main R Markdown file
├── INSAR2025.pdf           # Poster (PDF version)
├── INSAR2025.html          # Poster (HTML version)
├── custom.css              # Custom CSS for styling
├── INSAR.bib               # Bibliography file
├── merged.png              # Embedded figure/image
├── project\_icon.png        # Project logo/icon
├── Diversity...png         # Additional figures (two PNGs)
├── combine...png           # Supporting image
├── .Rhistory               # R session history

````

> _Note: File names shortened for readability. See actual filenames in the repository._

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/INSAR2025-poster.git
   cd INSAR2025-poster
````

2. Open `INSAR2025.Rmd` in RStudio.

3. Install required R packages (if not already installed):

   ```r
   install.packages(c("posterdown", "rmarkdown", "knitr"))
   ```

4. Knit the R Markdown file to generate your poster (PDF/HTML):

   * **PDF:** Ensure you have a LaTeX distribution installed (e.g., TinyTeX).
   * **HTML:** No additional dependencies beyond R packages.

---

## 📄 Licence

This project is distributed under the MIT License. See `LICENSE` for more information.

---

## 🙋 Acknowledgements

* Poster generated using [`posterdown`](https://github.com/brentthorne/posterdown) by Brent Thorne.
* Conference: International Society for Autism Research (INSAR) 2025.
