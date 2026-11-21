# KQL Query Library

## Failed Sign-ins

```kusto
SigninLogs
| where ResultType != 0
| summarize Count=count() by UserPrincipalName
```

## Successful Admin Sign-ins

```kusto
SigninLogs
| where ResultType == 0
| where UserPrincipalName contains "admin"
```

## Risky Sign-ins

```kusto
SigninLogs
| where RiskLevelDuringSignIn != "none"
```
