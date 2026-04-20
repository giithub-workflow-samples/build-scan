# Black Duck SCA Build Scan

This repository demonstrates a **full build scan** with Black Duck SCA using GitHub Actions.

## Overview

A full build scan installs dependencies and runs a comprehensive Black Duck SCA scan to detect open source vulnerabilities in your project.

## Workflow

See the sample workflow: [.github/workflows/main.yml](.github/workflows/main.yml)

## Results

[View Scan Results](https://giithub-workflow-samples.github.io/build-scan/execution-logs/)

## Usage

1. Fork this repository
2. Set the following secrets in your repository:
   - `BLACKDUCK_URL` — Your Black Duck server URL
   - `BLACKDUCK_TOKEN` — Your Black Duck API token
3. Push a commit to trigger the scan

## Documentation

[Black Duck Security Scan Action Documentation](https://documentation.blackduck.com/bundle/bridge/page/documentation/c_github-blackduck.html)

