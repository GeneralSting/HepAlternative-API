# HepAlternative-API

- HepAlternative-API is the backend API for the [HepAlternative project](https://github.com/GeneralSting/HepAlternative). Together with the HepAlternative frontend, this API forms a completely refactored version of the [PIN-Elektra project](https://github.com/GeneralSting/HEP-Elektra), featuring a modernized backend and frontend design.

## Introduction

- HepAlternative-API serves as the backend of the HepAlternative project, providing the necessary services and database interactions for managing an information system for electricity consumption, focusing on managing customers, items, and creating invoices. It enables customer administration by adding, updating and deleting data, while ensuring the uniqueness of the customer code and the meter. The system supports the creation of an invoice, where the user can select the customer, items and enter the quantity to generate the invoice. Accounts can be reversed, and canceled accounts are not shown in the overview or statistics. The application also allows users to view the invoices created for their registered meters.

## Project Status

- this API is currently under development. Below is the current progress:

- completed :white_check_mark:
  - read-only access to database data
- in Progress :construction:
  - implementation of login and registration functionality
    - add tables to the database with the correct organizational logic
  - adding authentication and authorization mechanisms
  - enabling write, update, and delete operations in addition to read-only access

![hepa-realtionships](https://github.com/user-attachments/assets/91ee93a8-2c67-44bb-a660-b90efd4aef4f)

## API Documentation :construction:

- The API documentation is in progress and will be updated as features are implemented. It will include endpoints for user authentication, data management, and more.
