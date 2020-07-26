# Instruction to Setup
1. conda env create -f environment.yml
2. source activate epub
3. python epub2pdf.py "{filepath}"
4. It will generate {filename}.pdf in current directory

# Known Bugs
1. Problem in image addition
2. Pdf Outline issues.
3. Some books have different data folder like "OPS" instead of "OEBPS" and "styles" instead of "css"
4. page change for each chapter.
