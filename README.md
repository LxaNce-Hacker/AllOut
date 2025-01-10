# AllOut - Logout Everywhere

AllOut is a simple web application that helps you securely log out from multiple online accounts with just one click. It supports a wide variety of popular websites and ensures that your session ends properly, giving you peace of mind about your online security.

👉 [LIVE](https://lxance.site/allout/) 👈

## Features

- **One-click Logout:** Log out from multiple online services simultaneously.
- **Supports Popular Sites:** Includes platforms like Gmail, Amazon, GitHub, YouTube, and more.
- **Clean UI:** A responsive, modern design with an intuitive interface.
- **Easy to Use:** Just open the application, and it will start the logout process for the listed websites.

## How It Works

AllOut uses `GET` and `POST` requests to send logout commands to various websites. The application creates hidden `img` or `iframe` elements to execute these requests in the background. A visual status is displayed for each site to indicate the logout process:

- **Pending**: Logging out in progress.
- **Success**: Successfully logged out.
- **Failed**: Logout attempt failed.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/LxaNce-Hacker/AllOut
   ```

2. Navigate to the project folder:
   ```bash
   cd AllOut
   ```

3. Open `index.html` in your web browser.

## Usage

1. Open the `index.html` file in a browser.
2. The application will automatically attempt to log you out from all listed websites.
3. Observe the status updates for each website in the grid.

## Supported Websites

The following websites are currently supported:

- AOL
- Amazon
- Blogger
- Delicious
- DeviantART
- DreamHost
- Dropbox
- eBay
- Gandi
- GitHub
- Gmail
- Google
- Hulu
- Instapaper
- Linode
- LiveJournal
- MySpace
- Netflix
- New York Times
- Newegg
- Photobucket
- Skype
- Slashdot
- SoundCloud
- Steam Community
- Steam Store
- ThinkGeek
- Threadless
- Tumblr
- Vimeo
- Wikipedia
- Windows Live
- Woot
- WordPress
- Yahoo!
- YouTube

## Limitations

- Logout functionality is dependent on the current structure and API of the supported websites. Changes made by the website providers might break the functionality.
- Some websites may require manual intervention if additional logout confirmation is needed.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes.
   ```bash
   git commit -m "Add your message here"
   ```
4. Push your changes.
   ```bash
   git push origin feature-name
   ```
5. Open a pull request on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Disclaimer

This application is for educational purposes only. Use it responsibly and ensure that you have the proper permissions to log out from any accounts. The developer is not responsible for any misuse of this tool.

---

Stay safe. Log out everywhere with **AllOut**!
