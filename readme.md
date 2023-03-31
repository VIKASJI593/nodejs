//output in terminal while click on delete button
{ phone: '1111111111' }

//after kill the terminal ouput show in url
http://localhost:8000/delete-contact/?phone=1111111111


//home.ejs file

<div class="delete-button">
<a href="/delete-contact/?phone=<%= i.phone %>">
<img class="img" src="https://img.icons8.com/metro/26/000000/waste.png"/>
</a>
</div>

nodemon index.js

http://localhost:8000/

http://localhost:8000/practice

// create a new repository

git init

git add .

git commit -m "16-query-url"

git branch -M 16-query-url

git branch

git remote add origin https://github.com/VIKASJI593/nodejs.git

git remote -v

git push -u origin 16-query-url

git push -f -u origin 16-query-url
