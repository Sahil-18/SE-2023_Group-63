# Software Engineering Fall 2023

## Project 1

First phase of the Software Engineering Project was to evaluate 5 different projects. These projects covered a variety of use cases which used a diverse technology stack, each with its own sets of challenges and opportunities.

Projects provided to us for evaluation are:
#### 1. ClassMate Bot
#### 2. MyDollar Bot
#### 3. Feature Hunt
#### 4. GITS
#### 5. Recipe Recommender


While trying to assess these projects on different metrics provided on the course github repository,  we faced multiple challenges with setting up the project, understanding different technology stack and also to come up with unique substantial future opportunities/scope in each project. Based on these parameters we decided to choose the Recipe Recommender project for the next phase of the Software Engineering Project.


Before going forward with Recipe Recommender project, let us provide brief reasons for not going forward with other projects:

### 1. ClassMate Bot
 Initially, we successfully set up and ran this project. But we faced some issues while getting it run. Documentation provided many useful set up tips and a video but did not provide enough  resources in case of any issue. Also it was difficult to set up this project mainly due to extensive dependencies and managing their versions. Furthermore, we thought that there is a very limited future scope for this project which is the main reason behind not going ahead with this project.

### 2. MyDollar Bot
We were able to run this project easily as the complete set up guide is provided in the README file of the project repository. Bots are platform dependent and therefore might pose some limitations to further development. Also, we found that future scope provided by the authors is not that substantial. Hence decided to drop the MyDollarBot project.

### 3. GITS
This project is quite interesting and also has fantastic documentation provided with it. This project requires a lot of prerequisite knowledge about GIT and GIT workflow. Basic level queries have already been implemented earlier by authors. Therefore, we felt that it would be difficult and complicated to gain this knowledge and develop a one-shot solution for many other complex GIT queries in such a short period of time. Therefore, we decided to not go forward with the GITS project.

### 4. Feature Hunt
Feature Hunt project uses flask as backend technology. We as a team have very less experience with flask than with other technologies used in the Recipe Recommender Project. Even though this project happens to have a lot of use cases and scope but because of lack of experience with technology, we decided to choose Recipe Recommender project rather than Feature Hunt.


## Project selected for SE Project 2: Recipe Recommender
Recipe recommender as its name suggests recommends recipes based on what ingredients and type of cuisine the user provides. Here the user is anyone who is looking to cook his next meal using the ingredients they have or look up local restaurants that offer a recipe they are looking for. The software aims to help people in deciding their next meal while providing detailed recipe, preparation time, type of cuisine and even providing ratings for the recipes. 

This project uses NodeJs to develop backend and ReactJs to develop frontend. It also uses a mongo database. We were able to set up this project and run it. We faced little to nothing issues while doing so as most of the setup instructions were provided in the documentation. We still had trouble understanding the database structure as some of the data does not reside on the database but saved using csv (comma separated values) file. These files are stored in project file structure only making it difficult to understand the relationships between tables. 

## Practices we will be commiting to avoid difficulties we faced
During the process of project 1, we faced multiple problems with different projects. Following are some of these issues and policies to avoid them. 

#### 1. Documentation Insufficiency
ClassMate Bot documentation provided useful setup tips and a video guide, it didn’t provide any troubleshooting resources. To avoid this issue in future, we would ensure that documentation includes solutions to common issues, frequently asked questions and links to various support platforms such as stackoverflow.


#### 2. Absence of Future Scope in Documentation
MyDollar Bot was a great project but it lacked future scope. Problem we faced was we had to skim through all the projects, understand them,  try to run them and before selecting a project for the next phase come up with significant future goals. Without proper understanding of code it is impossible to come up with significant goals which are implementable without changing any of the previous code. This issue can be avoided by mentioning future scope in the documentation of the project. README file of MyDollar Bot didn’t clearly mention anything about future scope but directed it to open issues. Therefore, we would commit to provide clear future scope for the next phase project.


#### 3. Absence of Prerequisite Knowledge
GITS project requires a lot of GIT commands knowledge. Without this knowledge, it is very difficult to understand and further extend the project. We were unable to find any resource of such prerequisite knowledge to ease our understanding of the project. Hence we would try our best to provide resources or links to tutorials for contributors to gain enough background knowledge about the project.


#### 4. Database Structure
Recipe Recommender, even though we selected this project for the next phase, has some issues which can be resolved. Some of the useful data is stored in csv files which can be transferred to the database using appropriate tables to ease the data handling and security. Also since it’s an open source project, a documentation section about Database Tables Relationships would be beneficial.


Above were some of the major issues we faced during this phase of the project and policies which we would like to implement in our next phase project to avoid them.
