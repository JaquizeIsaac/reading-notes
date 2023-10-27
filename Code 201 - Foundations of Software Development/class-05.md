# HTML Media

> What is a real world use case for the alt attribute being used in a website?

* The "alt" attribute in a website's code is like a description for images. It helps in several real-world situations:

* Accessibility: It's essential for people with disabilities. When they use screen readers, the "alt" text describes what the image is about.

* SEO: Search engines use this text to understand and rank your website better, making it more likely to show up in search results.

* When Images Don't Load: If an image can't load, the "alt" text shows up, so users still know what the image was supposed to be.

* Text-Only Browsers: Some people use text-only browsers that can't show images. "Alt" text helps them understand what's missing.

* Enhancing User Experience: Even if images are visible, "alt" text can provide extra information or clarity, especially for charts and complex visuals.

* Legal Compliance: In some places, websites must follow rules for accessibility. Using "alt" text is often required by law.

> How can you improve accessibility of images in an HTML document?

* Add "alt" Text: Use the "alt" attribute to describe what the image shows. Be clear and concise.

* Describe Complex Images: For complicated pictures, give a detailed description in the "alt" text.

* Use Captions: Add captions or labels near images for extra details.

* Make Interactive Images Accessible: If an image is a button or link, use special code to explain its purpose to screen readers.

* Include Text Content: If an image has important text, ensure the text is also in the webpage, not just in the image.

* Use Proper HTML: Use the right HTML elements like < figure > and < figcaption for images and their descriptions.

* Check Accessibility: Use tools to test your website's accessibility to ensure images are described well and usable for everyone.

* Use online tools like WAVE or browser extensions like axe DevTools to check for issues.

* Test your site with screen readers to understand how users with disabilities experience it.

* Also, review your site manually to make sure image descriptions are clear and relevant.

> Provide an example of when the figure element would be useful in an HTML document.

< figure >
  < img src="diagram.png" alt="Water cycle diagram" >
  < figcaption >This is a diagram of the water cycle.< /figcaption >
< /figure >

> Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.
What image type would you use to display a screenshot on your website and why?

GIF Image:

It's like a moving picture, good for simple animations.
SVG Image:

It's like a flexible drawing that stays clear when big or small.
For showing a screenshot on your website, use a PNG image because it's great for keeping text and details sharp, just like taking a photo of your screen.

source: Using Images In HTML/ Common Image Types and Choosing Image Formats/ ChatGpt

## Learn CSS

> Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

* Foreground Color: This is like the color of the paint you use for drawing the main things, like a red apple or a blue car. It's the color of the stuff you want to stand out.

* Background Color: Now, think of the background color as the color of the paper or canvas you're painting on. It's like the backdrop behind the main things you're drawing. It's not the focus; it's what's behind everything else, like the blue sky behind the tree.

> Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

* Pick a Color Theme: Choose a set of colors that match the blog's style. Think about what colors represent the blog's topic or vibe.

* Header and Logo: Use one color for the header and logo to make them unique and memorable.

* Background: Make the background light, like white or light gray, so the text is easy to read.

* Text Color: Use dark text on the light background for readability.

* Highlight: Add one or two colors to make important things stand out, like buttons or links.

* Category Colors: Assign different colors to blog categories for clarity.

* Images: Use colorful images that fit the content.

* Stay Consistent: Keep using the same colors throughout the blog.

* Space Things Out: Make sure there's enough space between elements.

* Think About Readers: Check that the colors are easy on the eyes and don't make reading difficult.

> What should you consider when choosing fonts for an HTML document?

* Easy to Read: Pick fonts that are easy to read, especially for regular text.

* Know Your Audience: Think about who will visit your site. Different fonts suit different people and types of websites.

* Content Matters: The type of content on your site influences font choice. Formal sites need traditional fonts, while creative sites can use more unique ones.

* Keep It Consistent: Use just a few fonts across your site, and be sure to choose fonts that go well together.

* Web-Safe Fonts: Stick to fonts that work on most devices and browsers to avoid display issues.

* Fallback Fonts: Plan for backup fonts in case a visitor's device doesn't support your first choice.

* Font Size and Line Spacing: Make sure text is big enough to read comfortably, and space lines apart for clarity.

* Good Contrast: Use colors that make text stand out from the background.

* Spacing and Kerning: Adjust letter and word spacing if needed.

* Test on Different Devices: Make sure your chosen fonts look good on various devices and screens.

* Check Licensing: If you use custom fonts, make sure you have the right to use them online.

* Web Fonts: Consider using web font services like Google Fonts that offer a variety of fonts designed for websites.

> What do font-size, font-weight, and font-style do to HTML text elements?

* Font-Size: This property controls the size of the text. You can make text appear larger or smaller. For example, setting "font-size: 18px;" will make the text larger, while "font-size: 12px;" will make it smaller. You can use different units like pixels (px), percentages (%), or ems (em) to define the size.

* Font-Weight: This property manages how thick or bold the text appears. It can range from "normal" (regular text) to "bold" (heavier, thicker text). You can also use numeric values like "400" for normal and "700" for bold. It affects the visual weight of the text characters.

* Font-Style: This property changes the style of the text, making it appear italic or normal. You can set it to "italic" to slant the text, or "normal" to keep it upright. It's used to add emphasis or differentiate text.

> Describe two ways you could add spacing around the characters displayed in an h1 element.

* Letter Spacing: You can increase or decrease the space between individual letters within the text.

* Word Spacing: You can adjust the space between words in the text, making them closer together or farther apart.

source: Using Color in CSS/ChatGpt

## Things I want to know more about

I want to see what the foreground and background look when you code it into CSS. I was kind of confused on how foreground color changes. I tried to find information on it and it just confusd me more. I hope to see in class the difference in make in your code.