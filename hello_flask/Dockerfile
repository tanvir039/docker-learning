FROM python:3.8-slim
WORKDIR /app
# Copy all files from the current directory to the /app directory (. because we are already in /app -> WORKDIR /app)
COPY . .
RUN pip install flask
EXPOSE 5002
CMD ["python", "app.py"]