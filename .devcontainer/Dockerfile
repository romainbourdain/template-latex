FROM qmcgaw/latexdevcontainer

# Installer les packages nécessaires
RUN apt-get update && apt-get install -y \
    texlive-latex-extra \
    texlive-science \
    texlive-lang-french \
    texlive-bibtex-extra \
    biber \
    && rm -rf /var/lib/apt/lists/*