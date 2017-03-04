# VODday-Hackathon-Submissions
This is a sample submission repository for Open Data Hackathon Projects. You can [fork this repo](https://help.github.com/articles/fork-a-repo/) and use this as a starting point. You do not have send a pull request for this repo. This is just a sample of what your repo can look like when you submit it to us as part of the final process for the hackathon.

##Team Name
*Choose a fun team name!*



##Vancouver Open Data Day Challenge
*What VODDay Challenge is your project focusing on? (See the [2017 VODday Challenges](https://www.opendatabc.ca/pages/2017-vodday-vancouver-open-data-day#challenges).)*



##Prototype Problem Statement
*A clear statement of the problem your team has identified to address through the project. Use this problem statement as the basis to ideate around. Research and validate the problem to test if it is an issue, or if others are already addressing in. You may need to pivit your problem statement, and ideas around approach depending on what you discover about the issue and resources available.*

*This will help focus your approach to addressing the challenge.*



##Protoype Summary
*Summarize your approach to addressing the challenge. Highlight the value of your approach to addressing the challenge, who your inteded users are, and the long term vision.*



##Open Data Sets
###What Open Data Sets Will You Use?
*What open data sets, standards, OpenAPI's etc does your prototype draw on? How does it use them?*

 - List them here...



###What Open Data Sets Do You Still Need?
*Identify open data sets that are not yet available, but would benifit or are needed for the project. Explain how you would use the data to improve your prototype and address the challenge.*

*This is your chance to form a mini business case for the data you need to share with open data providers!*



##Prototype
###Live Prototype
*Link to your prototype.*


###Presentation
*Link to your presentation or any related visuals you want to share.*



##Next Steps
*What do you need to do next to turn this prototype into a working solution?*



##Progress
*Keep updating as you continue to turn your prototype into a working solution.*
 - Summarize what progress you've made since VODday
 - Tweet [@OpenDataBC](https://twitter.com/opendatabc) with your updates
 - Show off your progress at [OpenDataBC events](https://www.meetup.com/OpenDataBC-Vancouver)
 - Share your prototype and progress with the organizations related to the challenge your adressing and the providers of the open data you are using.


##Setup
### Install Dependencies

We have two kinds of dependencies in this project: tools and Angular framework code. The tools help
us manage and test the application.

* We get the tools we depend upon via `npm`, the [Node package manager][npm].
* We get the Angular code via `bower`, a [client-side code package manager][bower].
* In order to run the end-to-end tests, you will also need to have the
  [Java Development Kit (JDK)][jdk] installed on your machine. Check out the section on
  [end-to-end testing](#e2e-testing) for more info.

We have preconfigured `npm` to automatically run `bower` so we can simply do:

```
npm install
```

Behind the scenes this will also call `bower install`. After that, you should find out that you have
two new folders in your project.

* `node_modules` - contains the npm packages for the tools we need
* `app/bower_components` - contains the Angular framework files

*Note that the `bower_components` folder would normally be installed in the root folder but
`angular-seed` changes this location through the `.bowerrc` file. Putting it in the `app` folder
makes it easier to serve the files by a web server.*

### Run the Application

We have preconfigured the project with a simple development web server. The simplest way to start
this server is:

```
npm start
```

Now browse to the app at [`localhost:8000/index.html`][local-app-url].
