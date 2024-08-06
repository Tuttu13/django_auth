FROM python:3.12
ENV PYTHONUNBUFFERED 1
WORKDIR /apps/backend

RUN ls -la /app/backend || true

COPY app/backend/requirements.txt /apps/backend/requirements.txt

RUN ls -la /apps/backend

COPY app/backend /apps/backend

RUN ls -la /apps/backend

RUN pip install --upgrade pip
RUN pip install -r /apps/backend/requirements.txt
