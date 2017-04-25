# VODday-Hackathon-Submissions
This is a sample submission repository for Open Data Hackathon Projects. You can [fork this repo](https://help.github.com/articles/fork-a-repo/) and use this as a starting point. You do not have send a pull request for this repo. This is just a sample of what your repo can look like when you submit it to us as part of the final process for the hackathon.

##Team Name
*Team Vancouver Access*

##Team Members
- [Julie Sturgeon, Data Scientist/Mathematician](https://www.linkedin.com/in/julie-sturgeon-48274355/)
- [Kate Kourbatova, Full Stack Web Developer](https://www.linkedin.com/in/katekourbatova/)
- [Godot Bian, Business/Computer Science](https://www.linkedin.com/in/godotyuanbian/)
- [Aidin Mirsaeidi, Data Analyst](https://www.linkedin.com/in/aidinmirsaeidi/)
- [Manil Chowdhury, Web Developer](https://www.linkedin.com/in/manilchowdhury/)
- [Kevin Weiss, Firmware/Hardware/Software Engineer](https://www.linkedin.com/in/kevin-weiss-a9b2bb44/)
- [Farnaz Rashidi, Web Developer/Software Engineer](https://www.linkedin.com/in/farnaz-rashidi/)
- [Peter Lin, Data Scientist/Pharmacist](https://www.linkedin.com/in/peterlinmds/)


##Vancouver Open Data Day Challenge Summary
The team of 8 designed and prototyped a web-based application aimed to improve accessibility for various groups. (ie. transit, wheelchair, deaf, blind, and non-English users plus those who are sensitive to noise and/or scent) using open data sets from the government and businesses.

Won two out of six challenges
- Wildcard Challenge (Awesome prototype using open data across any category that inspires the judges)
- ProtoHack Challenge (Best idea with a viable business concept)





##Prototype
###Live Prototype


[Access 360 Prototype by Team Vancouver Access](https://api.mapbox.com/styles/v1/katekourbatova/cizw1z0q800182sobp8fr8clv.html?title=true&access_token=pk.eyJ1Ijoia2F0ZWtvdXJiYXRvdmEiLCJhIjoiY2l6dzFtN2IwMDE2bzJ2cWxtc2w1eTM2diJ9.6BFVNNLMaOv17XaM99E7Zw#13.12/49.2858/-123.1276)


###Presentation


[Access 360 slides](https://docs.google.com/presentation/d/15Z48N4_i0vHwOA2_2WuzHrn89sRgN-NmZi1xxk3iUcg/edit#slide=id.p4)



##Next Steps
*Continue to improve the app to include more data points using public and non public data sets*




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
