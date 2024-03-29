# FunFic Generator with ChartGPT

This project has the purpose of learning Django and get more familiarity with python3, API consumption and dealing with data. 

## Theme

The main idea of this project is to make FunFic based on movies, so we will consum data from 
[TheMoviedb](https://www.themoviedb.org/) and use this data to create a site where people can generate a fanfic, behind the scenes our API will use OPENAI API to create this for us and after that show that to the user. 

## About the structure of this project

To learn more about the best prictices of Python and Django I'm goig to use the documentation [Structuring Your Project](https://docs.python-guide.org/writing/structure/), as a beginner I don't know much about Python Conventions or how a good python project structure should be, maybe this can enlight me a little bit. 

For Django convention and best practice I'll be using a StudyGyann article about Django Best Practices, you can read it [here](https://studygyaan.com/django/best-practice-to-structure-django-project-directories-and-files#:~:text=The%20way%20I%20like%20to,content%20in%20the%20media%20folder.&text=If%20playback%20doesn't%20begin%20shortly%2C%20try%20restarting%20your%20device.).


# Architecture

![Architecture](https://raw.githubusercontent.com/rafaelcmonteiro/movie_mania/main/fanfic_generator.png)

# TODO

Now that we decided how our architecture will look alike at the end of this project, we have to start a MPV/Prototype.

## MVP/Prototype

- [ ] Create a [OPEN AI KEY](https://platform.openai.com/docs/api-reference/authentication), to interact with chatGPT at.
- [ ] Use any software like Postman to make some request to the API, use the [API DOC](https://platform.openai.com/docs/api-reference/chat)
- [ ] Create a sample code that use a name of a movie and get from GPT chart the following. 

Exemple:

- "Can you make a fanfic about guardian of the galary vol.3"
- "Now, make it as if were a terror history"

After you receive the answer, you can store it in a file, and that will do.

## Next Steps

The next, will be the heavier part of the job. 
- Interact with any source of movie names can be MDBAPI or MovieDB.
- Get a JSON with the best movies of all time, you can make a code to get that list from the API, or just set a list by yourself.
- Show a sample HTML with the list of movies and redirect it, when a name is clicked, to a page with a random generated funfic by chart GPT.

After that feel free to create more...

## Frameworks and Tools

|Name |Version|
|-----|--------|
|Python|3       |
|Django  |1.8   |
|Mysql  |8.0.27 |
|HTML  |5   |
|CSS  |3   |
|Bootstrap  |3  |