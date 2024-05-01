FROM python:3.9
WORKDIR /app
COPY script.py /app
COPY requirements.txt /app
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 5000
CMD ["python", "script.py"]
