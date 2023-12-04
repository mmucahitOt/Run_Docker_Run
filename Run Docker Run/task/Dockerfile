# Write the codes below!

FROM python:3.11-slim

EXPOSE 8000

WORKDIR "/home/app"

ADD . "/home/app"

RUN pip install -r ./hyper-app/requirements.txt

ENTRYPOINT ["python3", "./hyper-app/main.py"]

