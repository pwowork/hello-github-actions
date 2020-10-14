FROM debian:9.5-slim

ADD launcher.sh /launcher.sh
ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /launcher.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/launcher.sh"]
