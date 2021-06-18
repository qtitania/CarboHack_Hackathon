# CARBOHACK-TRACK YOUR CARBON FOOTPRINT
<!-- 
[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue)](https://developer.ibm.com/callforcode/get-started/) [![Website](https://img.shields.io/badge/View-Website-blue)](https://sample-project.s3-web.us-east.cloud-object-storage.appdomain.cloud/) -->

**CARBOHACK- Web Application meant to calculate and track your carbon footprint and provide you suggestions on how to reduce it.**

![Logo](./static/img/logo.png)

## Contents

  - [Short Description](#short-description)
    - [What is the problem?](#what-is-the-problem)
    - [How we plan to help?](#how-we-plan-to-help)
    - [The idea](#the-idea)
  - [Demo video](#demo-video)
  - [The Architecture](#the-architecture)
  - [Long Description](#long-description)
    - [What is Carbon Footprint and why does it matter?](#what-is-carbon-footprint-and-why-does-it-matter)
    - [How does CarboHack accomplish that task?](#how-does-carboHack-accomplish-that-task)
  - [Solution Roadmap](#solution-roadmap)
    - [What does CarboHack currently do?](#what-does-carboHack-currently-do)
    - [What more will CarboHack do in the future?](#what-more-will-carboHack-do-in-the-future)
  - [Live Demo](#live-demo)
  - [IBM Service Used](#ibm-service-used)
  - [The Team](#team)


## SHORT DESCRIPTION:

### *What is the problem?*

The world’s Carbon Footprint (i.e., greenhouse gas emissions) have detrimental effects on the environment and on all life on Earth – the most notable of which is the melting of the ice caps and the looming threat of the world going under water. Plus, what’s even more deadly is people’s lack of awareness on how much they are aiding the process unknowingly and how easily they can slow it down just by modifying their lifestyle a little.

### *How we plan to help?*

We plan on letting people know both exactly how much they are contributing to the Earth’s demise and what measures they can take to fight Global Warming on an individual level. We also plan on collecting the required data (check the long description to know what data exactly and what is its significance) and providing it to organizations who wish to create change on a larger level.

### *The Idea.*

Our idea is creating a web application called CarboHack meant to calculate and track carbon footprint on an individual (and later, organizational as well) basis and provide the individual suggestions on how to reduce it. CarboHack will store individual footprint records throughout the months and organize it by state/union territory (of residence). There are many organizations and changemakers who are looking for ways to reduce carbon emissions who have no way of procuring the data required for them to act. The data that they require can be provided by us.

![Roadmap](./static/img/roadmap.jpg)

## DEMO VIDEO:

<!-- [![Watch the video](./static/img/logo.png)](https://youtu.be/UdkeWFFWnTg) -->
Watch the video here: https://cloud.ibm.com/catalog?search=cloudant#search_results

## THE ARCHITECTURE:

![Video transcription/translation app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## LONG DESCRIPTION:

**CARBOHACK- Web Application meant to calculate and track your carbon footprint and provide you suggestions on how to reduce it.**

### *What is Carbon Footprint and why does it matter?*

Carbon Footprint is the amount of total greenhouse gas emission by an individual, an organization, an event or a place. CarboHack measures the carbon emission of an individual. As we are all aware, the addition of greenhouse gases into the atmosphere is the main culprit of Global Warming. At this rate, major cities of the world will be under water in 30 years. CarboHack is merely an initiative to prevent that. 

![Roadmap](./static/img/roadmap.jpg)

### *How does CarboHack accomplish that task?*

There are two major ways in which this webapp plans on accomplishing that task. 

- *One*, it helps individuals reduce their own carbon footprint by assigning goals and providing the steps required to accomplish them. This would go miles in achieving our objective as every change begins at an individual level. 

![Roadmap](./static/img/roadmap.jpg)

- *Two* , it provides the much-required data. India suffers from a severe lack of proper carbon footprint tracking apps unlike other countries and we seek to change that. Chandigarh is the first and only state/union territory of India to have an app to measure carbon footprint. Even so, carbonwatch (the aforementioned app) is pretty inaccessible and hard to use as it asks for the exact amount of electricity used in kwh and such other details that would be difficult for the user to provide. CarboHack is an improvement in that space as it asks the user questions which can be readily answered and provides an accurate estimate after calculation. CarboHack will store individual footprint records throughout the months and organize it by state/union territory (of residence). 
Hence, it would be possible to get individual carbon footprints in different states of India. It would be easy to find out averages or see the trends in every state. For example, which state has the highest average carbon footprint and is it because of the excess usage of cars by individuals or too much emission by industries? What is the state with lowest average carbon footprint doing right?  This particular brand of information and data is invaluable if we are to attempt to bring down tour country’s greenhouse gases emission. Why is this data so important? The first step to change in any area is research and procuring data in that area. There are many organizations and changemakers who are looking for ways to reduce carbon emissions. The data that they require can be provided by us. That is our objective.

> **That is how we are looking to contribute to saving our Earth from going under water.**


## SOLUTION ROADMAP:

### *What does CarboHack currently do?*

The project currently does the following things.

- Currently, a portion of our dream has been materialized in the form of CarboHack’s present version consisting of a landing page, a sign-in/sign-up page, an initial entry form and a daily form to calculate and track carbon footprints and a user page with everything they need or want to know, all of which have a beautiful and easy-to-use UI in common.

![Roadmap](./static/img/roadmap.jpg)
- The landing page lets the user know in few words what is carbon footprint and what the role of CarboHack is and takes to the sign-in/sign-up page. If the user is signing up, they have to fill an initial questionnaire and then we display their carbon footprint estimate calculated using 3 major parameters.

![Roadmap](./static/img/roadmap.jpg)

![Roadmap](./static/img/roadmap.jpg)

![Roadmap](./static/img/roadmap.jpg)
- For continuous tracking, there is a daily form to fill every day. We track the user’s carbon footprint daily and display it in the form of a monthly average carbon footprint, carbon footprint so far this month and a graph showing their emissions per month since they signed up.

![Roadmap](./static/img/roadmap.jpg)
- CarboHack provides personalized suggestions according to the user’s overall goal to achieve and the information they provide us with every day.

![Roadmap](./static/img/roadmap.jpg)

It's in a free tier IBM Cloud Kubernetes cluster. In the future we plan to run on Red Hat OpenShift, for example.

### *What more will CarboHack do in the future?*

- CarboHack is going to be scaled to the national level where we can trace the carbon emissions of individuals and hence of a locality, town, city, we give them the steps to reduce their carbon footprints and reward them with environmental points. 
- CarboHack will be expanded to measure footprint of organizations and industries which undoubtedly contribute more greenhouses gases than common-place individuals. The webapp will help whole organizations to cut-down their carbon emissions which will make huge strides in improving our environment and slowing down climate change. 
- Even more parameters will be added to make the assessment more accurate and provide further more specific but easy-to-implement suggestions. 
- When we have collected a large amount data points, we wish to incorporate machine learning and help our system learn to plot and predict the carbon emission rate at some particular location in the near future. We believe the ceiling of potential this project has is unimaginably high.
- We are planning to make a community blog portal creating India's first climate change portal where fellow humans who are worried about the environment can come together and share their personal initiatives and ideas and have a platform to communicate and collaborate in their fight against climate change. 

![Roadmap](./static/img/roadmap.jpg)

<!-- ## Getting started

In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

- [sample-react-app](./sample-react-app/)
- [sample-angular-app](./sample-angular-app/)
- [Explore other projects](https://github.com/upkarlidder/ibmhacks) -->

## LIVE DEMO:

You can find a running system to test at [callforcode.mybluemix.net](http://callforcode.mybluemix.net/).

## IBM SERVICE USED:

<!-- - [IBM Cloudant](https://cloud.ibm.com/catalog?search=cloudant#search_results) - The NoSQL database used
- [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
- [IBM API Connect](https://cloud.ibm.com/catalog?search=api%20connect#search_results) - The web framework used
- [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
- [Maven](https://maven.apache.org/) - Dependency management
- [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds -->
IBM DB2

## TEAM:

*A group of college students from Heritage Institute of Technology, Kolkata*
- OISHEE SAHA
- SK MIRAJ UDDIN
- URMI JANA
- AUNOMITRA GHOSH



<!-- ## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

<a href="https://github.com/Call-for-Code/Project-Sample/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Call-for-Code/Project-Sample" />
</a>

- **Billie Thompson** - _Initial work_ - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details. -->

### THANK YOU

