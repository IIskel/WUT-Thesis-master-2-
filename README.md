# WUT-Thesis ![CI](https://github.com/ArturB/WUT-Thesis/workflows/CI/badge.svg)

Repozytorium zawiera szablon pracy dyplomowej w LateXu: inżynierskiej oraz magisterskiej - przeznaczony dla Wydziału EiTI oraz Wydziału MEiL Politechniki Warszawskiej.

Certainly! Here's a template for a README file tailored for a thesis document intended for GitHub, with Overleaf/LaTeX integration:

---

# Thesis Title

## Overview

This repository contains the LaTeX source files for my thesis titled Recognition of Objects in the Environments of Autonomous Vehicles in real-time. This thesis endeavors to investigate a deep learning-based obstacle avoidance system designed for autonomous vehicles, including mobile robots, through the utilization of Neural Architecture Search (NAS)

## Getting Started

To compile the LaTeX document, you can either use your local LaTeX distribution or import this project into Overleaf.

### Local Compilation

1. Ensure you have LaTeX installed on your system. You can download it from [TeX Users Group](https://www.tug.org/).
2. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/IIskel/WUT-Thesis-master-2-.git
   ```

3. Navigate to the project directory:

   ```bash
   cd your-repository
   ```

4. Compile the main LaTeX file:

   ```bash
   pdflatex main.tex
   ```

   Run this command multiple times to resolve references and generate the final PDF.

### Overleaf Integration

1. Sign up or log in to [Overleaf](https://www.overleaf.com/).
2. Click on "New Project" -> "Import from GitHub".
3. Enter the URL of this repository.
4. Overleaf will import the project. You can now edit and compile the LaTeX document online.

## Structure

- **`main.tex`**: Main LaTeX file containing document structure and metadata.
- **`tex`**: Directory containing individual chapters.
- **`tex/image`**: Directory for storing figures.
- **`bibliografia.bib`**: Directory for bibliography files (e.g., `.bib`).

## Contributing

Feel free to open an issue or submit a pull request if you have any issues, have suggestions, or want to contribute.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

I would like to express my gratitude to Prof. Rzymkowski Cezary, for their invaluable support and guidance throughout the thesis writing process.
