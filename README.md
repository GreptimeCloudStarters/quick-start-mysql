# Introduction

This quick start script collects system metrics, such as CPU and memory usage, and sends them to GreptimeCloud using the MySQL protocol.

Use the following command to start it:

```shell
chmod +x quick-start.sh && ./quick-start.sh -h <host> -d <dbname> -u <username> -p <password>
```

## Release

1. Update the version in `quick-start.sh`.
2. Commit and push code
3. Create a tag with the version and push it

```shell
git tag v<major>.<minor>.<patch>
git push origin v<major>.<minor>.<patch>
```
5. Add release and upload the `quick-start.sh` file in the release page
6. Update the download link of `quick-start.sh` in the [quick start docs](https://github.com/GreptimeTeam/docs/tree/main/docs/greptimecloud) of GreptimeCloud.
