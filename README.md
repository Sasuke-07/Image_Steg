# Image Steganography Web Application

This project is a simple web application that allows users to embed secret messages within an image using steganography. After embedding the message, the user can protect it with a password to ensure secure extraction later.

## Features

- **Image Upload**: Users can upload an image file.
- **Message Embedding**: The application hides a secret message within the image.
- **Password Protection**: Users can set a password to protect the hidden message.
- **Message Extraction**: The message can be extracted by re-uploading the image and entering the correct password.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Cryptography**: SJCL (Stanford JavaScript Crypto Library)

## How It Works

1. **Upload an Image**: Users choose an image from their device.
2. **Enter a Message**: Users input the message they want to hide.
3. **Create a Password**: The password is used to encrypt the message.
4. **Embed the Message**: The image with the embedded message can be downloaded.
5. **Extract the Message**: To retrieve the hidden message, the user re-uploads the image and provides the correct password.

## File Structure

- `index.html`: The main HTML file for the user interface.
- `main.js`: The JavaScript file handling the steganography logic, image processing, and password encryption.
- `main.css`: The stylesheet for styling the web page.
- `sjcl.js`: The Stanford JavaScript Crypto Library used for encryption.

## Installation and Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/Sasuke-07/Image_Steg.git
    ```

2. Open the `index.html` file in your browser to run the application locally.

## Usage

1. Upload an image from your device.
2. Enter the message you want to hide.
3. Set a password to encrypt the message.
4. Click the **Embed Message** button to generate the steganographic image.
5. To extract the message, upload the steganographic image and enter the password.

## Security

- The message is encrypted with the password using SJCL, ensuring that only those with the correct password can retrieve the message.

## Contributing

1. Fork the repository.
2. Create your feature branch:

    ```bash
    git checkout -b feature/your-feature
    ```

3. Commit your changes:

    ```bash
    git commit -m 'Add new feature'
    ```

4. Push to the branch:

    ```bash
    git push origin feature/your-feature
    ```

5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
