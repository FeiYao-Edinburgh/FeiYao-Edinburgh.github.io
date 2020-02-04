This is the repo supporting Fei Yao's personal website.

Basic editing steps:
- \_data/navigation.yml controls the contents visible
- Seperate pages are mainly stored in \_pages. Filenames are not important. Extension names don't matter, either (e.g. I have changed talks.html to presentations.md). Copy the header of an existing one and add markdown scripts below. As long as it corresponds to \_data/navigation.yml, it can display correctly. I have removed teaching.html, cv.md. Other files will be checked in a later time to see if can be deleted as well as related dirs.
- Python scripts under markdown_generator/ is to create seperate pages for each paper, I might add more contents for each paper manually based on the automatic production. talks related scripts and tsv files are removed since I do not need them. Remaining files will be inspected in a later time to see if can be removed.

There are still some issues need to be addressed...
- footer
- Upload images, slides, and comments/responses if applicable for each paper. Note that the url cited should be something like https://feiyao-edinburgh.github.io/files/FeiCV.pdf. All files stored in files.
- Update the map contents under Life menu
- Upload Best Student Paper Award pdf files and make update in Honors.
- Update homepage in my cv on overleaf.
- Remove unnecessary dirs like posts, portfolio
- [ResearcherID](https://publons.com/researcher/2061962/fei-yao/)