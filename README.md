# Dom-Explorer

Dom-Explorer is a web-based tool designed for testing various HTML parsers and sanitizers. It displays the results of each parser as a tree and allows users to create pipelines that chain multiple parsers to visualize the transformation of HTML at each step. 

This repository contains the source code for the website published at: [Dom-Explorer Website](https://yeswehack.github.io/Dom-Explorer/).

## Features

- **Parser/Sanitizer Support:**
  - [Ammonia](https://github.com/rust-ammonia/ammonia)
  - [Angular](https://angular.dev/)
  - [Custom](https://developer.mozilla.org/en-US/docs/Web/JavaScript) (user-defined JavaScript)
  - [DomParser](https://developer.mozilla.org/en-US/docs/Web/API/DOMParser)
  - [DomPurify](https://github.com/cure53/DOMPurify)
  - [HighlightJs](https://highlightjs.org/)
  - [IframeView](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe) (render HTML in a sandboxed iframe)
  - [JsXss](https://jsxss.com/en/index.html)
  - [Parse5](https://github.com/inikulin/parse5)
  - [SafeValues](https://github.com/google/safevalues)
  - [SrcdocParser](https://developer.mozilla.org/en-US/docs/Web/API/HTMLIFrameElement/srcdoc)
  - [TemplateParser](https://developer.mozilla.org/en-US/docs/Web/API/HTMLTemplateElement)

- **Tab Sync:**  
  Synchronizes pipelines and HTML parsing across multiple browser tabs in real-time.

- **Embeddable Pipelines:**  
  Users can embed pipelines into their websites as an iframe for others to interact with.

- **Presets:**  
  Save commonly used pipelines for easy reuse.

- **Shareable URL:**  
  Share pipelines by simply copying and pasting the URL. The state of the pipeline is embedded in the URL, making it easy to share with others.

## Prerequisites

- [Bun](https://bun.sh/) (v1.1.29 or later)
- [Rust](https://rustup.rs/)

## Getting Started

To get started with Dom-Explorer:

1. Install [Bun](https://bun.sh/):
   ```bash
   curl -fsSL https://bun.sh/install | bash
   ```

2. Install [Rust](https://rustup.rs/):
   ```bash
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
   ```

3. Clone the project and install dependencies:
   ```bash
   git clone https://github.com/yeswehack/Dom-Explorer
   cd Dom-Explorer
   bun install
   ```

4. Run the development server:
   ```bash
   bun run dev
   ```

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve this tool.
