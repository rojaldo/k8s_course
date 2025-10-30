FROM python:3.12-slim-bullseye
# install app from my_dir
COPY ./my_dir /my_dir
WORKDIR /my_dir
# install dependencies
RUN pip install -r requirements.txt
# run app
CMD ["python", "app.py"]