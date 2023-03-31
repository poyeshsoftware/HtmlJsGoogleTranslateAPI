# Word Translation Tool

A simple web-based tool for translating selected text using the Google Translate API. Users can input text, select a portion of it, and view the translated text in a popover. This project utilizes HTML, CSS, JavaScript, jQuery, and Bootstrap.

## Features

- Text selection and highlighting
- Translation using the Google Translate API
- Popover to display the translated text
- Reset and insert buttons to clear and insert new text
- Hide popover when clicking outside or resetting

## Libraries and APIs Used

- [Bootstrap](https://getbootstrap.com/)
- [jQuery](https://jquery.com/)
- [Popper.js](https://popper.js.org/)
- [Google Translate API](https://cloud.google.com/translate/docs)

## Getting Started

1. Clone this repository or download the source code.
2. Obtain a Google Translate API key by following the instructions in the [Google Translate API documentation](https://cloud.google.com/translate/docs/basic/setup-basic).
3. Replace the `API_KEY` placeholder in the `translateText` function with your actual API key.
4. Open `index.html` in your favorite web browser.

## Usage

1. Insert your text in the textarea and click the "Insert" button.
2. Select a word or a sentence in the displayed text.
3. A popover with the translation will appear above the selected text.
4. To hide the popover, click outside the text or the popover, or click the "Reset" button.

## License

This project is open source and available under the [MIT License](LICENSE).