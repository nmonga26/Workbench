# ONDC Workbench

Developer tools and utilities for ONDC ecosystem.

## Tools Include:
- API Testing Suite
- Protocol Validator
- Mock Server
- Development Environment Setup

## Quick Start

### API Testing Suite
```bash
cd api-testing
npm install
npm run test
```

### Protocol Validator
```bash
cd protocol-validator
python -m pip install -r requirements.txt
python validate.py --spec path/to/spec.json
```

### Mock Server
```bash
cd mock-server
docker build -t ondc-mock-server .
docker run -p 8080:8080 ondc-mock-server
```

## Development Setup

1. Clone this repository
2. Install dependencies for each tool
3. Configure environment variables
4. Run the desired tool

## Related Repositories
- [ONDC-Specifications](https://github.com/nmonga26/ONDC-Specifications)
- [Services](https://github.com/nmonga26/Services)
- [Reference-SDKs-Services](https://github.com/nmonga26/Reference-SDKs-Services)
