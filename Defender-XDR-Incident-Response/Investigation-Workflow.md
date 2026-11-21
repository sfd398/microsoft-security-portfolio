# Investigation Workflow

## Initial Alert

Alert Source:
- Microsoft Defender for Office 365
- Microsoft Defender XDR
- Microsoft Sentinel

## Investigation Steps

### Step 1 - Identify User

Gather:

- Username
- Email Address
- Device Name
- Sign-in History

### Step 2 - Assess Risk

Determine:

- Was MFA completed?
- Was the sign-in successful?
- Was the sign-in location unusual?

### Step 3 - Search For Additional Activity

Review:

- Mailbox activity
- SharePoint activity
- Teams activity
- Device activity

### Step 4 - Contain

Actions:

- Disable account
- Reset password
- Revoke sessions
- Isolate device

### Step 5 - Recovery

- Reinstate account
- Verify device health
- Monitor activity
