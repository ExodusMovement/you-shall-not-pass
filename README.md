# you-shall-not-pass

Dummy dependency to block some packages from being pulled through Yarn resolutions.

# How to use

in your `package.json`:

```json
"resolutions": {
  "download-file-sync": "@exodus/you-shall-not-pass",
}
```
