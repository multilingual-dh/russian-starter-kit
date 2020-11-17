# Russian Starter Kit
Resources for getting started with DH methods in Russian.

## Before you begin: Add Google Colab to Drive
Google Colab lets you run the code described here using Google servers, and accessing files that you've stored in Google Drive.

In Google Docs, click the big **+ New** button. 
![Google Drive new button](images/drive-new.png)
Choose **More**, then **Connect more apps**. Search for `colab` and add Google Colaboratory to your Drive.

## If you have text files (.txt)...
Lemmatize them (turning every word into its dictionary form) before searching or using any word-count tool like [Voyant](http://voyant-tools.org/) or [AntConc](https://www.laurenceanthony.net/software/antconc/).

[Click here to launch the Russian lemmatizer](http://colab.research.google.com/github/multilingual-dh/russian-starter-kit/blob/main/colab_russian_lemmatizer.ipynb) on Colab.

## If you have PDFs instead of text files...
Your PDF may already have an invisible text layer that you can export if you have Adobe Acrobat Pro. Open the PDF in Adobe Acrobat Pro, then go **File** --> **Export to** --> **Text (plain)**.

Open the text file. If it's readable Russian, upload it to Google Drive and run the Russian lemmatizer linked above. If the file has text, but it's unreadable gibberish that looks like Latin with diacritics (e.g. ôèëüìà îá îñíîâíîì ðåêëàìíîì), paste the text [into the top box on this Universal Cyrillic decoder website](https://2cyr.com/decode/?lang=en) (you may have to break it up into smaller chunks and do them one at a time), hit "OK" using the default settings, and see if that fixes it.

If that doesn't fix it, or if you get a blank text file out of Adobe Acrobat, upload the PDF to Google Drive and [use this Russian OCR notebook](http://colab.research.google.com/github/multilingual-dh/russian-starter-kit/blob/main/Tesseract_RU.ipynb) on Colab that will attempt to "read" the image of the PDF and convert it into text.

## Other resources of note

* [Transkribus](https://transkribus.eu/) (low per-page cost after initial free pages) has a model by Achim Rabus for transcribing B&W or color medieval Slavic manuscripts