# QuicStreams - Python Implementation of QUIC Protocol

### Ariel Shamay

**Email:** [arielsh49@gmail.com](mailto:arielsh49@gmail.com)

---

## Project Overview

**QuicStreams** is a Python implementation of the **QUIC (Quick UDP Internet Connections)** protocol, designed for efficient, reliable, and secure network communication over UDP. It supports advanced stream management, providing separate streams within the same connection for improved data transfer and multiplexing.

---

## Main Features

- **QUIC Protocol Implementation**: Reliable and secure transport protocol over UDP.
- **Client-Server Architecture**: Easy-to-use client and server modules (`QuicClient`, `QuicServer`).
- **Stream Management**: Independent input/output streams (`StreamIn`, `StreamOut`) for efficient data handling.
- **Performance Experiments**: Scripts and tools for testing and comparing protocol performance (`exp.py`).
- **Comprehensive Testing**: Automated testing modules ensuring reliability (`TestQuicClient.py`, `TestQuicServer.py`).
- **Network Traffic Analysis**: Compatibility with network analysis tools (e.g., Wireshark, using `.pcapng` files).

---

## Project Structure

- **`QuicClient.py` / `QuicServer.py`**: Main client and server implementations.
- **`StreamIn.py` / `StreamOut.py`**: Handle input and output streams.
- **`QUIC_API.py`**: User-friendly API for interacting with QUIC functionalities.
- **`exp.py`**: Script to perform performance testing and comparisons.
- **`experiments` folder**: Contains data and scripts related to experimental runs.
- **`Test*` files**: Automated test scripts ensuring functionality correctness.

---

## Setup Instructions

### Requirements

- Python 3.x
- Libraries (if any specific libraries are required, list them here)

### Installation

Clone the repository:

```bash
git clone <repository_url>
cd QuicStreams
```

Install dependencies (if required):

```bash
pip install -r requirements.txt
```

### Running the Application

- To start the server:

```bash
python QuicServer.py
```

- To start the client:

```bash
python QuicClient.py
```

### Running Tests

Execute automated test scripts:

```bash
python TestQuicServer.py
python TestQuicClient.py
```

---

## Technologies & Tools

- **Python**
- **Wireshark** (for network traffic analysis)
- **QUIC Protocol**

---

## Notes

Ensure your Python environment is properly configured, including any required libraries, for seamless execution and testing.
