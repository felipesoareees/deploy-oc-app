FROM python:3.6

EXPOSE 8000

WORKDIR /opt

COPY frontend.py .
COPY requirements.txt . 

RUN pip3 install -r requirements.txt

CMD [ "python", "frontend.py"]
