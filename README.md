**IETE Hackathon project ML problem statement.**


Creating a **movie review sentiment analyser** which tells whether a movie review is positive or negative or neutral.


I wanted to create a web app on which you would select a movie , it will tell you whether movie has generally recieved positive or negative or neutral reviews and you would also get a option to write your own review which would effect the general ratings.


I started by taking Rotten Movies Tomato Dataset from kaggle. Plan was to preprocess the reviewText and from that preprocessed text create embeddings and and then using sentiment analyer from pipeline of transformer i wanted generate sentiment and sentiment score.Since many movies had different reviews so i wanted to take a mean of all review scores and set a threshold of 0.6 to tell if movie is positive, 0.4-0.6-neutral and <0.4 negative.
and then create a flask app but my GPU compute units got over and had to revert to cpu and at the end project couldnt be completed.

I got a lot to learn from this project and got to know about many new things and it spiked my interest to read about NLP.

