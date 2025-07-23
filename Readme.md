# Add new tag to run GHA

```shell
export THE_TAG="prefix-BLAHBLAH"
git tag "${THE_TAG}" && git push origin dev "${THE_TAG}"
```
