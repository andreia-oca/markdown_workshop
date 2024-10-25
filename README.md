# Markdown Workshop

A repository containing material to explain the Markdown format

> [!TIP]
> (GitHub) Markdown is used for writing and rendering documentation on Github, as well as write comments, issues, and pull requests.

> [!NOTE]
> You can recognize Markdown files by their `.md` file extension.

Full documentation and examples for the following concepts can be found in the [GitHub Markdown Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

Showcase the following Markdown concepts:
- Headers
- Styling text - bold, italics, strikethrough
- Lists - ordered, unordered
- Todo Lists
- Links
- Quotes - quoting text, code blocks, syntax highlighting
- Tables
- Images
- Alerts

Other fun stuff:
- Emojis
- Collapsible sections
- Create diagrams
- Tables of contents


**Bold**
*Italics*
~~Strikethrought~~

- Item 1
- Item 2

* Item 3
* Item 4

1. Item 1
2. Item 2

- [x] Task 1
- [ ] Task 2

This is a [hyperlink](https://github.com/rosedu/workshop-markdown/tree/main).

## Example for quotes

> This is a quote

Typewriter font: `This is a quote`, `filename.txt`, `command`, `echo "Hello, World!"`, `cat file.txt`.

```python
print("Hello)
```

```python
def hello_world():
    print("Hello, World!")
```

```bash
echo "Hello, World!"
```

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

## Example for tables

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Row 1    | Row 1    |
| Row 2    | Row 2    | Row 2    |
| Row 3    | Row 3    | Row 3    |

## Example for alerts

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Hsmdkasdy.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Example for emojis

:smile: :+1: :sparkles: :tada: :rocket: :metal: :octocat:

## Example for collapsible sections

<details>
<summary>Click to expand!</summary>
This is hidden content that can be shown when the user clicks on the title.
</details>

## Example for images

![Github Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
![Octocat](./images/github-octocat.png)

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)


## Example for diagrams

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    Note right of John: Rational thoughts <br/>prevail...
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

## Example for tables of contents

1. [Example for quotes](#example-for-quotes)
2. [Example for tables](#example-for-tables)
3. [Example for images](#example-for-images)
4. [Example for alerts](#example-for-alerts)
5. [Example for emojis](#example-for-emojis)
6. [Example for collapsible sections](#example-for-collapsible-sections)
7. [Example for diagrams](#examplefordiagrams)
