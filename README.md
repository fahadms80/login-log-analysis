# login-log-analysis

Simple login log analysis and detection of failed login attempts.

---

## Risk Summary

Based on the log analysis:

- We detected 3 failed login attempts from user `admin` at IP `10.0.0.5` within 1 minute.
- This indicates a possible brute-force attack.

### Risk Components:
- **Asset:** Login system
- **Threat:** Unauthorized access attempt
- **Vulnerability:** No login attempt limit
- **Impact:** High (could lead to account compromise)

### Recommendation:
- Implement login lockout after 3 failed attempts.
