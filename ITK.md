# Giv din stemme

```shell
cp .env-local-task.example .env-local-task
# Edit .env-local-task
task build
task up
```

```shell
task dev:sql:query <<'EOF'
SELECT *
  FROM clips
  JOIN locales ON locale_id = locales.id\G
EOF
```
