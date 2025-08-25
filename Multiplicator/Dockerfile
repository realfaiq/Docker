# base image
FROM python:3.13

# workdir
WORKDIR /app

# copy
COPY . /app

# run
RUN pip install -r requirements.txt

# command
CMD ["python3", "./app.py"]