# Introduction to spatial computational programming

This course is to serve as an introductory level to spatial workflows in computation,and modern day software engineering.
It assumes basic knowledge of basic spatial operations.

They are quite a number of programming languages used in the geospatial domain from ***python , javascript, c++, spark, scala to R*** . Each of the languages have their pro`s and cons from speed to verbosity or even meer popularity; but the type of mentality one should have is that "whatever can be done in one language can be done in any other programming language" and there are existing inter-language wrapper to access functionality  between one another. For example GDAL(Geospatial data abstraction Library) one of the most used software for different spatial file formats I/O and conversion is written in C++ but the functionality can be accesed in R using **rgdal** or python using **pygdal** from osgeo.

Since this module is not focused on any specific subdomain of geospatial industry, the language used will be python and reletated modules for the spatial operations.

>>>>> Spatial visualization: R, javascript, python, etc.

>>>>> Geoprocessing and/or Geostatistics: python, R,Spark, C++, C#,octave etc

>>>>> Spatial web development: Javascript, python, R, C++,C#,Scala.etc

>>>>> Raster Processing:  C++, python, R, Javascript,C++, Matlab, octave etc

*Above list is not definitive but just to show how the same tools can be used to achieve similar tasks, thus it's adviceable to pick the tool(your swiss knife) that you can obtain the end results without a steep learning curve and is comfortable with*

This material does not serve as a complete guide to spatial analytics and geoprocessing but as an appetizer to solving basic spatial problems by designing simple algorithms and re-use of already exiting ones without "re-inventing the wheel" and keeping it DRY(don't repeat yourself technique) using python programming language..

The main goal of is to provide a programmer/computer science set of thinking to the students participating.

#### Objectives of the Presentation
________________________________

## Pre-course
>> - **Overview of version control system (git) and github/gitlab/atalassian repositories**
        

        Software used to keep track of your files and backing up online.
        This proves vital in collaboratory research and programming; also at a personal level to manage your files.
        [link to git ](git software capentries)
        [link to git](atlassian intro to git)
        [progit link](link to progit  book)

>> - **Brief discussion on using *nix based shell/terminal/command prompt**

        Text based set of programs that ships default with your pc/laptop that proves helpful in writing automation scripts
        navigating through directories/folder, files. Before the rise of the Graphical User Interfaces laptops were text based where instead 
        the beautiful User interfaces back in the 70's. 
        
        With the current progress made in cloud computing, familiarity in the *nix based commands gives the student an easy time through 
        prefered cloud service e.g google GCE, amazon AWS etc
        [link](to linux sw capentries)
        [link](to ess-edu resource)

>> - **Introduction to computational thinking with python**