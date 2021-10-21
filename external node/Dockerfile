FROM nginx:1.15-alpine

COPY start.sh /usr/local/bin/

RUN apk add --no-cache curl jq python3 py3-pip

RUN apk add --update bash \
	&& rm -rf /var/cache/apk/* \
	&& chmod +x /usr/local/bin/start.sh

EXPOSE 443

CMD ["start.sh"]