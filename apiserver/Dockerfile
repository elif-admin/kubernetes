FROM python:alpine
COPY . /app
WORKDIR /app
RUN pip install -r ./apiserver/requirements.txt
EXPOSE 80
CMD python ./apiserver/app.py
