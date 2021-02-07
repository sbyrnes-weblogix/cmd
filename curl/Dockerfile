FROM ubuntu
RUN apt-get update && apt-get install -y curl jq && apt-get clean && rm -rf /var/lib/apt/lists
ENTRYPOINT ["curl"]

