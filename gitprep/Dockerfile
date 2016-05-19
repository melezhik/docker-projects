FROM perl:5.20
RUN apt-get update
RUN apt-get install sudo
RUN cpanm Sparrow
RUN sparrow index update
RUN sparrow plg install gitprep
RUN sparrow plg run gitprep
ENTRYPOINT ["sparrow"]

