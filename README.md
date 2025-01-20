# davidkhala/build-push-action

Use
```

    - uses: davidkhala/build-push-action@main
      with:
        working-directory: .
        password: ${{secrets.GITHUB_TOKEN}}
        image: ubuntu # The basename of image

```
