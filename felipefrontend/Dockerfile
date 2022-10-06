FROM python:3.6

RUN pip install -r requirements.txt

COPY app.py /opt/

ENTRYPOINT [ "FLASK_APP=/opt/app.py", "flask run --host=0.0.0.0" ]