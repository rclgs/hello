FROM python@sha256:99100de0b8685fedd2d686d4a1ded176486825cf54fec5c32da7c64f01936920
COPY --from=ghcr.io/astral-sh/uv:latest /uv /uvx/ /bin/

ADD . /app
WORKDIR /app
RUN uv sync --locked

EXPOSE 8000

CMD ["uv", "run", "python", "manage.py", "runserver", "0.0.0.0:8000"]