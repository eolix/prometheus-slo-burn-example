FROM prom/prometheus

COPY *.yml /etc/prometheus/

# Tests your rules before starting
RUN promtool check rules /etc/prometheus/*.rules.yml
