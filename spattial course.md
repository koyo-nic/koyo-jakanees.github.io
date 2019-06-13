
# Introduction to Spatial Computational Programming.  
###### Jakanees 2019-06-08 
___

This course is to serve as an introductory level to spatial workflows in computation,and modern day geospatial engineering and product dissemination.

It assumes basic knowledge of basic spatial operations.

They are quite a number of programming languages used in the geospatial domain from ***python , javascript,R, C/C++, spark, scala, to Rust*** . Each of the languages have their pro`s and cons from speed to verbosity or even meer popularity; but the type of mentality one should have is that "whatever can be done in one language can be done in any other programming language" and there are existing inter-language wrapper to access functionality  between one another. For example GDAL(Geospatial data abstraction Library) one of the most used software for different spatial file formats I/O and conversion is written in C++ but the functionality can be accesed in R using **rgdal** or python using **pygdal** from osgeo.

Since this module is not focused on any specific subdomain of geospatial industry, the language used will be python and reletated modules for the spatial operationsin the free and opensource scope therefore proprietory modules will not be subject to this scope.

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
>> - **Git for Spatial Scientists:**
*Overview of version control system (git) and github/gitlab/atalassian repositories*
        
        Software used to keep track of your files and backing up online.
        This proves vital in collaboratory research and programming; also at a personal level to manage your files
        use of 'pull/push, merge, commit, clone'.
        [link to git ](git software capentries)
        [link to git](atlassian intro to git)
        [progit link](link to progit  book)
        If comfortable enough, check geogit documentation/installation and give it a go.
        Include short tutorial on github flavoured markdown for emphasis on documentation of workflows

>> - **Introduction to terminal/shell**
*Brief discussion on using 'nix based shell/terminal/command prompt*

        Text based set of programs that ships default with your pc/laptop that proves helpful in writing automation scripts
        navigating through directories/folder, files. Before the rise of the Graphical User Interfaces laptops were text based where instead 
        the beautiful User interfaces back in the 70's. 
        
        With the current progress made in cloud computing, familiarity in the *nix based commands gives the student an easy time through 
        prefered cloud service e.g google GCE, amazon AWS etc
        [link](to linux sw capentries)
        [link](to ess-edu resource)

>> - **Introduction to computational thinking with python**
*Overview of programming thinking in solving obvious and ubiquitious real world problems using computer science principles and python programming*

____________________________________________________________________________________________________________________
_____________________________________________________________________________________________________________
>>>**Essential Concepts**
_______________________________________________________________________
 > *An excerpt from [Computational Models](http://ksuweb.kennesaw.edu/~jgarrido/computational.html) Dr. Jose M. Garrido 2016*
>>A computational model is a computer implementation of the solution to a (scientific) problem for which a 
>> mathematical representation has been formulated. Developing a computational model includes formulating the
>> mathematical model and implementing it by applying Computer Science concepts, principles and methods such as: 
>>**abstraction, decomposition, specification, conceptual modeling, programming, data structures, algorithms, design**
>>**structures, verification, and validation.** Computational modeling is the foundation of Computational Science.
>> Abstraction is recognized as a fundamental and essential principle in problem solving and software development.
>>
>> Computational Science integrates concepts and principles from applied mathematics and computer science and >>applies them to the various scientific and engineering disciplines.
>>
>> Computational science is an emerging area (or discipline) that involves developing computational models applied in various areas of science and engineering to solve large-scale (and complex) scientific problems.
>>
>> Computational Thinking is required for any problem that involves calculations. This involves deciding: what ??>>calculations use what values, and the order in which the calculations must occur. It usually requires >>multi-disciplinary and team work.
>>
>> Computational thinking is the ability to describe the requirements of a problem, design a mathematical solution >>to the problem, and implement the solution in a computer.
>>
>> Large and complex computational models usually require high performance computing resources to execute and the >>models are used to study the behavior of large and complex real systems or  processes. 
_______________________________________________________________________________________________________
_____________________________________________________________________________________________________
Understanding the concepts of solving problems systematically and designing the solutions to this problems(recursively and algorithmically) using code.
Derive and write simple programs to compute cuberoot, pallidrome strings etc without using in built modules or functions.
        
Emphasis of this section is not to memorise the syntax of python language but how to design and descibe each and every single step of the solution in simple plain english, then worry about the code implementation afterwards.
        
At the end the student should be familiar with python syntax style, defining functions, variable creation and assignment, different data type and the declaration, control flow and branching.
        
introduction to external modules and libraries: How they are installed and can be accessed e.g. Numpy, Bokeh, fiona,shapely, rasterio, pysal, pandas, geopandas.
> **Familiarity with Numpy and Pandas** 
python modules used in numeric computation and read data tables is desired but not reguired
[python Dev stack](https://gistbok.ucgis.org/bok-topics/python-gis#DevStack) open source modules.
[awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial)