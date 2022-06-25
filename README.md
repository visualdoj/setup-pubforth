# Setup PubForth

GitHub action for installing latest released [PubForth](https://github.com/visualdoj/pubforth).

# Inputs

* `repo-token`: GitHub token. Defaults to `github.token`

# Example

```yaml
      - name: Setup PubForth
        uses: visualdoj/setup-pubforth@main

      - name: Run program
        run:  pubforth --experimental -e "1 2 3 . . ."
```

See [example-for-setup-pubforth](https://github.com/visualdoj/example-for-setup-pubforth) for full example.
