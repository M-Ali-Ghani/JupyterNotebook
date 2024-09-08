FROM python:3.12-slim

RUN mkdir Jupyter

WORKDIR /Jupyter/

COPY . /Jupyter/

RUN pip install Jupyter

EXPOSE 8888

CMD ["jupyter","notebook","--ip=0.0.0.0","--allow-root","--no-browser"]
