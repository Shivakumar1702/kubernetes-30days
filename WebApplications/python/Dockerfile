FROM python:latest
LABEL createdby="shiva"
WORKDIR /usr/src/app
RUN pip install Flask
COPY app.py .
CMD [ "python", "./app.py" ]