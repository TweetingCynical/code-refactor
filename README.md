# Horiseon

## Code Refactoring

### Deployment / Code Repository

[Live deployment](https://tweetingcynical.github.io/code-refactor/)

[Repository](https://github.com/TweetingCynical/code-refactor)

### Scope and Purpose

Review all HTML and CSS code and refactor to meet accessibility standards. Ensure the site does not change visually.

### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

```
Your website must meet accessibility standards. You can achieve this completing the following:

- Semantic HTML elements can be found throughout the source code
- HTML elements follow a logical structure independent of styling and positioning
- Image and icon elements contain accessible `alt` attributes
- Heading attributes fall in sequential order
- Title elements contain a concise, descriptive title
```

### Overview of Code Changes

index.html

- Add site title
- Change div tags for header and footer
- Add alt labels to the content and benefits images for accessibility
- Replace div tags with nav, section, article and aside tags
- Remove unnecessary img closing tags
- Add comments to help with reading code

style.css

- Match new tags to html references
- Change .header and .footer to match change from class to tags
- Match sequence of code to html
- Use single class rules to combine like styling for content and benefits
- Add comments to help with reading code

## Screenshot

Working version of site should look like this:
![Site Screenshot](./assets/images/screenshot.jpg)

## License

MIT License

Copyright (c) 2023 TweetingCynical

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
