+++
date = 2021-02-01T00:00:00  # Schedule page publish date.

title = "Missing Data and Multiple Imputation"

time_start = 2021-02-01T12:30:00
time_end = 2021-03-29T13:20:00

abstract = "Real world data is rarely even complete and missing data is more the rule than the exception.  Instead of ignoring this fact and analyzing only complete cases, you will learn how to report missing data and incorporate them into your analysis."

abstract_short = "Missing Data and Multiple Imputations"

event = "Stat Studio Workshops"

event_url = "https://www.eventbrite.com/o/usu-cehs-statistical-consulting-studio-13278759178"

location = "Zoom Video Conferencing (register to receive the link and password)"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects (i.e. teaching classes).
#   Simply enter the filename (excluding '.md') of your project file in `content/teaching/`.
teaching = ["SSworkshops"]

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "workshops/StatStudio_workshop_missingdata_header.PNG"
caption = "Stat Studio Workshop: Missing Data and Multiple Imputations"

+++

What is the difference between MCAR, MAR, MNAR?  We will cover the difference between these three, as well as how to distinguish (test) which type describes the underlying mechanism that is likely responsible for the generation of missingness in specific data, as well what this distinction implies for options forward.

Historically, simplistic and sub-optimal methods have been used for dealing with missing data: complete case analysis, single value imputation (mean, regression, hot decking, ect.).  No matter the method used to deal with missing data, similar reporting of the extent of missingness and proposed mechanism is always required.

Multiple imputations (MI) is conducted in 3 stages: imputation, analysis, and pooling.  We will focus on Multivariate Imputation by Chained Equations (MICE), an MCMC algorithm for imputation, and Rubin’s rules for pooling.  We will apply this process for various inferential techniques, including t-tests, ANOVA-based methods, and regression analysis.

Application of MI will be expanded to more complex situations: planned missing designs and multilevel/hierarchical sampling structures.
