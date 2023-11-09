# Local Storage and How to Use It On Webistes

## Why would a developer use local storage for a web application?

> Developers use local storage for web applications for various reasons, primarily to store data on the client-side (in the user's browser) instead of on the server. Local storage provides a way to store and retrieve data, such as settings, user preferences, or application-specific data, directly in the user's browser.

## What information should not be stored in local storage?

> Certain categories of data should be avoided when utilizing local storage because of security and privacy considerations. Local storage can be accessed by JavaScript running on the same domain, which implies that mishandling sensitive information in this storage can expose it to potential security vulnerabilities.

* passwords
* authentication tokes
* PII
* Financial data
* session data (session identifiers or user roles)
* API Keys and secrets

## Local storage can store what type of data? How would you convert it to that type before storing?

> Local storage is capable of housing information exclusively in the format of strings. It exclusively accommodates string data, necessitating the conversion of other data types, such as numbers, objects, and arrays, into strings before storing them. This transformation process is commonly known as "serialization."