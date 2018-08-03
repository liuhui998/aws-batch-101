## Source: https://github.com/HenrikBengtsson/r-base-centos7
## Copyright: Henrik Bengtsson (2017)
## License: GPL (>= 2.1) [https://www.gnu.org/licenses/gpl.html]

FROM centos:centos7

RUN yum -y install which unzip aws-cli
ADD fetch_and_run.sh /usr/local/bin/fetch_and_run.sh
WORKDIR /tmp
USER nobody
ENTRYPOINT ["/usr/local/bin/fetch_and_run.sh"]
