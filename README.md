# ITE183 Laboratory 2 - WebSocket Server

A simple WebSocket chat server developed using **Bonezegei Scripting Language v1.3.3** for ITE183 - Web Systems and Technologies.

This project demonstrates real-time communication between multiple browser clients using WebSockets.

## Features

- Real-time message broadcasting between connected clients
- WebSocket connection and disconnection handling
- Client identification and message logging
- HTTP server running on port 8000
- Custom 404 page for undefined routes

## How to Run

1. Install Bonezegei Scripting Language v1.3.3.
2. Clone or download this repository.
3. Open the project folder in VS Code.
4. Install the required dependencies using `bzg install`.
5. Start the server using `bzg run`.
6. Open `http://localhost:8000` in your browser.

**Note:** On Windows, the HTTP library may require the MinGW-w64 `libwinpthread-1.dll` runtime to be available in the system's DLL search path.

## Testing

Open `http://localhost:8000` in two separate browser windows.

Send messages from either window and verify that both clients receive the broadcast messages.

To test the custom 404 page, visit `http://localhost:8000/nonexistent`.

## Project Files

- `app.bzg` - HTTP and WebSocket server implementation
- `package.json` - Project configuration and dependencies
- `public/index.html` - WebSocket chat interface
- `public/404.html` - Custom 404 page
- `lib/` - Required HTTP library files
- `documentation/` - Laboratory screenshots and testing evidence

## Documentation

Screenshots demonstrating the installation, server execution, multi-client communication, and 404 page testing are available in the `documentation` folder.

## License

This project is licensed under the MIT License.