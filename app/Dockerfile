FROM apache/superset:latest-dev

USER root
#CHANGE LOGO
RUN mv /app/superset/static/assets/images/favicon.png /app/superset/static/assets/images/favicon1.png
RUN mv /app/superset/static/assets/images/superset-logo-horiz.png /app/superset/static/assets/images/superset-logo-horiz1.png
COPY ["favicon.png", "/app/superset/static/assets/images"]
COPY ["superset-logo-horiz.png", "/app/superset/static/assets/images"]

USER superset