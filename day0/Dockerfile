FROM python:3

WORKDIR /App
COPY . /App

RUN pip install -r requirements.txt

ENTRYPOINT ["python3"]
CMD ["app.py"]