# install-redis-on-freeBDS
Installing instruction of Redis server on freeBDS machine

## Step 1
`sudo pkg install redis`

===>  CONFIGURATION NOTE:

To setup "redis" you need to edit the configuration file:/usr/local/etc/redis.conf

To run redis from startup, add redis_enable="YES" in your /etc/rc.conf.

## Step 2
To run redis server `redis-server`

## Step 3
To run redis client `redis-cli`
