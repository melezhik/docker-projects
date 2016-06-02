FROM perl:5.20
RUN apt-get update
RUN apt-get install sudo
RUN apt-get install git-core
RUN cpanm Sparrow
RUN sparrow index update
RUN sparrow index summary
RUN sparrow plg install gitprep
RUN sparrow plg run gitprep
CMD sparrow plg run gitprep --param action=start --param start_mode=foreground

