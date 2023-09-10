FROM jupyter/minimal-notebook

COPY ./requirements.txt /tmp/requirements.txt
RUN pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
RUN pip install -r /tmp/requirements.txt
