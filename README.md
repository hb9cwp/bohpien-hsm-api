# Bohpien HSM GRPC API

GRPC API definition for Bohpien HSM.

## Overview
Bohpien HSM is an MIT licensed open source HSM (Hardware Security Module) that enables sensitive cryptographic processing to be offloaded to a dedicated 
machine. The main API is written in GRPC so that:
- Interfaces can be used for both client and server side
- Underlying service implementation can be implemented in various programming languages.

## Features
Bohpien HSM supports the following functions:
- Message digesting
- Encryption functions
- Decryption functions
- Random number generation functions
- Signature generation function

## Building

- Clone repository
    
    ```
    $ git clone https://github.com/edipermadi/bohpien-hsm-api.git
    ```

- Build and install

    ```
    $ cd bohpien-hsm-api
    $ mvn clean package install
        
    ``` 
