
FROM python:3.9-slim
WORKDIR /app
COPY PythonFiles/client/app/requirements.txt /app/
RUN pip install -r requirements.txt

COPY  /home/pc17/CS205L_Final/PythonFiles/client/app/client.py /app/

CMD ["python", "app.py"]