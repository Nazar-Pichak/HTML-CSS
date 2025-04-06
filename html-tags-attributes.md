## Base and global tags

| Tag               | Description                                    | Pair Tag (Yes/No) | Common Attributes                        | Block/Inline |
|-------------------|------------------------------------------------|-------------------|------------------------------------------|--------------|
| `<!DOCTYPE>`      | Defines the document type                      | No                | N/A                                      | N/A          |
| `<html>`          | Defines an HTML document                       | Yes               | `lang` (specifies the language of the document) | Block |
| `<head>`          | Contains metadata/information for the document | Yes               | `profile` (defines a metadata profile)   | Block        |
| `<title>`         | Defines a title for the document               | Yes               | N/A                                      | Inline       |
| `<body>`          | Defines the document's body                    | Yes               | `class`, `id`, `style` (global only)     | Block        |
| `<h1>` to `<h6>`  | Defines HTML headings                          | Yes               | `class`, `id`, `style` (global only)     | Block        |
| `<p>`             | Defines a paragraph                            | Yes               | `class`, `id`, `style` (global only)     | Block        |
| `<br>`            | Inserts a single line break                    | No                | N/A                                      | Inline       |
| `<hr>`            | Defines a thematic change in the content       | No                | `class`, `id`, `style`                   | Block        |
| `<!--...-->`      | Defines a comment                              | No                | N/A                                      | N/A          |

## Text formatting, progresses, hidden content
| Tag              | Description                                                           | Pair Tag (Yes/No) | Common Attributes                       | Block/Inline |
|------------------|-----------------------------------------------------------------------|-------------------|-----------------------------------------|--------------|
| `<acronym>`      | Not supported in HTML5. Use `<abbr>` instead. Defines an acronym      | Yes               | N/A                                     | Inline       |
| `<abbr>`         | Defines an abbreviation or an acronym                                 | Yes               | `title` (provides a description for the abbreviation) | Inline       |
| `<address>`      | Defines contact information for the author/owner of a document/article| Yes               | `class`, `id`, `style`                  | Block        |
| `<b>`            | Defines bold text                                                     | Yes               | `class`, `id`, `style`                  | Inline       |
| `<bdi>`          | Isolates a part of text that might be formatted in a different direction | Yes            | `class`, `id`, `style`                  | Inline       |
| `<bdo>`          | Overrides the current text direction                                  | Yes               | `dir` (sets the direction)              | Inline       |
| `<big>`          | Not supported in HTML5. Use CSS instead. Defines big text             | Yes               | `class`, `id`, `style`                  | Inline       |
| `<blockquote>`   | Defines a section that is quoted from another source                  | Yes               | `cite` (specifies the source of the quote) | Block     |
| `<center>`       | Not supported in HTML5. Use CSS instead. Defines centered text        | Yes               | `class`, `id`, `style`                  | Block        |
| `<cite>`         | Defines the title of a work                                           | Yes               | `class`, `id`, `style`                  | Inline       |
| `<code>`         | Defines a piece of computer code                                      | Yes               | `class`, `id`, `style`                  | Inline       |
| `<del>`          | Defines text that has been deleted from a document                    | Yes               | `class`, `id`, `style`                  | Inline       |
| `<dfn>`          | Specifies a term that is going to be defined within the content       | Yes               | `class`, `id`, `style`                  | Inline       |
| `<em>`           | Defines emphasized text                                               | Yes               | `class`, `id`, `style`                  | Inline       |
| `<font>`         | Not supported in HTML5. Use CSS instead. Defines font, color, and size for text | Yes     | `color`, `size`, `face` (deprecated)    | Inline       |
| `<i>`            | Defines a part of text in an alternate voice or mood                  | Yes               | `class`, `id`, `style`                  | Inline       |
| `<ins>`          | Defines a text that has been inserted into a document                 | Yes               | `class`, `id`, `style`                  | Inline       |
| `<kbd>`          | Defines keyboard input                                                | Yes               | `class`, `id`, `style`                  | Inline       |
| `<mark>`         | Defines marked/highlighted text                                       | Yes               | `class`, `id`, `style`                  | Inline       |
| `<meter>`        | Defines a scalar measurement within a known range (a gauge)           | Yes               | `min`, `max`, `value`, `low`, `high`    | Inline       |
| `<pre>`          | Defines preformatted text                                             | Yes               | `class`, `id`, `style`                  | Block        |
| `<progress>`     | Represents the progress of a task                                     | Yes               | `value`, `max`                          | Inline       |
| `<q>`            | Defines a short quotation                                             | Yes               | `cite` (specifies the source of the quote) | Inline    |
| `<rp>`           | Defines what to show in browsers that do not support ruby annotations | Yes               | N/A                                     | Inline       |
| `<rt>`           | Defines an explanation/pronunciation of characters (for East Asian typography) | Yes      | N/A                                     | Inline       |
| `<ruby>`         | Defines a ruby annotation (for East Asian typography)                 | Yes               | N/A                                     | Inline       |
| `<s>`            | Defines text that is no longer correct                                | Yes               | `class`, `id`, `style`                  | Inline       |
| `<samp>`         | Defines sample output from a computer program                         | Yes               | `class`, `id`, `style`                  | Inline       |
| `<small>`        | Defines smaller text                                                  | Yes               | `class`, `id`, `style`                  | Inline       |
| `<strike>`       | Not supported in HTML5. Use `<del>` or `<s>` instead. Defines strikethrough text | Yes    | `class`, `id`, `style`                  | Inline       |
| `<strong>`       | Defines important text                                                | Yes               | `class`, `id`, `style`                  | Inline       |
| `<sub>`          | Defines subscripted text                                              | Yes               | `class`, `id`, `style`                  | Inline       |
| `<sup>`          | Defines superscripted text                                            | Yes               | `class`, `id`, `style`                  | Inline       |
| `<template>`     | Defines a container for content that should be hidden when the page loads | Yes           | N/A                                     | Block        |
| `<time>`         | Defines a specific time (or datetime)                                 | Yes               | `datetime` (specifies the time)         | Inline       |
| `<tt>`           | Not supported in HTML5. Use CSS instead. Defines teletype text        | Yes               | `class`, `id`, `style`                  | Inline       |
| `<u>`            | Defines some text that is unarticulated and styled differently from normal text | Yes     | `class`, `id`, `style`                  | Inline       |
| `<var>`          | Defines a variable                                                    | Yes               | `class`, `id`, `style`                  | Inline       |
| `<wbr>`          | Defines a possible line-break                                         | No                | N/A                                     | Inline       |

