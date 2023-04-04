FROM python:3.5
RUN pip3 install flask && pip3 install redis
COPY app.py /opt
EXPOSE 5000
CMD ["python3", "/opt/app.py"]
