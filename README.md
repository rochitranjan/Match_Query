# Match_Query

Problem Statement - Given a user entered query in the search box, output the product title which has maximum match with the entered query.
For eg if the query is '3 clinique', then the output should be :
3 Clinique Repairwear Laser Focus Wrinkle Correcting Eye Cream .17 oz/5 ml
Each is preferred over NEW! Clinique Repairwear Laser Focus Wrinkle
Correcting Eye Cream 5ml


In case of multiple product matches (with the same overlap), output the product with least product price.
For eg if someone says 'playstation', output is:  
Dual PlayStation/PlayStation 2 PS1 PS2 PSX to PC USB Controller Adapter
(Price=$2.75)

You will need to clean data in the product price column.
Also, handle cases like if the user enters 'antidark', the code should be able to
do fuzzy matching and recognize similarity with products that have 'Anti-Dark'
in their name.
