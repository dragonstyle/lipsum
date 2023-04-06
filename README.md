# Lipsum Extension For Quarto

The Lipsum extension is useful for generating placeholder text.

## Installing

```bash
quarto add dragonstyle/lipsum
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

Simply place the shortcode where you'd like placeholder content to be generated. Be default, the lipsum shortcode will emit 5 paragraphs of lipsum. For example:

```
{{< lipsum >}}
```

### Number of Paragraphs

You can specify how many paragraphs of Lipsum you'd like included. For example, to include 7 paragraphs of lipsum, you would write:

```
{{< lipsum 7>}}
```

### Ranges
 
Lipsum use a dictionary of lipsum paragraphs. You can use particular paragraphs if you'd like, by providing a range. For example, to emit paragraphs 2, 3, and 4 you would write:

```
{{< lipsum 2-4 >}}
```

You can also specify decreasing ranges, such as:

```
{{<lipsum 4-2 >}}
```

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).

