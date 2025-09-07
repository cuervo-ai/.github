<!-- 
🚀 CUERVO Platform Pull Request Template
Please fill out this template to help us review your changes efficiently.
-->

## 📋 Pull Request Summary

### What does this PR do?
<!-- Provide a concise description of what this PR accomplishes -->

### Why is this change needed?
<!-- Explain the problem this PR solves or the feature it adds -->

### Related Issues
<!-- Link to related issues using "Closes #123", "Fixes #456", or "Related to #789" -->

---

## 🔍 Change Details

### Type of Change
<!-- Check the box that best describes this PR -->
- [ ] 🐛 Bug fix (non-breaking change that fixes an issue)
- [ ] ✨ New feature (non-breaking change that adds functionality)
- [ ] 💥 Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] 📚 Documentation update (changes to documentation only)
- [ ] 🔧 Configuration change (changes to CI/CD, build tools, etc.)
- [ ] ♻️ Refactoring (code change that neither fixes a bug nor adds a feature)
- [ ] 🎨 Style/UI changes (changes that affect the appearance or user experience)
- [ ] 🏗️ Infrastructure (changes to deployment, docker, k8s, etc.)
- [ ] 🔒 Security (changes that improve security)

### Component/Service Affected
<!-- Check all that apply -->
- [ ] 🎯 Frontend (cuervo-admin)
- [ ] 🔧 Backend Platform (cuervo-mcp-platform)
- [ ] 🤖 Agent Service (cuervo-agent-service)
- [ ] ⚡ Execution Service (cuervo-execution-service)
- [ ] 🔐 Auth Service (cuervo-auth-service)
- [ ] 📊 Metrics Service (cuervo-metrics-service)
- [ ] 🔔 Notification Service (cuervo-notification-service)
- [ ] 🌐 MCP Server (cuervo-mcp-server)
- [ ] 🔗 MCP Integration (cuervo-mcp-integration)
- [ ] ⚖️ Consensus Layer (cuervo-hydra-hicon)
- [ ] 🖥️ Desktop Client (cuervo-menou)
- [ ] 🧩 Plugins (cuervo-plugins)
- [ ] 📚 Shared Libraries (shared-kernel/types)
- [ ] 🏗️ Infrastructure (cuervo-infrastructure)
- [ ] 📖 Documentation (cuervo-docs)
- [ ] 🚪 Gateway (cuervo-gateway)

---

## 🧪 Testing

### Testing Strategy
<!-- Describe how you tested these changes -->
- [ ] Unit tests added/updated
- [ ] Integration tests added/updated
- [ ] End-to-end tests added/updated
- [ ] Manual testing performed
- [ ] Performance testing conducted
- [ ] Security testing performed

### Test Coverage
<!-- If applicable, mention test coverage changes -->
- Previous coverage: __%
- New coverage: __%

### Manual Testing Checklist
<!-- Check all that were manually tested -->
- [ ] Feature works as expected in development environment
- [ ] Feature works as expected in staging environment
- [ ] No regression in existing functionality
- [ ] Cross-browser compatibility verified (if frontend)
- [ ] Mobile responsiveness verified (if frontend)
- [ ] API endpoints tested with various inputs (if backend)
- [ ] Error handling tested
- [ ] Performance impact assessed

---

## 🔒 Security Considerations

### Security Impact Assessment
<!-- Check all that apply and explain if necessary -->
- [ ] No security implications
- [ ] Adds new authentication/authorization
- [ ] Modifies existing security controls
- [ ] Introduces new dependencies
- [ ] Changes data access patterns
- [ ] Modifies API surface
- [ ] Changes network configuration
- [ ] Updates cryptographic operations

### Security Checklist
- [ ] No sensitive data exposed in logs
- [ ] Input validation implemented
- [ ] Output sanitization implemented
- [ ] Authorization checks in place
- [ ] No hardcoded credentials
- [ ] Dependencies security scanned
- [ ] HTTPS/TLS properly configured
- [ ] CORS policies reviewed

