# MockBank API Documentation

This repository contains the **OpenAPI specification** for the MockBank API, providing interactive API documentation using **Swagger UI**, hosted on GitHub Pages.

## Features

- OpenAPI specification defined in YAML.
- Interactive API documentation powered by Swagger UI.
- API endpoint descriptions, request parameters, and response schemas.
- OAuth 2.0 authentication support using Auth0.
- Documentation automatically published through GitHub Pages.

## Repository Structure

```text
├── index.html       # Swagger UI configuration
├── openapi.yaml     # OpenAPI specification
└── README.md        # Repository documentation
```

## View API Documentation

Access the interactive Swagger UI documentation at:

https://YOUR_USERNAME.github.io/mockbank-api-spec/

## Local Setup

Clone the repository and start a local HTTP server:

```bash
git clone https://github.com/YOUR_USERNAME/mockbank-api-spec.git
cd mockbank-api-spec
python -m http.server 8000
```

Open http://localhost:8000 in your browser.

## Contributing

To update the API documentation, modify `openapi.yaml` and push your changes to the main branch. GitHub Pages will publish the updated documentation automatically.
