
talcat
======


## Why

Because.

## What

A `socat;netcat`-enabled bi-directional audio transmission utility.

## How

#### As a service consumer

    git clone git@github.com:docteurklein/talcat.git
    cd talcat
    ./bin/talcat <username-you-want-to-correspond-to>

### As a service provider


    git clone git@github.com:docteurklein/talcat.git
    cd talcat
    ./bin/get &
    ./bin/put &
    tail -f logs

