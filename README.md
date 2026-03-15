# CODEOWNERS Test Repository

This repository is used to verify CODEOWNERS behavior on GitHub.

## Purpose

Test whether all code owners need to approve a PR when files from multiple
directories with different owners are changed in a single PR.

## Directory Structure

| Directory | Owner |
|---|---|
| `imgs/product-a/` | @gh-test-1733 |
| `imgs/product-b/` | @gh-test-1733 |
| `imgs/product-c/` | @testuser452 |
| `imgs/web-service/` | @gh-test-1733 |
test case 5
