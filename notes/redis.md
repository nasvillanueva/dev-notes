# Redis

* MISCONF Redis is configured to save RDB snapshots... :
> MISCONF Redis is configured to save RDB snapshots, but is currently not able to persist on disk. Commands that may modify the data set are disabled.
>
> execute `redis-cli config set stop-writes-on-bgsave-error no`
