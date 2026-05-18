FROM debian:stable-slim
LABEL maintainer="enrico.simonetti@gmail.com"

RUN useradd --system --no-create-home --shell /usr/sbin/nologin sugar

COPY apps/sugarfixpermissions /usr/local/bin/sugarfixpermissions
RUN chmod +x /usr/local/bin/sugarfixpermissions

CMD ["/usr/local/bin/sugarfixpermissions"]
