# How to Test if a SOCKS5 Proxy Works

This guide provides instructions on how to test if a SOCKS5 proxy works on Windows, macOS, and Linux.

## Windows

1. Open Command Prompt.
2. Use `curl` to test the SOCKS5 proxy:
    ```sh
    curl --socks5 <proxy_host>:<proxy_port> http://www.google.com
    ```

## macOS

1. Open Terminal.
2. Use `curl` to test the SOCKS5 proxy:
    ```sh
    curl --socks5 <proxy_host>:<proxy_port> http://www.google.com
    ```

## Linux

1. Open Terminal.
2. Use `curl` to test the SOCKS5 proxy:
    ```sh
    curl --socks5 <proxy_host>:<proxy_port> http://www.google.com
    ```

Replace `<proxy_host>` with the proxy server address and `<proxy_port>` with the proxy port number. If the proxy is working, you should see the HTML content of the Google homepage.
