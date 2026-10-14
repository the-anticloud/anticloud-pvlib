# How to Update — PVLIB

**Project:** `PVLIB`
**Category:** SOLAR
**Domain:** solar
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
PVLIB --version
PVLIB check-update
```

### Applying Updates
```bash
pip install --upgrade PVLIB
```

### Rolling Back
```bash
pip install PVLIB==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
