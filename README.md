# poetry-python-distroless
An example dockerfile that uses distroless image in the final stage of a docker build for python and poetry.

This was written for a fastapi project run with uvicorn. Just putting it out there in case anyone runs into the issues I had!


This is based on the [google recommendations](https://github.com/GoogleContainerTools/distroless/blob/main/examples/python3-requirements/Dockerfile)

I also looked at [this](https://github.com/hkiang01/distroless-python-poetry/blob/main/Dockerfile) example to get started, but ended up using poetry a different way.
