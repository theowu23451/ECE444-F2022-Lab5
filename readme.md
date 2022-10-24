# ECE444-F2022-Lab5 (Group 3)

This repo is a clone of https://github.com/nelaturuk/education_pathways

### Activity 1 Screenshots
![image](https://user-images.githubusercontent.com/50794673/197642899-37c664b9-0da0-48fb-9630-53b0024b10e6.png)
![image](https://user-images.githubusercontent.com/50794673/197642850-9affb60d-398d-4c93-a8e8-965207679beb.png)

### Activity 2-5 Screenshots
#### Home Page
![image](https://user-images.githubusercontent.com/50794673/197642980-76a66ac6-3351-4224-b5dc-a6ba29eb93aa.png)

#### Results Page - Form
![image](https://user-images.githubusercontent.com/50794673/197643037-24404886-129f-47b1-b4cc-1c38cef47969.png)

#### Results Page - Results
![image](https://user-images.githubusercontent.com/50794673/197643057-6aee059e-e104-4e67-8ae1-3a7f3651ca71.png)

### Activity 6 Screenshots
#### User Story 2.1
![image](https://user-images.githubusercontent.com/50794673/197643112-f2c80168-ef94-4335-b3c3-ff77a8274b5c.png)
![image](https://user-images.githubusercontent.com/50794673/197643120-3ea090cc-eddb-4835-81bb-2978f91d2446.png)

#### User Story 3.1
![image](https://user-images.githubusercontent.com/50794673/197643569-e5c2bd62-73e2-464d-9c23-ecad21d06d16.png)
<img width="1361" alt="image" src="https://user-images.githubusercontent.com/45493463/197645746-22f544ea-81e7-4644-bd78-f23d1564ff04.png">


#### User Story 3.2
![image](https://user-images.githubusercontent.com/50794673/197643134-d8b21196-f88b-415d-908a-02032c09c96a.png)
![image](https://user-images.githubusercontent.com/50794673/197643603-0f141db2-58cd-4da6-8549-49a94396cd46.png)

## CARTE Education Pathways

### Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

### Setup Instructions

#### With Docker


### Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
