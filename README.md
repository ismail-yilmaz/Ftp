
# FTP package for U++ 


This package provides an easy-to-use interface to the client side of the File Transfer Protocol
as specified in RFC 959, with support for a number of advanced capabilities.

## Features

- Time-constrained blocking, and non blocking operation modes.
- Multithreaded file transfers, using worker threads.
- IPv6 connections and NATs, as specified in RFC 2428.
- Ftp over TLS/SSL (FTPS), as specified in RFC 2228.
- Feature negotiation mechanism as specifien in RFC 2389.
- Parsing of UNIX and DOS style directory listings.
- Extending the existing functionality of Ftp class.
- Transfer restart/resume mechanism, as specified in RFC 3959.
- UTF-8 encoded path names.

## Examples

| Name               | Description |
|---                 |---          |
| FtpGet             | Demonstrates basic FTP file download in blocking mode.     |
| FtpGetNB           | Demonstrates basic FTP file download in non-blocking mode. |
| FtpGetMT           | Demonstrates basic Ftp file download, using a worker thread. |
| FtpGUI             | Demonstrates a basic FTP browser with GUI (with upload, download, mkdir, rename, delete commands). |
| FtpMultiGetMT      | Demonstrates FTP dir listing and concurrent file transfers, using worker threads. |
| FtpOverTLS         | Demonstrates the secure connection capability of FTP package in blocking mode. |
| FtpQueryFeatures   | Demonstrates the feature query mechanism, as defined in RFC 2389 |
| FtpRawCommand      | Demonstrates FTP raw command execution in blocking mode. |
| FtpConsumerGet     | Demonstrates the usage of a consumer function for Ftp download in blocking mode. |
| FtpConsumerGetMT   | Demonstrates the usage of a consumer function for Ftp download, using a worker thread. |

* Note: FtpGUI's interface is inspired by qt's (v4.8) [FtpExample](http://doc.qt.io/archives/qt-4.8/qt-network-qftp-example.html)

