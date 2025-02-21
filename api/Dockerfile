FROM python:3.9


WORKDIR /code

COPY ./requirements.txt /code/requirements.txt


RUN pip install -r /code/requirements.txt


COPY . /code


EXPOSE 8000

# Define the command to run your app
CMD ["python",  "main.py"]