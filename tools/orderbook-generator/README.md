# Order Book Generator

## Prerequisites
1. Install redis-server (e.g. `apt-get install redis-server`)
2. Install Python 3.6
3. Install Python dependencies (`pipenv install`)


## Running it
Assuming Redis is installed and its' server is at `/usr/local/bin/redis-server`:

    $ python -m generator.conductor --redis-server-cmd /usr/local/bin/redis-server
    
For additional options run:

    $ python -m generator.conductor -- --help


## Output
Redis dump file (`dump.rdb`) will be in `/output/method/TIMESTAMP` directory.