FROM python:3
WORKDIR /root/iit/rp_py_app
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
CMD ["python","./rp.py"]
