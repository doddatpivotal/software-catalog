# Exemplar Application Portfolio

This repo serves as an exemplar system catalog for the Acme Company.

## Preview Tech Docs

```bash
npx @techdocs/cli serve
```


## Publish Tech Docs

```bash
techdocs-cli generate --no-docker
techdocs-cli publish --publisher-type awsS3 --storage-name npc-tiger-backstage --entity default/Location/tap-gui-catalog-info
```

