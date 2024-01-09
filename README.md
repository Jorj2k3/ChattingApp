# Java Chat Application Project

## Classes and Interfaces

### `Server` Class
- **Extends:** `JFrame`
- **Implements:** `ActionListener`
- **Characteristics:**
  - Socket programming for basic server functionality.
  - GUI development using Swing components (`JPanel`, `JButton`, `JTextField`, `JLabel`, etc.).
  - Handles user actions through the implementation of `ActionListener`.

### `Client` Class
- **Extends:** `JFrame`
- **Implements:** `ActionListener`
- **Characteristics:**
  - Establishes a connection to the server using socket programming.
  - GUI development with Swing components for user interface.
  - Implements `ActionListener` for handling user actions.

### `ActionListener` Interface
- **Purpose:**
  - Handles user actions, such as button clicks.
  - Requires the implementation of the `actionPerformed` method.

## Other Aspects
- Both classes use static variables (`vertical`, `f`) for shared state.
- Socket streams (`DataInputStream`, `DataOutputStream`) facilitate communication between server and client.
- Static methods for formatting labels and handling time display in the GUI.

## Usage

1. **Server:**
   - Run the `Server` class to start the server.
   - The server will listen for incoming client connections.

2. **Client:**
   - Run the `Client` class to launch the client GUI.
   - Connect to the server by entering the server's IP address and port.

3. **Chatting:**
   - Start sending messages between the server and clients.

## Dependencies

- Java Swing for GUI development.


