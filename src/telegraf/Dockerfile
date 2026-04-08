FROM telegraf:1.38.0

RUN apt-get update && apt-get install -y speedtest-cli && rm -rf /var/lib/apt/lists/*

COPY telegraf.conf /etc/telegraf/telegraf.conf
