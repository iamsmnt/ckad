FROM python:3.11-slim


#identify the maintainer of the image
LABEL version="0.0.1"
LABEL maintainers="workingwithsomnath@gmail.com"

#add python code
#1st is the path of the python file and 2nd is the place where the file should be placed /
ADD hello.py /

#execute the python file
CMD [ "python", "./hello.py" ]