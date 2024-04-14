# URL Shortener Project

Welcome to my URL shortener project! This is my first backend project built using Node.js, Express, and MongoDB.


# Overview

This project aims to provide a simple and efficient way to shorten long URLs into more manageable and shareable links. With this application, you can generate short URLs for any long URL you provide, making it easier to share links, especially on platforms with character limits like Twitter.


# Features

Shorten URLs: Easily shorten long URLs into shorter, more manageable links.

Customizable URLs: Optionally, you can provide a custom alias for your shortened URL.

Statistics: Track basic statistics such as the number of times a shortened URL has been accessed.

Secure: Uses MongoDB for data storage and Express for handling HTTP requests, ensuring security and reliability.


# Usage

Send a POST request to /shorten endpoint with a JSON payload containing the long URL you want to shorten.

Optionally, you can provide a custom alias for your shortened URL.

The server will respond with a shortened URL.

Use the shortened URL to access the original long URL.
