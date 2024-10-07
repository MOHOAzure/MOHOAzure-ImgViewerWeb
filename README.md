# MOHOAzure-ImgViewerWeb
Using Chrome's latest file system handler to implement local image viewer. See `Security` section for more details.

# Demo
[Demo](https://imgur.com/a/5w74MZ8)

# Features
- Fullscreen Viewing: Supports fullscreen display of animated images in local directories, including formats like JPG, PNG, APNG, WEBP, AVIF, and GIF, providing an immersive viewing experience.

- Automatic Image Loading: Automatically loads and displays the next image when scrolling down with the mouse wheel, eliminating the need for additional clicks and enhancing fluidity of operation.

- Re-select Directory: Allows users to reselect the local folder, providing flexible management of image sources. To cancel re-seleciton, users can click on the blank area.

- Clear Browser Data: Offers a one-click clear function to remove recorded data, ensuring user privacy and data security.

- Thumbnail Preview List: A thumbnail preview list is displayed at the bottom of the screen without obstructing the main viewing area, allowing users to easily select and view desired images.

- Horizontal Scrolling of Thumbnails: Users can scroll horizontally within the thumbnail area using the mouse wheel, facilitating quick browsing when the thumbnail list exceeds the visible area.

- Independent Area Interaction: When the mouse is over the thumbnail area, vertical scrolling only affects the thumbnail list and does not interfere with the main viewing area, ensuring intuitive and convenient interactions.


# Security
The File System Access API in modern browsers is designed with security in mind. When a user grants a website access to local files or directories, the permission is session-based and temporary. Once the browser is closed, the granted file access permissions are automatically revoked. This means that upon reopening the browser, the website will no longer have access to the previously authorized files or directories, and the user will need to explicitly re-grant access if needed.

This mechanism ensures that file access is not persistent across browser sessions, enhancing user privacy and security by limiting the duration and scope of the granted permissions.