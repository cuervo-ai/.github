# Security Policy

## Supported Versions

We currently provide security updates for the following versions of CUERVO platform components:

| Component | Version | Supported |
| --------- | ------- | --------- |
| Core Services | 1.x.x | ✅ |
| Agent Service | 1.x.x | ✅ |
| Execution Service | 1.x.x | ✅ |
| Metrics Service | 1.x.x | ✅ |
| Admin Dashboard | 1.x.x | ✅ |

## Reporting a Vulnerability

We take the security of CUERVO platform seriously. If you discover a security vulnerability, please follow these steps:

### 1. Do Not Open a Public Issue

Please do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.

### 2. Report Privately

Send a detailed report to our security team:
- **Email**: security@cuervo.cloud
- **Subject**: [SECURITY] Vulnerability Report - [Brief Description]

### 3. Include Details

Please include as much of the following information as possible:
- Type of vulnerability (e.g., SQL injection, XSS, authentication bypass)
- Full paths of source file(s) related to the vulnerability
- Location of the affected source code (tag/branch/commit/direct URL)
- Special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

### 4. Response Timeline

- **Initial Response**: Within 48 hours of report submission
- **Status Update**: Within 7 days with preliminary assessment
- **Resolution**: Timeline depends on severity and complexity

## Security Best Practices

### For Contributors

- Enable two-factor authentication on your GitHub account
- Use signed commits when contributing
- Never commit secrets, API keys, or credentials
- Follow secure coding practices
- Run security scans before submitting pull requests

### For Users

- Keep all CUERVO components updated to the latest versions
- Use strong authentication methods
- Regularly review access logs
- Follow the principle of least privilege
- Implement proper network security measures

## Security Features

CUERVO platform includes built-in security features:

- **Authentication**: JWT-based authentication with refresh tokens
- **Authorization**: Role-based access control (RBAC)
- **Data Protection**: Encryption at rest and in transit
- **Audit Logging**: Comprehensive activity tracking
- **Input Validation**: Protection against injection attacks
- **Rate Limiting**: Protection against abuse

## Security Updates

Security updates are distributed through:
- GitHub Security Advisories
- Release notes
- Email notifications to registered users

## Contact

For security-related questions or concerns:
- **Security Team**: security@cuervo.cloud
- **General Contact**: hola@cuervo.cloud

## Acknowledgments

We appreciate the security research community's efforts in responsibly disclosing vulnerabilities. Contributors who report valid security issues will be acknowledged in our security advisories (unless they prefer to remain anonymous).