---

## 📊 Performance Impact

### Performance Considerations
<!-- Check if this change affects performance -->
- [ ] No performance impact expected
- [ ] Performance improvements expected
- [ ] Potential performance degradation (explain below)
- [ ] Performance testing required

### Performance Testing Results
<!-- Include any performance benchmarks if applicable -->
```
Before: 
After: 
Improvement: 
```

---

## 🚀 Deployment

### Deployment Requirements
<!-- Check all that apply -->
- [ ] No special deployment requirements
- [ ] Database migrations required
- [ ] Configuration changes required
- [ ] Infrastructure updates required
- [ ] Restart services required
- [ ] Cache clearing required
- [ ] CDN invalidation required

### Rollback Plan
<!-- Describe how to rollback if issues arise -->

### Feature Flags
<!-- If using feature flags, describe the rollout strategy -->
- [ ] No feature flags used
- [ ] Feature flag configuration: `FEATURE_NAME=true`
- [ ] Gradual rollout planned
- [ ] A/B testing setup

---

## 📖 Documentation

### Documentation Updates
<!-- Check all that apply -->
- [ ] No documentation changes needed
- [ ] README updated
- [ ] API documentation updated
- [ ] User documentation updated
- [ ] Developer documentation updated
- [ ] Architecture documentation updated
- [ ] Deployment documentation updated

### Additional Context
<!-- Add any additional context about the changes -->

---

## ✅ Pre-merge Checklist

### Code Quality
- [ ] Code follows project style guidelines
- [ ] Self-review completed
- [ ] Code is properly commented
- [ ] No console.log/debug statements left
- [ ] No TODO comments left (unless tracked in issues)
- [ ] Error handling is appropriate
- [ ] Code is DRY (Don't Repeat Yourself)

### Git Hygiene
- [ ] Commit messages are clear and descriptive
- [ ] Branch is up to date with target branch
- [ ] No merge conflicts
- [ ] Commit history is clean (squash if necessary)

### Dependencies
- [ ] No new dependencies added without justification
- [ ] New dependencies are actively maintained
- [ ] Security vulnerabilities checked
- [ ] License compatibility verified

### Monitoring & Observability
- [ ] Appropriate logging added
- [ ] Metrics/telemetry added if needed
- [ ] Error tracking configured
- [ ] Alerts configured if needed

---

## 🤝 Review Guidelines

### For Reviewers
Please check:
- [ ] Code quality and maintainability
- [ ] Security considerations
- [ ] Performance implications
- [ ] Test coverage adequacy
- [ ] Documentation completeness
- [ ] Breaking change impact

### Review Criteria
- **Security**: Critical security changes require approval from @cuervo-ai/security
- **Architecture**: Significant architectural changes require approval from @cuervo-ai/architecture
- **Performance**: Changes affecting critical paths require performance review
- **Breaking Changes**: Must be approved by @cuervo-ai/maintainers

---

## 📝 Additional Notes

### Screenshots/Videos
<!-- Add screenshots or videos demonstrating the changes, especially for UI changes -->

### Dependencies
<!-- List any new dependencies or significant dependency updates -->

### Migration Guide
<!-- If this is a breaking change, provide migration instructions -->

### Future Considerations
<!-- Any follow-up work or considerations for future iterations -->

---

## 🏷️ Labels
<!-- The following labels will be automatically applied based on your selections above -->
<!-- maintainers will adjust as needed during review -->

**Estimated Review Time:** <!-- small/medium/large -->
**Priority:** <!-- low/medium/high/critical -->

---

<sub>
🤖 Generated with CUERVO Platform Development Standards
| [Contributing Guide](./CONTRIBUTING.md) | [Code of Conduct](./CODE_OF_CONDUCT.md) | [Security Policy](./SECURITY.md)
</sub>