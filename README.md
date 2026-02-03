# Global Security Community Wiki

This repository hosts the Global Security Community Wiki, built with MkDocs and deployed to Azure Static Web Apps.

## Local Development

### Prerequisites

- Python 3.x
- pip

### Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the development server:
   ```bash
   mkdocs serve
   ```

3. Open your browser to `http://127.0.0.1:8000`

### Building

To build the static site:
```bash
mkdocs build
```

The built site will be in the `site/` directory.

## Deployment

This site is automatically deployed to Azure Static Web Apps when changes are pushed to the `main` branch. The deployment workflow is configured in `.github/workflows/azure-static-web-apps.yml`.

## Project Structure

```
.
├── docs/              # Documentation source files
│   └── index.md      # Home page
├── mkdocs.yml        # MkDocs configuration
├── requirements.txt  # Python dependencies
└── staticwebapp.config.json  # Azure Static Web Apps configuration
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
