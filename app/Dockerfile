#linux containers
FROM python:alpine3.8

#windows containers
#FROM winamd64/python

#RUN pip install --upgrade pip \
# && pip install flask

# Install Flask server
RUN pip install flask 

# Copy local directory "src" to container filesystem "/src"
COPY src /src

EXPOSE 80

CMD ["python", "/src/main.py"]
