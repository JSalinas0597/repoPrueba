FROM python

EXPOSE 5000

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt --break-system-packages

CMD python run.py
