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
    - A new song form with three inputs, one for Artist, one for Song Name and the last for Album 
    - an Add Song button under the form, which makes a request to the local server to add the song with details specified in the inputs
    - the list of songs - stored on the local server (my-json-server) - see the songs already existing in `db.json` and use this format for adding new songs or displaying them. Sort the songs by votes (high to low)
- Install necessary packages using `npm install`
- To start the songs server, type `npm run start`
- use fetch API to load the songs
- after adding a song, the music top must display the new song in the list. Do not re-fetch the songs, just add the new song in the song list container, using `insertAdjacentHTML("beforeend", songHtmlText)` https://developer.mozilla.org/en-US/docs/Web/API/Element/insertAdjacentHTML
- documentation for my-json-server here: https://www.npmjs.com/package/json-server
- style the page for desktop and mobile viewing, making it responsive (use the inspector to test the look on mobile devices)
- if you need to upload images to your repo, place them all inside the images folder
- use English everywhere (page, variables naming, comments, commit messages)

