FROM python:3.6.0-alpine

WORKDIR  /app
ADD requirements.txt /app
RUN pip3 install -r requirements.txt
ADD . /app
EXPOSE 500


ENTRYPOINT ["python3", "post_app.py"]
