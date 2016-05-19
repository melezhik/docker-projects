# SYNOPSIS

Builds docker image with GitPrep server installed


# USAGE

    # build an image with target melezhik/gitprep
    $ sudo docker build -t melezhik/gitprep .

    # run gitprep server
    $ sudo docker run -p 10020:10020 -d -i melezhik/gitprep

