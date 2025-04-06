FROM microsoft/mssql-server-linux:2022-latest

COPY . /usr/src/docker

WORKDIR /usr/src/docker

# これをするとSQL Server を起動してくれるらしい
CMD /bin/bash ./entrypoint.sh