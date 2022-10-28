# Three Tier Architecture for Web Applications on AWS
A project on a three tier architecture for web applications hosted on AWS.

## What Is A Three-tier Architecture?

A three-tier architecture divides web applications into three layers: presentation (or web) tier, application tier and database tier. 
- Web tier runs on clients' web browser, and is the user interface (UI) of the application. This layer is where the users interact with the application by sending information to the application or requesting information from the application.
- Application tier contains the business logic and core functionalities of the application. It processes the information and requests collected from the user, then stores the information in the database or retrieves requested information from the database tier and send it back to the user.
- Database tier stores the data of the application.

## Security In Three-tier Architecture

In a three-tier architecture, the web tier is accessible from the Internet. However, only the web tier can "talk" to the application tier, and only the application tier can "talk" to the database tier.

## Architecture Diagram

[<img src="">]

This is an architecture for a three-tier web application hosted on AWS.

## Detailed Instruction

See instruction.docx.

## Additional Services

## Future Enhancement
