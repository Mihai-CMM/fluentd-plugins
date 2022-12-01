# fluentd-plugins
bitnami fluentd with mongo and psql plugins

This is just an extension of bitnami/fluentd container to use also mongo and psql/mysql outputs

##
RUN  fluent-gem install fluent-plugin-mongo -v 0.7.12
RUN  fluent-gem install fluent-plugin-sql
RUN  fluent-gem install pg -v 1.4.5
##

Everything else needed is on their Bitnami github and web

If you really need my image you can change bitnami chart to

.....
image:
  registry: docker.io
  repository: costache2mihai/fluentd-plugins
  tag: latest
.....
