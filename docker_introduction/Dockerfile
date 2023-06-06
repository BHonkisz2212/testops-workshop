FROM python:3.12.0b1-slim-buster
WORKDIR /app
COPY --from=builder /app/output.txt .
COPY script.py .
CMD ["python", "script.py"]
# uzyjemy nowego obrazu pythonowego
# wyswietlimy zawartosc pliku przez uruchomienie skryptu pythonowego jako entrypoint