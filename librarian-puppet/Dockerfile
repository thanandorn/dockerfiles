FROM centos:latest
MAINTAINER tron@bashton.com

RUN yum -y install ruby-devel ruby make gcc git
RUN echo "gem: --no-ri --no-rdoc" > ~/.gemrc
RUN gem install puppet -v 4.2.0
RUN gem install librarian-puppet -v 2.2.1

ENTRYPOINT ["librarian-puppet"]
CMD ["install"]
