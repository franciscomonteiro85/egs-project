# Dockerfile

# pull the official docker image
FROM python:3.9.4-slim

RUN mkdir /stock
# set work directory
WORKDIR /stock

# # set env variables
# ENV PYTHONDONTWRITEBYTECODE 1
# ENV PYTHONUNBUFFERED 1

# install dependencies
COPY requirements.txt .
RUN pip install -r requirements.txt

# copy project
COPY . .

# EXPOSE 8080/tcp

# ENTRYPOINT ["uvicorn", "stock.main:app"]

