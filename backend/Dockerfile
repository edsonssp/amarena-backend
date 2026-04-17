FRFROM python:3.11-slim

WORKDIR /app

COPY requisitos.txt .
RUN pip install --no-cache-dir -r requisitos.txt

COPY . .

EXPOSE 8001

CMD uvicorn servidor:app --host 0.0.0.0 --port ${PORT:-8001}
Clique em "Commit changes"
