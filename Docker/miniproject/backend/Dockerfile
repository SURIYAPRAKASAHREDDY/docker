# FROM python:3.9
# WORKDIR /app
# COPY . .
# RUN pip install -r requirements.txt
# EXPOSE 5000
# CMD ["python", "app.py"]


FROM python:3.10

WORKDIR /app
COPY . .

RUN pip install flask mysql-connector-python

CMD ["python", "app.py"]
