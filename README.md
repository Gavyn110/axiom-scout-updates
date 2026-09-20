# Axiom Scout Updates

This public repository contains only update metadata and encoded release packages for Axiom Scout. It must not contain wallet credentials, recovery phrases, private keys, user settings, trade databases, or logs.

The installed Control Center reads `manifest.json`, downloads the listed package parts over HTTPS, verifies the decoded ZIP against the published SHA-256, backs up the current application, installs the update, and can roll back the application files if needed.
