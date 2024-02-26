# Music Top page

Here you will learn how to load data from a mock server

## Steps

- Clone this repo:
    - click the green Code button in github, copy the URL
    - open the Visual Studio Code in your learning folder and and write in terminal `git clone <paste_your_url_here>`
- create a separate branch `git switch -c "dev"`
- add html and css files and code
- in VS Code, click on html file and Go Live (plugin installed previously) to avoid refreshing the page on changes
- when you're done coding, add the changes to staging using + button in VS Code Source Control tab or type on terminal `git add .`
![VS Code staging](images/stage.png) 
- commit and push the code `git commit -am "commit message here"`, `git push -u origin dev`
- go to github and raise a pull request from your development branch to master
![Open PR](images/pullRequest.png) 

## Requirements

- Create a Music Top webpage which contains:
    a. three inputs, one for Artist, one for Song Name and the last for Album 
    b. an Add Song button under the inputs, which makes a request to the local server to add the song with details specified in the input
    c. the list of songs stored on the local server (my-json-server) - see the songs already existing in db.json and adopt this format for adding new songs or displaying them
- Install necessary packages using `npm install`
- To start the songs server, type `npm run start`
- use fetch API to load the songs
- after adding a song, the music top must refresh and display the new song in the list
- style the page for desktop and mobile viewing, making it responsive (use the inspector to test the look on mobile devices)
- if you need to upload images to your repo, place them all inside the images folder
- use English everywhere (page, variables naming, comments, commit messages)

