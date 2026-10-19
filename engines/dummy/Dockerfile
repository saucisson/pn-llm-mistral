FROM python:3.14-slim
RUN useradd -m runner
COPY entrypoint.py /entrypoint.py
USER runner
ENTRYPOINT ["python", "/entrypoint.py"]
