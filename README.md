# Image Steganography Web Application

This project is an image steganography web application that allows users to embed secret messages within an image. After embedding the message, the user can protect the steganographic image with a password, which will be required for future extraction of the message.

## Features

- **Image Upload**: Users can upload an image of their choice.
- **Message Embedding**: Users can input a secret message to be hidden within the uploaded image.
- **Password Protection**: After embedding the message, users can create a password to secure the image.
- **Message Extraction**: With the correct password, the hidden message can be extracted from the steganographic image.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js (optional, based on your stack)
- **Cryptography**: Using SJCL (Stanford JavaScript Crypto Library) for encryption and password handling.

## How It Works

1. **Upload an Image**: Users choose an image from their device.
2. **Enter a Message**: The user inputs the message they want to hide.
3. **Create a Password**: The password ensures only authorized users can extract the message.
4. **Download the Image**: The image with the embedded message can be downloaded.
5. **Extract the Message**: To retrieve the message, the user reuploads the image and provides the correct password.

## Installation and Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your-repo-name
    ```

3. Install the necessary dependencies (if applicable):

    ```bash
    npm install
    ```

4. Run the project locally:

    ```bash
    npm start
    ```

5. Open your browser and navigate to:

    ```bash
    http://localhost:3000
    ```

## Usage

1. Visit the main page.
2. Upload your image and enter a secret message.
3. Set a password for the image.
4. Click the **Embed Message** button.
5. Download the steganographic image.
6. To extract the message, return to the site, upload the image, and provide the password.

## Security

- The embedded message is encrypted using the user's password, ensuring that only users with the correct password can extract the message.
- The project uses the SJCL (Stanford JavaScript Crypto Library) for encryption and decryption.

## Contributing

1. Fork the repository.
2. Create your feature branch:

    ```bash
    git checkout -b feature/your-feature
    ```

3. Commit your changes:

    ```bash
    git commit -m 'Add some feature'
    ```

4. Push to the branch:

    ```bash
    git push origin feature/your-feature
    ```

5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

