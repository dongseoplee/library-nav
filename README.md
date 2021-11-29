# library-nav
2021 Gachon univeristy algorithm class term project<br>
This is a service for the experimental implementation of the edit distance algorithm and the dijkstra algorithm.

http://chromato99.com

This is a web service to shorten the search time to locate a book when using the Gachon University library.

Provides a function with 'Dijkstra' algorithm to inform you of the shortest path from the current location to the location of the book when searching for a book name. <br>
Also, if you make a typo when searching for a book name, similar book names are automatically suggested by using 'Edit Distance' algorithm.

Currently, there is no Gachon University library DB, so the Gangnam-gu smart library DB is being used temporarily.

- Example Screenshots
![Screenshot from 2021-11-29 02-05-57](https://user-images.githubusercontent.com/20539422/143778625-0500e8e7-f3de-4149-b7f9-4acc3b135dc6.png)
![Screenshot from 2021-11-29 02-06-50](https://user-images.githubusercontent.com/20539422/143778641-0750cd6d-509e-481c-8f27-75ae95e8fb26.png)
![Screenshot from 2021-11-29 02-07-13](https://user-images.githubusercontent.com/20539422/143778648-3e728bcf-774a-4a42-8b09-1c0d84807b0c.png)

  
# Run on localhost
1) Download DB data from https://www.data.go.kr/data/15071671/fileData.do or your own DB.
2) Set MySQL server and table as below and set db.template.js to db.js with your setting.
![Screenshot from 2021-11-29 13-28-31](https://user-images.githubusercontent.com/20539422/143809094-e616ca9a-2276-4fae-a8ad-b5289775933a.png)

3) Run Server with Node.js
```
cd <project directory>
npm install
node server.js
```

# Tech Stack
[FE] HTML / CSS / Javascript<br>
[BE] Node.js<br>
[Database] MySQL<br>
Testing DB from https://www.data.go.kr/data/15071671/fileData.do 
