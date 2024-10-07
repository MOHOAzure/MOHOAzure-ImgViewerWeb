# MOHOAzure-ImgViewerWeb
Using Chrome's latest file system handler to implement local image viewer. See `Security` section for more details.

# Demo
[Demo](https://imgur.com/a/5w74MZ8)

# Features
- Large screen or fullscreen viewing animated pictures in local directory.
- Scolling thumbnails.
- Re-select directory.
- Clear recorded data on browser

# Security
The File System Access API in modern browsers is designed with security in mind. When a user grants a website access to local files or directories, the permission is session-based and temporary. Once the browser is closed, the granted file access permissions are automatically revoked. This means that upon reopening the browser, the website will no longer have access to the previously authorized files or directories, and the user will need to explicitly re-grant access if needed.

This mechanism ensures that file access is not persistent across browser sessions, enhancing user privacy and security by limiting the duration and scope of the granted permissions.