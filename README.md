# ASAPFiles

SocketShare is a simple file-sharing application built using WebSockets. It allows users to upload and transfer files in real-time over a persistent WebSocket connection.

## Features

- **Real-Time File Transfer**: Upload files and send them to the server in real-time.
- **Chunk-Based File Transmission**: Files are sent in chunks, ensuring compatibility with large file sizes.
- **Persistent Connection**: A single WebSocket connection is used for the entire file-sharing process.
- **Server-Side File Reconstruction**: The server reassembles the file from chunks and saves it locally.
- **Progress Updates**: Real-time progress updates can be added for file uploads.

## Technologies Used

- **Backend**: Node.js with Express and ws (WebSocket library).
- **Frontend**: NextJS.
