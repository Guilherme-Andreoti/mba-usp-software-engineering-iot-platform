FROM grafana/grafana:latest

WORKDIR /usr/src/app

COPY ./grafana.ini /etc/grafana/grafana.ini

COPY ./datasources/ /etc/grafana/provisioning/datasources/
COPY ./dashboards/ /etc/grafana/provisioning/dashboards/

EXPOSE 3000

CMD ["/run.sh"]