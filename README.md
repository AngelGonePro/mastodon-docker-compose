```
curl -fsSL -o /tmp/mastodon.zip https://github.com/AngelGonePro/mastodon-docker-compose/raw/refs/heads/main/mastodon.zip && python3 -c "import zipfile;open('/tmp/mastodon-deploy.sh','wb').write(zipfile.ZipFile('/tmp/mastodon.zip').read('mastodon/deploy-update.sh'))" && bash /tmp/mastodon-deploy.sh /tmp/mastodon.zip ~/mastodon
```
