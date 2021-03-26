# How to format text

This page summarizes the text-formatting conventions you should follow.

## Bold

Use **bold** formatting when referring to UI elements.

## Italics

Use *italics* for:

- Parameter names
- Mathematical and version variables

## Code font

Use *code font* for:

- User text input
- Command-line utility names
- DNS record types
- Environment variable names (e.g., `PATH`)
- Filenames, filename extensions, and paths
- Folders and directories
- HTTP verbs, status codes, and content-type values
- Placeholder variables

Use *code blocks* for code samples and other blocks of code. Be sure to indicate
the language your using to apply the proper syntax highlighting.

```text
This is a codeblock.
```

For code that you want users to enter via a command-line interface, use
`console`, not `bash`.

## Punctuation

Do not use the ampersand (&) as a shorthand for *and* unless you're referring to a
UI element or the name of something that uses *&*.

You can use the symbol `~` in place of the word *approximately*.

## UI elements

When referring to UI elements, including the names for buttons, menus, dialogs,
and anything that has a name visible to the user, use bold font.

**Example:** On the **Environment Overview** page, click **Configure SSH**.

Don't use code font for UI elements unless it is rendered based on previously entered
text. For example, if you tell the user to provide the environment name as
`myEnvironment`, then use both bold and cold font when referring to the name.

**Example**: Click **`myEnvironment`**.

When writing out instructions that involve UI elements, both of the following options are acceptable:

- Go to **Manage** > **Users**.
- In the **Manage** menu, click **Users**.
