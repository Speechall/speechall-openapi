# Speechall API OpenAPI Specification

This repository contains the official OpenAPI 3.0 specification file for the Speechall REST API.

The Speechall API provides robust and flexible speech-to-text capabilities, allowing users to transcribe audio using various providers and apply custom text replacement rules.

## What is OpenAPI?

OpenAPI Specification (formerly Swagger Specification) is a language-agnostic, standard description format for RESTful APIs. This file (`openapi.yaml`) serves as a contract that precisely defines the API's endpoints, parameters, request/response formats, authentication methods, and more.

## Purpose of this Repository

The purpose of this repository is to provide developers, partners, and API tooling with the canonical, machine-readable definition of the Speechall API interface.

This `openapi.yaml` file can be imported into various tools to:

*   Generate client libraries (SDKs) in different programming languages.
*   Generate interactive API documentation (like Swagger UI or Redoc).
*   Configure API gateways or testing tools (like Postman).
*   Understand the API structure without needing to manually inspect endpoints.

## What's Included Here

This repository **only** contains the `openapi.yaml` file.

It does **not** include:

*   The Speechall API server code.
*   Official client libraries (SDKs) – these will be in separate repositories.
*   Detailed tutorials or guides (refer to the official documentation).
*   Example code for using the API.

These other resources are maintained separately.

## Using the Specification

1.  **Clone or Download:** Get a copy of this repository.
2.  **Use with Tools:** Import the `openapi.yaml` file into your preferred OpenAPI-compatible tool (e.g., OpenAPI Generator, Swagger UI, Postman, Stoplight Studio, etc.). Consult your tool's documentation for specific instructions on importing an OpenAPI file.

## Getting Started with the API

To actually make calls to the Speechall API described by this specification, you will need an API key and should consult the official Speechall API documentation:

*   **Official Documentation:** https://speechall.com/docs
*   **API Base URL:** `https://api.speechall.com/v1`
*   **Authentication:** API Key via `Authorization: Bearer YOUR_API_KEY` header.

## Contribution

If you find any inaccuracies, inconsistencies, or missing details in the `openapi.yaml` specification file itself, please feel free to open an issue or submit a pull request in this repository.

## License

The OpenAPI specification file (`openapi.yaml`) in this repository is licensed under the [MIT License](LICENSE).