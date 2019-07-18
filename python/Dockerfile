ARG python_version
ARG alpine_version
FROM python:${python_version}-alpine${alpine_version}
COPY ./requirements.txt /tmp/requirements.txt
RUN pip install -r /tmp/requirements.txt
WORKDIR /var/src
CMD /bin/sh
