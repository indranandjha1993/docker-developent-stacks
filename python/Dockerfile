FROM python:latest

COPY src/ /python

WORKDIR /python

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]
