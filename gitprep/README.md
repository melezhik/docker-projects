# SYNOPSIS

Builds docker image with GitPrep server installed.


# USAGE

    # build an image with target melezhik/gitprep
    # you probably will need to run this command more than once
    # if meet "Installing the dependencies failed: Installed version (1.636) of DBI is not in range '== 1.634'"
    # error
    $ sudo docker build -t melezhik/gitprep .

    # run gitprep server
    $ sudo docker run -p 10020:10020 -d -i melezhik/gitprep

    # test it!
    curl 127.0.0.1:10020

# AUTHOR

[Alexey Melezhik](mailto:melezhik@gmail.com)


