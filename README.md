![SRIJAS_LOGO](https://user-images.githubusercontent.com/40118578/135184051-73acf9be-07c1-4c98-9730-68fa161f6a1b.png)



[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Github](https://img.shields.io/badge/language-python-red.svg)
![GitHub issues](https://img.shields.io/github/issues-raw/ineelshah/SRIJAS)
![Github closes issues](https://img.shields.io/github/issues-closed-raw/ineelshah/SRIJAS)
![Github pull requests](https://img.shields.io/github/issues-pr/ineelshah/SRIJAS)
![Github closed pull requests](https://img.shields.io/github/issues-pr-closed/ineelshah/SRIJAS)
[![DOI](https://zenodo.org/badge/408230160.svg)](https://zenodo.org/badge/latestdoi/408230160)
[![Build Status](https://app.travis-ci.com/ineelshah/SRIJAS.svg?branch=main)](https://app.travis-ci.com/ineelshah/SRIJAS)
[![codecov](https://codecov.io/gh/ineelshah/SRIJAS/branch/main/graph/badge.svg?token=Z9MGKKAXN6)](https://codecov.io/gh/ineelshah/SRIJAS)
![version](https://img.shields.io/badge/version-1.0-blue)
![github workflow](https://github.com/ineelshah/SRIJAS/actions/workflows/unit_test.yml/badge.svg)
![github workflow](https://github.com/ineelshah/SRIJAS/actions/workflows/style_checker.yml/badge.svg)
![github workflow](https://github.com/ineelshah/SRIJAS/actions/workflows/main.yml/badge.svg)
![github workflow](https://github.com/ineelshah/SRIJAS/actions/workflows/code_formatter.yml/badge.svg)
![github workflow](https://github.com/ineelshah/SRIJAS/actions/workflows/code_cov.yml/badge.svg)
![github workflow](https://github.com/ineelshah/SRIJAS/actions/workflows/close_as_a_feature.yml/badge.svg)
![github workflow](https://github.com/ineelshah/SRIJAS/actions/workflows/Respost.yml/badge.svg)


https://user-images.githubusercontent.com/25223347/135366127-f6b741f2-de85-4d64-92c9-cd1d2f518090.mp4





# S.R.I.J.A.S.
## Job Search was never this easy
Smart-Resume-Interpreter-And-Job-Alert-System is an application that makes your job search easy and less frustrating.
With SRIJAS, you can upload your resume and job which you want to search for. The application will browse Linkedin and Glassdoor websites to search for the jobs.
The links of the jobs that matches with the skills in your resume, will be sent to you via email.

This is our submission for the Project for Software Engineering CSC 510 Fall 2021.

## Infrastructure Description:
![Infrastructure](https://github.com/ineelshah/SRIJAS/blob/main/images/Infrastructure.jpg)

## Database Schema:
![DB_Schema](https://github.com/ineelshah/SRIJAS/blob/main/images/DB_Schema.jpg)

## Overview
<table border="2" bordercolorlight="#b9dcff" bordercolordark="#006fdd">

  <tr style="background: #010203 ">
    <td valign="left"> 
      <p style="color: #FF7A59"> 1.This is the main SRIJAS web page 
      </p>
      <a href="./images/home_page.png"> 
        <img src="./images/home_page.png" >      
      </a>
    </td>
    <td valign="center"> 
      <p style="color: #FF7A59"> 2.User have to upload their resume file and enter the details
      </p>
      <a href="./images/resume_upload.png">
        <img src="./images/resume_upload.png"> 
      </a>
    </td>
  </tr>
  <tr style="background: #010203;"> 
    <td colspan = "2">
      <p style="color: #FF7A59"> 3.The application matches the job postings with the skills and send email to the user.
      </p>  
      <a href="./images/email.PNG">
        <img src="./images/email.PNG">    
      </a>
     </td>
    </td>
  </tr>
  </table>

## Plan Of Action:

### Phase 1:
- [ ] Designing the infrastructure for hosting the web application, database and other required services.
- [ ] Taking Resume, User Email and other basic User Details from the User using a portal.
- [ ] Design Database to support all phases of development.
- [ ] Scraping data from job posting websites like LinkedIn.
- [ ] Developing an Email or Notification Service.
- [ ] Extract knowledge from scraped data.
- [ ] Match user skillsets with the skillsets extracted from scraped data.


### Phase 2:
- [ ] Take more advanced filters from the user.
- [ ] Allow users to choose the threshold of matching of Skills.
- [ ] Integrate the basic portal with a login service.
- [ ] Create a system that stores user profiles and can generate insights from it.
- [ ] Allow users to select previously uploaded resumes.

### Phase 3:
- [ ] Develop a dashboard.
- [ ] Summarize and generate a graph about how the user's resume has progressed.
- [ ] Allow users to generate insights from how the uploaded resume compares with job descriptions in the market.
- [ ] Generate insights from all collected data.

🔱: Installation
---
1. Clone the Github repository to a desired location on your computer. You will require [git](https://git-scm.com/) to be preinstalled on your machine. Once the repository is cloned, you will then ```cd``` into the local repository.
```
git clone https://github.com/ineelshah/SRIJAS.git
cd SRIJAS
```
2. This project uses Python 3, so make sure that [Python](https://www.python.org/downloads/) and [Pip](https://pip.pypa.io/en/stable/installation/) are preinstalled. All requirements of the project are listed in the ```requirements.txt``` file. Use pip to install all of those.
```
pip install -r requirements.txt
```

Contributors
---
<table>
  <tr>
    <td align="center"><a href="https://github.com/ineelshah"><img src="https://avatars.githubusercontent.com/u/40118578?v=4" width="75px;" alt=""/><br /><sub><b>Neel Shah</b></sub></a></td>
    <td align="center"><a href="https://github.com/PvPatel-1001"><img src="https://avatars.githubusercontent.com/u/69849039?v=4" width="75px;" alt=""/><br /><sub><b>Parth Patel</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/ameyatathavadkar"><img src="https://avatars.githubusercontent.com/u/25223347?v=4" width="75px;" alt=""/><br /><sub><b>Ameya Tathavadkar</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/jayrshah98"><img src="https://avatars.githubusercontent.com/u/41386638?s=400&u=b323434b42507c474829a804556d69da82d48c3f&v=4" width="75px;" alt=""/><br /><sub><b>Jay Shah</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/Harshil-Shah99"><img src="https://avatars.githubusercontent.com/u/38115399?v=4" width="75px;" alt=""/><br /><sub><b>Harshil Shah</b></sub></a><br /></td>
  </tr>
</table>

