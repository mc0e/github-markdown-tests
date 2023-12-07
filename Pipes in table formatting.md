# Pipes in table formatting

There are conflicting statements in docs.github.com pages about whether pipe characters are required at the ends of lines.

Issue submitted at https://github.com/github/docs/issues/30411

## Code

```markdown
|link | statement |
|-|-|
[organizing-information-with-tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables) | "The pipes on either end of the table are optional." |
[using-markdown-and-liquid-in-github-docs](https://docs.github.com/en/contributing/writing-for-github-docs/using-markdown-and-liquid-in-github-docs) | "Every row of a table in the GitHub Docs must start and end with a pipe, `\|`." |
```

## Display

|link | statements |
|-|-|
[organizing-information-with-tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables) | "The pipes on either end of the table are optional."<br> "There must be at least three hyphens in each column of the header row." |
[using-markdown-and-liquid-in-github-docs](https://docs.github.com/en/contributing/writing-for-github-docs/using-markdown-and-liquid-in-github-docs) | "Every row of a table in the GitHub Docs must start and end with a pipe, `\|`." |


## Conclusion

[organizing-information-with-tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables) is correct about the pipe characters, and it's even OK to mix and match formatting approaches within a table.

However, [organizing-information-with-tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables) also says  "There must be at least three hyphens in each column of the header row.", and this does not appear to be true.

