ARG PYTHON_VERSION
FROM python:${PYTHON_VERSION}

RUN curl -sSL https://install.python-poetry.org | python -
ENV PATH="/root/.local/bin:$PATH"
RUN poetry --version

ENTRYPOINT /bin/bash
