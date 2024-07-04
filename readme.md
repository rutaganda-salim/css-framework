**Salixcss Utility Classes Documentation**
=====================================

Welcome to the documentation for our SCSS utility classes package. This package provides a comprehensive set of utility classes to enhance front-end development.

**Table of Contents**
-------------------

* [Typography](#typography)
* [Colors](#colors)
* [Borders](#borders)
* [Flexbox](#flexbox)
* [Spacing](#spacing)
* [Sizing](#sizing)
* [Typography](#typography)
* [Backgrounds](#backgrounds)
* [Effects](#effects)
* [Flexbox & Grid](#flexbox--grid)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributions)
* [License](#license)

**Typography**
-------------

### Text Alignment

* `.text-left`: Aligns text to the left.
* `.text-center`: Centers text.
* `.text-right`: Aligns text to the right.
* `.text-justify`: Justifies text.

### Text Styling

* `.text-bold`: Makes text bold.
* `.text-italic`: Applies italic style to text.
* `.text-underline`: Underlines text.
* `.text-line-through`: Adds a line through text.
* `.text-uppercase`: Converts text to uppercase.
* `.text-lowercase`: Converts text to lowercase.
* `.text-capitalize`: Capitalizes the first letter of each word.

### Text Size

* `.text-xs`: Extra small text size.
* `.text-sm`: Small text size.
* `.text-base`: Base text size.
* `.text-lg`: Large text size.
* `.text-xl`: Extra large text size.
* `.text-2xl`: 2 times extra large text size.
* `.text-3xl`: 3 times extra large text size.
* `.text-4xl`: 4 times extra large text size.

### Text Color

* `.text-{color}`: Applies text color where `{color}` corresponds to predefined color classes.

### Line Height

* `.leading-{size}`: Sets the line height where `{size}` is a numeric value.

**Colors**
---------

### Background Color

* `.bg-{color}`: Applies background color where `{color}` corresponds to predefined color classes.
* `.bg-gradient-to-{direction}-{color1}-{color2}`: Applies a gradient background where `{direction}` is the gradient direction (t for top, r for right, b for bottom, l for left) and `{color1}`, `{color2}` are colors.

### Border Color

* `.border-{color}`: Sets border color where `{color}` corresponds to predefined color classes.
* `.border-{side}-0`: Removes border on `{side}` (e.g., top, right, bottom, left).
* `.border-{side}-solid`: Applies solid border on `{side}`.

**Borders**
----------

### Border Radius

* `.rounded-{size}`: Applies border radius where `{size}` is small, medium, large, full.

### Border Width

* `.border-{width}`: Sets border width where `{width}` is thin, thick.

### Border Style

* `.border-{style}`: Sets border style where `{style}` is dashed, solid, double.

**Flexbox**
---------

### Flex Container

* `.flex`: Enables flex container.
* `.flex-{direction}`: Sets flex direction (row, row-reverse, col, col-reverse).
* `.flex-wrap`: Allows flex items to wrap.
* `.justify-{content}`: Aligns flex items along the main axis (start, end, center, between, around, evenly).
* `.items-{align}`: Aligns flex items along the cross axis (start, end, center, baseline, stretch).

### Flex Item

* `.flex-{grow}`: Sets flex grow factor.
* `.flex-{shrink}`: Sets flex shrink factor.
* `.order-{n}`: Sets order of flex item.

**Spacing**
---------

### Padding

* `.p-{size}`: Applies padding where `{size}` is small, medium, large.

### Margin

* `.m-{size}`: Applies margin where `{size}` is small, medium, large.

**Sizing**
---------

### Width

* `.w-{size}`: Sets width where `{size}` is small, medium, large.

### Height

* `.h-{size}`: Sets height where `{size}` is small, medium, large.

### Min/Max Width/Height

* `.min-w-{size}`: Sets minimum width.
* `.max-w-{size}`: Sets maximum width.
* `.min-h-{size}`: Sets minimum height.
* `.max-h-{size}`: Sets maximum height.

**Typography**
-------------

### Font Size

* `.text-{size}`: Sets font size where `{size}` is small, medium, large.

### Font Family

* `.font-{family}`: Applies font family where `{family}` is serif, sans-serif, monospace.

**Backgrounds**
------------

### Background Color

* `.bg-{color}`: Applies background color where `{color}` corresponds to predefined color classes.

### Background Image

* `.bg-{image}`: Applies background image where `{image}` is url.

**Effects**
---------

### Box Shadow

* `.shadow-{type}`: Applies box shadow where `{type}` is small, medium, large.

**Flexbox & Grid**
------------

### Flex

* `.flex`: Enables flex container.
* `.flex-{direction}`: Sets flex direction (row, row-reverse, col, col-reverse).
* `.flex-wrap`: Allows flex items to wrap.
* `.justify-{content}`: Aligns flex items along the main axis (start, end, center, between, around, evenly).
* `.items-{align}`: Aligns flex items along the cross axis (start, end, center, baseline, stretch).

### Grid

* `.grid`: Enables grid container.
* `.grid-cols-{num}`: Sets number of columns.
* `.grid-rows-{num}`: Sets number of rows.
* `.col-span-{num}`: Spans columns.
* `.row-span-{num}`: Spans rows.

**Installation**
-------------

### Install

```bash
npm i salixcss
```

**Usage**
--------

To use these utility classes in your project, include the compiled SCSS file into your project's stylesheet:

```html
<link rel="stylesheet" href="node_modules/salixcss/dist/main.css">


Apply directly to your html

<div class="text-center text-xl bg-blue-500">
  This text is centered, extra large, and has a blue background.
</div>

```

Run the following command:

### contributions
-------------
Contributions are welcome! Please fork the repository and create a pull request with your changes.

**https://github.com/rutaganda-salim/salixcss**

Please let's make this a huge and big a css framework for every developer and I believe we can make it!!


