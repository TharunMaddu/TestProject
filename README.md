# TestProject
~$ git clone https://github.com/TharunMaddu/TestProject.git
~$ cd TestProject
~$ mvn package
~$ java -jar target/document-archive-0.1.0.jar

API's

1. Add a document/archive/upload?file={file}&person={person}&date={yyyy-mm-dd} POST
file: A file posted in a multipart request
person: The name of the uploading person
date: The date of the document

2. Find documents/archive/documents?person={person}&date={date} GET
person: The name of the uploading person
date: The date of the document

3. Get a document/archive/document/{id} GET
id: The UUID of a document


