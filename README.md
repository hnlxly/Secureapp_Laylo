## DevSecOps Pipeline Features

- SAST (Semgrep)
- Dependency Scanning (pip-audit)
- Secret Detection (Gitleaks)
- Container Scanning (Trivy)
- SBOM Generation (Syft)

## Artifacts Produced

- SBOM (CycloneDX)
- Vulnerability Reports
- Image Tag (Commit SHA)

## Trusted Build

The Docker image is only built if all security scans pass.
