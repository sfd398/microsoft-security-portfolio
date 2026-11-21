# Conditional Access Policy Matrix

| Policy | Users | Action |
|----------|----------|----------|
| Require MFA | All Users | Require MFA |
| Admin Protection | Administrators | MFA Every Sign-In |
| Block Legacy Authentication | All Users | Block |
| High Risk Sign-In | All Users | Block Access |
| New Device Registration | All Users | Require MFA |
| Remote Access | All Users | Require MFA |

## Deployment Order

1. Report Only Mode
2. Pilot Group
3. IT Staff
4. Officers
5. All Members
