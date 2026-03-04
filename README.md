# IT Support & Help Desk Portfolio - Jira Demo

This repository showcases my hands-on experience with **Jira Service Management** as a ticketing system for IT Support / Help Desk roles.  
I created a free Jira Cloud project to simulate real-world scenarios: creating, prioritizing, assigning, collaborating on, and resolving tickets (issues).

**Key skills**:
- Ticket creation & detailed documentation
- Priority management (Highest for blockers, varied for realism)
- Comment-based collaboration & updates
- Basic workflow transitions (To Do → In Progress → Resolved)

## Sample Tickets (Examples)

### 1. Network/Infrastructure Incident - WiFi Unstable

**Summary**: Office main WiFi unstable – Frequent disconnections
- **Issue Type**: Incident
- **Priority**: Highest (complete blockage for multiple users)
- **Assignee**: Diego (me, as primary agent)
- **Full Description**:  
  Since 10 AM, WiFi on floor 3 drops every 10-15 minutes.  
  Affects ~15 users (cannot access shared drives or video calls).  
  Ethernet works fine. Router LED flashing orange intermittently.  
  Attempts: Router restart → temporary fix but returns.  
  Urgent: Impacts productivity on entire floor.
- **Comments / Updates**:  
  - Requester: "Happening on multiple devices."  
  - Me: "Escalated to ISP. Temporary workaround: use mobile hotspot. ETA for fix: 2 hours."
**Outcome (simulated)**: Escalation handled + clear communication to keep users productive.

### 2. Critical Access Incident - Outlook Login Blocked


**Summary**: User unable to log in – Persistent login error

- **Issue Type**: Incident  
- **Priority**: Highest (complete blockage for the user)  
- **Assignee**: Diego (me, as primary agent)  
- **Full Description**:  
  The user reports they have been unable to log in to the internal system since yesterday.  
  Error message: "Invalid credentials" even though the password is correct.  
  Password reset attempted → email not received.  
  Impact: Blocks access to corporate email and daily tools.  
  Urgent: Prevents remote work completely.  
- **Comments / Updates**:  
  - Requester: "Tried on another browser and mobile device, same error."  
  - Me: "Checking account in Active Directory. Resetting password manually in 10 min."  
  - Update: "Password reset. Try with temporary one: Temp123 and change it immediately."  

**Why Highest Priority?** Total loss of access with no workaround without intervention.  
**Outcome (simulated)**: Quick password reset + verification to restore access.

### 3. Software Issue - Payroll App Crash

**Summary**: Payroll app crashes when generating monthly report

- **Issue Type**: Incident  
- **Priority**: High (serious impact with partial workaround)  
- **Assignee**: Diego  
- **Full Description**:  
  When trying to export the March payroll report, the application closes without any error message.  
  Happens on Windows 11 with Edge/Chrome.  
  Steps to reproduce:  
  1. Log in  
  2. Go to Reports > Monthly Payroll  
  3. Select March period  
  4. Click Export PDF → crash.  
  Impact: Prevents month-end accounting close.  
  Attachment: screenshot of the step before crash (simulated).  
- **Comments / Updates**:  
  - Requester: "Started after the February update."  
  - Me: "Reproduced the issue. Escalated to dev team. Temporary workaround: export to Excel instead."  

**Why High Priority?** Blocks a critical monthly process, but workaround allows partial continuation.  
**Outcome (simulated)**: Workaround communicated + escalation for permanent fix.

### 4. Hardware Request - Additional Monitor

**Summary**: Request for additional monitor for home office setup

- **Issue Type**: Service Request  
- **Priority**: Medium (improves productivity, not blocking)  
- **Assignee**: Diego
- **Full Description**:  
  Need an extra monitor (24" or larger) for dual-screen setup.  
  Reason: Working with multiple apps at once (Excel + CRM + browser).  
  Preferred model: Dell or similar (if in stock).  
  Delivery: Office pickup or ship to home address.  
- **Comments / Updates**:  
  - Requester: "Prefer one with HDMI and USB-C if possible."  
  - Me: "In stock and approved by manager. Shipping scheduled for Friday."  

**Why Medium Priority?** Enhances efficiency but user can continue with current setup.  
**Outcome (simulated)**: Request approved, delivery initiated.

### 5. Simple Query / How-to - Outlook Signature Setup

**Summary**: How to set up automatic email signature in Outlook?

- **Issue Type**: Service Request / Question  
- **Priority**: Low (quick how-to, no business impact)  
- **Assignee**: Diego  
- **Full Description**:  
  Hi, need step-by-step instructions to add a professional automatic signature in Outlook (desktop and web versions).  
  Include company logo if possible.  
  Thanks!  
  Using Outlook 365.  
- **Comments / Updates**:  
  - Requester: "Using Outlook 365."  
  - Me: "Guide attached: Step 1: File > Options > Mail > Signatures... [detailed steps]."  

**Why Low Priority?** Simple instructional request with no urgency or impact.  
**Outcome (simulated)**: Clear instructions provided → quick self-resolution.







