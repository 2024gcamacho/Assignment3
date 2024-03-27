# Guadalupe Camacho - CS:3980 - Assignment 3
# To get started with this assignment, I created my MongoDB account. I found the process to be confusing, so I read the documentation which helped me understand MongoDB better. After that, I downloaded the MongboDB compass to query my sample database. 
# Number 1: db.movies.find({ runtime: { $gt: 200 }, year: 1983  },{ runtime: 1,  title: 1,  year: 1, _id: 0 }).sort({ runtime: 1 })
# ![Image Alt Text](https://i.imgur.com/sNErp86.png)
#Number 2: db.movies.find({ year: { $gt: 2014 }, "imdb.rating": { $gt: 9 }}, { title: 1,  year: 1, "imdb.rating": 1,  _id: 0 })
# ![Image Alt Text](https://i.imgur.com/AMOFKPN.png)
