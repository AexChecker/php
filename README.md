# Generic PHP docker container

## Supported tags and respective `Dockerfile` links:

- [`7.1-2.0.1`, `7.1`, `latest` (*7.1/Dockerfile*)](https://github.com/AexChecker/php/blob/2.0.1/7.1/Dockerfile)
- [`7.0-2.0.1`, `7.0`, (*7.0/Dockerfile*)](https://github.com/AexChecker/php/blob/2.0.1/7.0/Dockerfile)
- [`5.6-2.0.1`, `5.6` (*5.6/Dockerfile*)](https://github.com/AexChecker/php/blob/2.0.1/5.6/Dockerfile)
- [`5.3-2.0.1`, `5.3` (*5.3/Dockerfile*)](https://github.com/AexChecker/php/blob/2.0.1/5.3/Dockerfile)

## Environment Variables Available for Customization

| Environment Variable | Type | Default Value | Description |
| -------------------- | -----| ------------- | ----------- |
| PHP_CLI_MEMORY_LIMIT                  | Int    | -1              | |
| PHP_ERROR_REPORTING                   | String | E_ALL           | |
| PHP_TRACK_ERRORS                      | String | On              | | 
| PHP_ERROR_LOG                         | String | /proc/self/fd/2 | |
| PHP_DATE_TIMEZONE                     | String | UTC             | |
| PHP_SENDMAIL_PATH                     | String | sendmail -t -i  | |
| PHP_MYSQLND_COLLECT_STATISTICS        | String | On              | |
| PHP_MYSQLND_COLLECT_MEMORY_STATISTICS | String | On              | |
| PHP_FPM_ERROR_LOG                     | String | /proc/self/fd/2 | |
| PHP_FPM_LOG_LEVEL                     | String | notice          | |
| PHP_FPM_ACCESS_LOG                    | String | /proc/self/fd/2 | |
| PHP_FPM_CATCH_WORKERS_OUTPUT          | String | yes             | |
| PHP_FPM_CLEAR_ENV                     | String | no              | Not available for 5.3 |
| PHP_FPM_LIMIT_EXTENSIONS              | String | .php            | |
| PHP_FPM_MAX_CHILDREN                  | Int    | 4               | |
| PHP_FPM_MAX_REQUESTS                  | Int    | 0               | |
| PHP_FPM_PROCESS_IDLE_TIMEOUT          | Int    | 30              | |
| PHP_MEMORY_LIMIT                      | Int    | 2048M           | |
| PHP_MAX_EXECUTION_TIME                | Int    | 300             | |
| PHP_MAX_INPUT_TIME                    | Int    | 60              | |
| PHP_MAX_INPUT_VARS                    | Int    | 2000            | |
| PHP_POST_MAX_SIZE                     | String | 512M            | |
| PHP_UPLOAD_MAX_FILESIZE               | String | 512M            | |
| PHP_DISPLAY_ERRORS                    | String | On              | |
| PHP_DISPLAY_STARTUP_ERRORS            | String | On              | |
| PHP_XDEBUG                            | Bool   | 0               | |
| PHP_XDEBUG_DEFAULT_ENABLE             | Int    | 0               | |
| PHP_XDEBUG_REMOTE_ENABLE              | Int    | 1               | |
| PHP_XDEBUG_REMOTE_PORT                | Int    | 9000            | |
| PHP_XDEBUG_REMOTE_AUTOSTART           | Int    | 1               | |
| PHP_XDEBUG_REMOTE_CONNECT_BACK        | Int    | 1               | |
| PHP_XDEBUG_REMOTE_HOST                | Bool   | localhost       | |
| PHP_XDEBUG_MAX_NESTING_LEVEL          | Int    | 512             | |
| PHP_LOG_ERRORS_MAX_LEN                | Int    | 1024            | |
| PHP_IGNORE_REPEATED_ERRORS            | String | Off             | |
| PHP_IGNORE_REPEATED_SOURCE            | String | Off             | |
| PHP_OPCACHE_ENABLE                    | Int    | 1               | |
| PHP_OPCACHE_VALIDATE_TIMESTAMPS       | Int    | 1               | |
| PHP_OPCACHE_REVALIDATE_FREQ           | Int    | 2               | |
| PHP_OPCACHE_MAX_ACCELERATED_FILES     | Int    | 20000           | |
| PHP_OPCACHE_MEMORY_CONSUMPTION        | Int    | 128             | |
| PHP_OPCACHE_INTERNED_STRINGS_BUFFER   | Int    | 16              | |
| PHP_OPCACHE_FAST_SHUTDOWN             | Int    | 16              | |
