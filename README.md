
# Instructions for updating the Complexity coursebook. 

- add additional notebooks/markdown files to directories separated by topic
- add the corresponding files to the `_toc.yml` file to add them to the overall table of content of the book. 
- test building the book for errors using `jupyter-book build .` or `jb build .` (if already inside the coursebook directory). 
- if no errors are present, the updated version of the book can be pushed live using the script `publish_book.sh`, which builds the book and pushes it to the live github pages website. 

