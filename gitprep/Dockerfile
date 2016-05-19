FROM perl:5.20
RUN cpanm Sparrow
RUN sparrow index update
RUN sparrow plg install gitprep
RUN sparrow plg run gitprep
