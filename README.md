# SentAnalysis
An online Sentiment Analysis tool where user can enter the review and the output will be the sentiment of the review

## Dataset
In this project IMDB reviews data is used
```bash
https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?select=IMDB+Dataset.csv
```
## LINK
```bash
https://sentanalysis1.herokuapp.com/
```
## Usage

User need to enter the review into the "TEXTAREA" given on the homepage and then submit it. Submt button will take you to the new page "OUTPUT" where you will get the sentiment of the review.

## Deploying it on HEROKU

* First make a requirements.txt file in your project folder
* This can be done using pip freeze(but it will list out all the libraries installed in your environment)
* So we can also user pipreqs(this will only list the libraries need for your current app) 
```bash
install pipreqs
pipreqs .
```
* Now we have a requirements.txt file of our project we need to add a Procfile(only needed for heroku)
* After that we need make a github repository of our project with all these files
* Then, on heroku make a new app and link that with github and just deploy.
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
