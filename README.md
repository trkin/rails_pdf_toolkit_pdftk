# Rails PDF Toolkit Wicked Pdfkit Wkhtmltopdf

We can manipulate pdf with PDF Toolkit and generate from docs using Wicked.

To create PDF using ruby code you can use https://github.com/trkin/rails_pdf_prawn

## PDF Tollkit

We need to use old gem https://github.com/blambeau/pdf-toolkit
It has dependency `pdftk` available on linux, mac and windows.

On ubuntu

```
sudo add-apt-repository ppa:malteworld/ppa
sudo apt update
sudo apt install pdftk
```

Some commands https://www.pdflabs.com/docs/pdftk-cli-examples/

```
# split pdf into multiple pages
pdftk in.pdf burst

# join
pdftk 1.pdf 2.pdf cat output 3.pdf
```