## Forms and inputs
| Tag              | Description                                                 | Pair Tag (Yes/No) | Common Attributes                        | Block/Inline |
|------------------|-------------------------------------------------------------|-------------------|------------------------------------------|--------------|
| `<form>`         | Defines an HTML form for user input                         | Yes               | `action`, `method`, `enctype`, `target`  | Block        |
| `<input>`        | Defines an input control                                    | No                | `type`, `value`, `name`, `placeholder`, `required` | Inline |
| `<textarea>`     | Defines a multiline input control (text area)               | Yes               | `rows`, `cols`, `name`, `placeholder`, `required` | Block   |
| `<button>`       | Defines a clickable button                                  | Yes               | `type`, `name`, `value`, `disabled`      | Inline       |
| `<select>`       | Defines a drop-down list                                    | Yes               | `name`, `multiple`, `size`, `required`   | Block        |
| `<optgroup>`     | Defines a group of related options in a drop-down list      | Yes               | `label`                                  | Block        |
| `<option>`       | Defines an option in a drop-down list                       | Yes               | `value`, `disabled`, `selected`          | Inline       |
| `<label>`        | Defines a label for an `<input>` element                    | Yes               | `for` (associates the label with an input) | Inline     |
| `<fieldset>`     | Groups related elements in a form                           | Yes               | `disabled`, `form`, `name`               | Block        |
| `<legend>`       | Defines a caption for a `<fieldset>` element                | Yes               | N/A                                      | Inline       |
| `<datalist>`     | Specifies a list of pre-defined options for input controls  | Yes               | `id`                                     | Block        |
| `<output>`       | Defines the result of a calculation                         | Yes               | `for`, `name`                            | Inline       |

## Frames (embed another document within the current HTML document)
| Tag              | Description                                                       | Pair Tag (Yes/No) | Common Attributes                        | Block/Inline |
|------------------|-------------------------------------------------------------------|-------------------|------------------------------------------|--------------|
| `<frame>`        | Not supported in HTML5. Defines a window (a frame) in a frameset  | No                | `src`, `name`, `scrolling`, `border`, `frameborder` | Inline       |
| `<frameset>`     | Not supported in HTML5. Defines a set of frames                   | Yes               | `cols`, `rows`, `frameborder`, `border`  | Block        |
| `<noframes>`     | Not supported in HTML5. Defines an alternate content for users that do not support frames | Yes | N/A                            | Block        |
| `<iframe>`       | Defines an inline frame                                           | Yes               | `src`, `width`, `height`, `name`, `sandbox`, `frameborder`, `longdesc`, `loading`, `allowfullscreen` `referrerpolicy`, `srcdoc`, `allow`, `title` | Inline       | 

## Images
| Tag              | Description                                                       | Pair Tag (Yes/No) | Common Attributes                        | Block/Inline |
|------------------|-------------------------------------------------------------------|-------------------|------------------------------------------|--------------|
| `<img>`          | Defines an image                                                  | No                | `src`, `alt`, `width`, `height`, `title`, `loading`, `srcset`, `sizes`, `usemap`, `crossorigin`, `longdesc`, `decoding`, `referrerpolicy`, `ismap` | Inline       |
| `<map>`          | Defines a client-side image map                                   | Yes               | `name`                                   | Block        |
| `<area>`         | Defines an area inside an image map                               | Yes               | `shape`, `coords`, `alt`, `href`, `target`, `rel`, `download`, `type` | Inline       |
| `<canvas>`       | Used to draw graphics, on the fly, via scripting (usually JavaScript) | Yes           | `width`, `height`, `id`, `class`, `style`| Block        |
| `<figcaption>`   | Defines a caption for a `<figure>` element                        | Yes               | N/A                                      | Inline       |
| `<figure>`       | Specifies self-contained content                                  | Yes               | `class`, `id`, `style`                   | Block        |
| `<picture>`      | Defines a container for multiple image resources                  | Yes               | `srcset`, `sizes`, `type`, `media`, `width`, `height`   | Block        |
| `<svg>`          | Defines a container for SVG graphics                              | Yes               | `width`, `height`, `viewBox`, `fill`, `xmlns`, `preserveAspectRatio`, `x`, `y`, `version`, `viewBox` | Block        |
