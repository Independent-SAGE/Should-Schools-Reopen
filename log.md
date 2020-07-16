# Log

 1. Rip original PDF report
 1. Download as HTML , EPUB (source) from Fidus Writer
 1. Load repo as Atom project
 1. Run R script for HTML to MD conversion https://github.com/akademie-oeffentliches-gesundheitswesen/fidus2github
    - sudo R
    - fidus2github:::convert_fidus_to_github(fiduszipfile = "your-download.zip")
 1. Copy all files accross to /docs/report/
 1. Unzip HTML to a folder to access other assets, e.g., ToC
 1. Paste in ToC from index.html to chapter_0.md
 1. Provide graphic alternatives for tables
 1. Generate front matter
 1. Render website with Hugo and Docsify
 1. Aquire identifiers and PIDs from Nielsen UK ISBN services and Zenodo DOI service
 1. Write metadata
 1. Add HTML to Vivliostyle CSS Typesetter and generate Web Book and PDF from Google Chrome
 1. Distribute print-on-demand via Lightningsource and ebook via Ingram Spark
 1. Publishing on GitHub Pages.
 1. Deposit with Zenodo - only usable media and not whole repo as confusing otherwise
 1. Deposit all citations in Zotero
 1. Make GitHub release

# To Do

  1. GitLab release
  1. Make ISBN legal deposit
  1. Enable Docsify multilingual translation
  2. Add Weblate translation services
  3. Re-render graphics and add SVG chart rendering
  4. Rationalise system
  5. Improve ebook Metadata
  6. Produce ebook Amazon Kindle AZW/kf8 file
  7. Amazon and Google Book - look inside, view inside
  8. Serving or embedding files inside Docsify
