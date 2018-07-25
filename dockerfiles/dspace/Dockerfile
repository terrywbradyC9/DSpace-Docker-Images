FROM alpine/git as clone
ARG DSPACE_BRANCH=dspace-6_x
ENV DSPACE_GIT https://github.com/DSpace/DSpace.git

WORKDIR /app

ADD * /app/
RUN ls -l
RUN find /app -print
