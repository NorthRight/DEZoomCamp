FROM python:3.10

RUN pip install pandas

WORKDIR /Week1
COPY pipeline.py pipeline.py

# ENTRYPOINT [ "bash" ]
ENTRYPOINT [ "python","pipeline.py" ]