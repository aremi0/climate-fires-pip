FROM docker.elastic.co/logstash/logstash:8.13.0

# Add your logstash plugins setup here
RUN logstash-plugin install logstash-codec-csv

# Mount in a docker volume to load dataframe
RUN mkdir /usr/share/logstash/csv

# docker build . --tag incendi:logstash