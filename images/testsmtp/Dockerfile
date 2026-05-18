FROM python:3.11-slim
LABEL maintainer="enrico.simonetti@gmail.com"

EXPOSE 25
ENV PYTHONUNBUFFERED=1
COPY smtp.py smtp.py
CMD ["python3", "smtp.py"]
