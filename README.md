#### MiniLM

- A Language Model built from scratch in C .

##### _Usage_

- compile to mlm.exe
- run ./mlm -q query
- run ./mlm -F folderpath -- to read all the text files in that folder
- run ./mlm -f filepath -- to read from the uploaded text file
- outputs by default are stored in output.txt .
- chat.txt has all the asked queries and the responses.
- run ./mlm delete chat -- to clear chat.txt .
- run ./mlm -qi filepath -- to read the query from a text file .
- run ./mlm pdf filename
- run ./mlm -F pdf folderpath -- to select a folder full of pdf's .

##### Requirements :

- Should be able to parse pdf's.
- Optional ability to export / write the chat in pdf format as well.

##### Why this ?

- Just a small project to learn Rust & LM's .
