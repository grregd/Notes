
apt install texlive-extra-utils

pdfjam pcb-top.pdf pcb-bottom.pdf --outfile 1.pdf

pdfnum --nup 2x1 1.pdf --outfile multiple.pdf

