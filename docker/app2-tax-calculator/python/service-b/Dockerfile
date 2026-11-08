FROM python:3.11.15-alpine3.22
WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
EXPOSE 4000
CMD [ "python", "main.py" ]