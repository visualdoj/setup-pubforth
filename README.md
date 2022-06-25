# Setup PubForth

GitHub action for installing latest released [PubForth](https://github.com/visualdoj/pubforth). Works on Linux, Windows and macOS runners.

# Inputs

* `repo-token`: GitHub token. Defaults to `github.token`

# Example

```yaml
      - name: Setup PubForth
        uses: visualdoj/setup-pubforth@main

      - name: Run PubForth
        run:  pubforth --experimental -e "1 2 3 . . ."
```

See [example-for-setup-pubforth](https://github.com/visualdoj/example-for-setup-pubforth) for full example.
