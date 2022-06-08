# Sphinx-doc using .md file format


Clone the repo


For documentation we are going to use sphinx and will be using .md format: 


```pip3 install sphinx```

```pip3 install recommonmark```

```pip3 install sphinx_rtd_theme```



- inside the main directory you will find **source** folder.
- Create your .md files inside source folder 
- Change the name of project, title author in *conf.py* file
- add file names .md files  in *index.rst* file. eg. test.md hass been added indide *index.rst*


for building the md file run the following command:

```sphinx-build -b html source/ build/html```

Open index.html file(inside build/html directory) in a browser by double clicking on the file.



