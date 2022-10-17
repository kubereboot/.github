# Security Policy

## Supported Versions

Kured releases versions in accordance with [the Semantic Version
specification](https://semver.org/):

- `<major>.<minor>.<patch>`
- Minor versions are increased for every new Kubernetes release, so every 3 months.
  If the newest Kubernetes release is `1.<x>.0`, we will make sure to build against
  the client libraries of `1.<x-1>.0`, so we support `1.<x>`, `1.<x-1>` and `1.<x-2>`.
  *Example:* Kubernetes 1.48.0 was just released. Next Kured minor release will
  use client libraries of 1.47, so we can support K8s `1.4{6,7,8}`.
- Patch releases of Kured are released on an ongoing basis, whenever the team
  decides it's worth releasing. No guarantees.
- Security fixes (e.g. CVEs fixed in dependencies) are currently not backported to
  older minor release versions.

The above describes the current development model. It's what our small team is
capable of delivering right now in terms of release management, testing, etc.

This means that the best support and most secure experience is always going to be
on the latest version of Kured.

## Reporting a Vulnerability

Please reach out to our private mailing lists `cncf-kured-maintainers@lists.cncf.io`.
We will get back to you as soon as we can and discuss the next steps to resolve the
issue and disclose the issue responsibily.

Thanks in advance for helping us make Kured more secure.
