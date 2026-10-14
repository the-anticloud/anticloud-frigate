# How to Update — FRIGATE

**Project:** `FRIGATE`
**Category:** SURVEILLANCE_CAMERA
**Domain:** surveillance camera
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
FRIGATE --version
FRIGATE check-update
```

### Applying Updates
```bash
pip install --upgrade FRIGATE
```

### Rolling Back
```bash
pip install FRIGATE==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
