ARG base_image=ubuntu:bionic
FROM ${base_image}

ADD https://repo.spring.io/libs-release/io/spring/concourse/releasescripts/concourse-release-scripts/0.3.2/concourse-release-scripts-0.3.2.jar /opt/concourse-release-scripts.jar

RUN apt-get update && apt-get install --no-install-recommends -y \
    git gnupg \
 && rm -rf /var/lib/apt/lists/*
