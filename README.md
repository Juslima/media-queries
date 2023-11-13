# media-queries


# HTML File Explanation and CSS Files README

In this assignment, I will be creating an HTML5 web page and implementing three essential media queries. Media queries are a crucial component of modern web design, allowing web developers to make their websites responsive and adaptable to different screen sizes and printing requirements. 

## `index.html`

### `<!DOCTYPE html>`

- **Purpose:** This declaration specifies the document type and version of HTML being used (HTML5).

### `<html lang="en">`

- **Purpose:** This opening tag signifies the beginning of the HTML document and sets the document's language to English.

### `<head>`

- **Purpose:** This section contains meta-information about the web page and links to external resources, such as CSS stylesheets.

### `<meta charset="UTF-8">`

- **Purpose:** This meta tag specifies the character encoding of the document as UTF-8, ensuring proper rendering of special characters.

### `<meta name="viewport" content="width=device-width, initial-scale=1.0">`

- **Purpose:** This meta tag configures the viewport settings for responsive design, adapting the content to the device's width and initial scale.

### `<title>Media Query</title>`

- **Purpose:** This is the title of the web page that appears in the browser's title bar or tab.

### Stylesheet Links

- **Purpose:** These `<link>` elements connect the HTML document to external CSS stylesheets. Each stylesheet is applied under specific conditions based on media queries.

  - `<link rel="stylesheet" href="style.css">`: The default stylesheet that applies to all screen sizes.

  - `<link rel="stylesheet" media="screen and (min-width: 940px)" href="large-screen.css">`: Styles for screens with a width of 940px or more.

  - `<link rel="stylesheet" media="screen and (min-width: 400px) and (max-width: 600px)" href="medium-screen.css">`: Styles for screens between 400px and 600px in width.

  - `<link rel="stylesheet" media="print" href="print.css">`: Styles for printing the web page.

### `<body>`

- **Purpose:** This is the main content area of the web page, containing the visible content.

### `<header>`

- **Purpose:** This is the header section of the web page. It typically includes elements like the page title or logo.

### `<h1>Media Query</h1>`

- **Purpose:** This is the main title or heading of the web page.

### `<nav>`

- **Purpose:** This is the navigation menu section, usually containing links to different parts of the website.

### `<ul>`

- **Purpose:** This is an unordered list that holds the navigation menu items.

### `<li><a href="#">Home</a></li>`

- **Purpose:** These list items are links to different sections of the website. The `href` attribute specifies the destination of each link. In this example, they are placeholders (indicated by `#`) and should be replaced with actual URLs.

### `<main>`

- **Purpose:** This is the main content section of the web page.

### `<section>`

- **Purpose:** This is a subsection within the main content area, often used to organize and structure content.

### `<h2>Why Are Media Queries Important?</h2>`

- **Purpose:** This is a subheading within the section.

### `<p>The use of media queries...</p>`

- **Purpose:** This is a paragraph of text content within the section. It explains the importance of media queries.

### `<footer>`

- **Purpose:** This is the footer section of the web page, typically containing copyright information and contact details.

### `<p>&copy; 2023 Juliana Lima</p>`

- **Purpose:** This is a paragraph displaying copyright information. The `&copy;` HTML entity represents the copyright symbol.

## CSS Files Explanation (README)

### 1. `styles.css`

- **Purpose:** This is the default stylesheet that applies to all screen sizes and serves as the foundation for the web page's styling.

- **Details:**
  - Sets the base font family to Arial and defines a light gray background color.
  - Styles the header with a dark gray background and white text.
  - Defines a centered navigation menu with list items displayed inline.
  - Styles the main content area with a maximum width, centered alignment, and white background.
  - Sets the footer text alignment and provides padding.

### 2. `large-screen.css`

- **Purpose:** This stylesheet is designed for screens with a width of 940px or more and includes styles that enhance the layout for larger screens.

- **Details:**
  - Increases the padding of the main content area for improved spacing on larger screens.
  - Enlarges the font size of the navigation menu.

### 3. `medium-screen.css`

- **Purpose:** This stylesheet targets screens between 400px and 600px, optimizing the design for medium-sized screens.

- **Details:**
  - Reduces the base font size to 14px for better readability on medium-sized screens.
  - Adjusts the font size of the navigation menu.

### 4. `print.css`

- **Purpose:** This stylesheet is specifically designed for printing the web page, ensuring a more printer-friendly layout.

- **Details:**
  - Resets the background and adjusts content for printing.
  - Hides the header and navigation menu to declutter the printed output.
  - Adjusts the padding and background of the main content area.
  - Centers the text in the footer for better printing.
