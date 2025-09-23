FROM bde2020/hadoop-nodemanager:2.0.0-hadoop3.2.1-java8
USER root
RUN apt-get update && apt-get install -y --no-install-recommends python3 ca-certificates && rm -rf /var/lib/apt/lists/*
RUN ln -sf /usr/bin/python3 /usr/local/bin/python3
USER root
