//1 Page


/login (POST)
http://localhost:5000/api/auth/login

//register (POST)
http://localhost:5000/api/auth/register

//getallUsers (GET)
http://localhost:5000/api/auth/users

//UserInfo/ (GET) => http://localhost:5000/api/auth/userInfo?x-access-token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNTQyMzcyYmExMGFiNTc0NTkyOTMyNiIsImlhdCI6MTY2NjQ1ODYzNywiZXhwIjoxNjY2NTQ1MDM3fQ.DZFLOD94Y43UPPwMziHcRCISrT3hlwDqgKAt22xWnX4



//updateplan update payment details
localhost:2500/updateplan/1

//part of body
{
"status":"Placed",
"bank_name":"SBI",
"date":"15/10/2024",
"cost":1496
}

//Delete plan suscription

localhost:2500/deleteOrder/62564d77f5aec503b2e0f2aa

//2 Home page
//TV shows
http://localhost:2500/TVShows
https://noderestnetflix.herokuapp.com/TVShows
//TV shows based on Title
http://localhost:2500/TVShows?Title=Buisiness%20Proposal
live link
https://noderestnetflix.herokuapp.com/TVShows?Title=Buisiness%20Proposal
//AllMovies
http://localhost:2500/all
https://noderestnetflix.herokuapp.com/all
//AllMovies based on Title
http://localhost:2500/all
https://noderestnetflix.herokuapp.com/all?Title=300

Search with Different genre:
//Action
http://localhost:2500/action
https://noderestnetflix.herokuapp.com/action
//Action based on Title
http://localhost:2500/action?Title=300
https://noderestnetflix.herokuapp.com/action?Title=300

//Adventure
http://localhost:2500/adventure
https://noderestnetflix.herokuapp.com/adventure
//Adventure based on Title
http://localhost:2500/adventure?Title=Rogue%20One:%20A%20Star%20Wars%20Story

//Crime
http://localhost:2500/crime
https://noderestnetflix.herokuapp.com/crime
//Crime ction based on Title
http://localhost:2500/crime?Title=Narcos
https://noderestnetflix.herokuapp.com/crime?Title=Narcos

//Horror
http://localhost:2500/horror
https://noderestnetflix.herokuapp.com/horror
//Horror based on Title
http://localhost:2500/horror?Title=Luke%20Cage
https://noderestnetflix.herokuapp.com/horror?Title=Luke%20Cage

//Romance
http://localhost:2500/romance
https://noderestnetflix.herokuapp.com/romance
//Romance based on Title
https://noderestnetflix.herokuapp.com/romance?Title=Luke%20Cage

Search with movie names
http://localhost:2500/all?Title:300
https://noderestnetflix.herokuapp.com/all?Title:300

Search with the name of actors/actresses

Based on imdb rating(basically imdb ration above) Sort with category id as param
https://noderestnetflix.herokuapp.com/filter/3

Based on category and year and sort on the basis Of imdbRating
http://localhost:2500/filter/3?year=2006
https://noderestnetflix.herokuapp.com/filter/3?year=2006

//3
//Payment Gateway

////////////////////////
