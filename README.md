# Star Tribune Locator

Star Tribune [Locator instance](https://github.com/datanews/locator).

## Tiles

Tiles setup with Mapbox and Bing account.

## Deploy

Deploy to S3 with:

```
aws s3 sync ./ s3://static.startribune.com/news/tools/locator --exclude=node_modules/*
```
