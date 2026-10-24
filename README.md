# ABSTRACT

Basic demo app in Crystal language,
forked from [sample-bookmark-app](https://github.com/bcardiff/sample-bookmark-app)
and changed to be runnable in 2026.


## Deps in use:

```
$ shards install

Resolving dependencies
Fetching https://github.com/crystal-lang/crystal-sqlite3.git
Fetching https://github.com/kemalcr/kemal.git
Fetching https://github.com/crystal-lang/crystal-db.git
Fetching https://github.com/luislavena/radix.git
Fetching https://github.com/crystal-loot/exception_page.git
Fetching https://github.com/sija/backtracer.cr.git
Installing db (0.15.0)
Installing sqlite3 (0.24.0)
Installing radix (0.4.1)
Installing backtracer (1.2.4)
Installing exception_page (0.5.0)
Installing kemal (1.14.0)
```

## Run:

```
$ ./run-it.sh 

2026-10-24T11:41:37.376281Z   INFO - kemal: [development] Kemal is ready to lead at http://0.0.0.0:3000
2026-10-24T11:41:52.421008Z   INFO - kemal: 200 GET / 186.75µs
2026-10-24T11:41:57.858259Z   INFO - kemal: 302 POST /b 186.22ms
2026-10-24T11:41:57.865445Z   INFO - kemal: 200 GET / 194.43µs
```
