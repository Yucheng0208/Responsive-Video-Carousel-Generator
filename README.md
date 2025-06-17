# YouTube Sliding Carousel Generator

A self-contained HTML tool for creating a responsive, infinite-looping "sliding window" YouTube video carousel. It features a live preview, multi-language UI, and produces clean, dependency-free code.

![Demo GIF of the Generator in Action](https://user-images.githubusercontent.com/1010733/102642502-8d2a7180-412c-11eb-9824-2c0617a26f3c.gif)
*(Recommendation: Replace the image URL above with a GIF or screenshot of your actual tool.)*

## About The Project

This project was born from the need for a highly specific and visually engaging video display. Traditional carousels move items, but this generator creates a unique "sliding window" effect where the *content* updates (e.g., items `1,2,3` become `2,3,4`), providing a seamless, infinite loop.

It's designed to be incredibly easy to use: just paste your YouTube links, and the tool generates a complete, self-contained block of HTML, CSS, and JavaScript that you can copy and paste directly into any website.

## Key Features

*   ✨ **Unique Sliding Window Effect**: Instead of a traditional carousel, the content slides infinitely, creating a `1,2,3` -> `2,3,4` -> `3,4,1` progression.
*   📱 **Fully Responsive**: The layout elegantly adapts from a three-video desktop view to a single-video mobile view, maintaining the core sliding logic.
*   🌐 **Multi-language Interface**: The generator UI supports Traditional Chinese, English, German, Japanese, and Korean, with auto-detection for the user's browser language.
*   🚀 **Live Preview**: See exactly how your video carousel will look and behave before you even copy the code.
*   📋 **Dependency-Free Output**: The generated code is written in pure, vanilla JavaScript and CSS. It requires **no external libraries** like jQuery or Owl Carousel to run on your website.

## How to Use

1.  **Open the Generator**: Download the `youtube-sliding-carousel-generator.html` file and open it in your web browser.
2.  **Input Your Videos**: Paste your list of YouTube video links (one per line) into the text area.
3.  **Generate**: Click the "Generate Code & Preview" button.
4.  **Copy & Paste**: Copy the complete code block from the output section and paste it into your website's HTML. That's it!

## License

Distributed under the MIT License. See `LICENSE.md` for more information.
