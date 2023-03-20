FROM python:3.6-slim
WORKDIR /usr/src/app
COPY . .
RUN pip install pipenv
RUN pipenv install
EXPOSE 5000
CMD ["echo", "DOCKER BUILD COMPLETED!............"]
CMD ["pipenv", "run", "python", "flask-html.py"]
