FROM python:3.9

EXPOSE 5005

WORKDIR /Part7


COPY requirements.txt /Part7
RUN pip install  -r requirements.txt --upgrade pip

COPY . /Part7

CMD python app.py