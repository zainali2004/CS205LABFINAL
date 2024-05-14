
FROM python:3.9-slim
WORKDIR /app
COPY PythonFiles/server/requirements.txt. /app/
RUN pip install -r requirements.txt
COPY /home/pc17/CS205L_Final/PythonFiles/server/app/server.py /app/
EXPOSE 5000
CMD ["flask", "run", "--host=0.0.0.0", "--port=5000"]