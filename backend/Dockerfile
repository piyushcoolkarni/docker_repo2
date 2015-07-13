FROM www.cybage-docker-registry.com:9080/nodebase

RUN mkdir -p "/data/artifact"

#steps for copying src to container for frontend
COPY components config controllers initializers models utility node_modules app.js Gruntfile.js package.json /data/artifact/

WORKDIR /data/artifact

CMD "grunt run"
