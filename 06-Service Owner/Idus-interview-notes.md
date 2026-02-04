# System Management Self-Assessment Questionnaire

**Purpose:** To understand how our critical systems are currently managed, for IT capacity planning.

## YOUR INFORMATION

**Your name:** Elena/Tom

**Your department/team:** Inköp/UH

---

## SECTION 1: SYSTEM OVERVIEW

**System name:** Idus

**Number of active users:** 30

**Who currently manages this system day-to-day?**
Elena/Tom

---

## SECTION 2: HOSTING & INFRASTRUCTURE

### How is this system hosted?
Check ONE box:
- [ ] Cloud/SaaS - Vendor manages everything (we access through web browser)
- [ ] Vendor-hosted - Vendor manages servers, we manage the system
- [x] Self-hosted - We have servers in our office/data center
- [ ] Not sure
- [ ] Other: _____

### Who manages these components?
Check the appropriate column for each component:

| Component | Vendor does this | We do this | Not sure |
|-----------|------------------|------------|----------|
| Servers/infrastructure | [ ] | [x] | [ ] |
| Backups | [ ] | [x] | [ ] |
| System updates/patches | [ ] | [x] | [ ] |
| System monitoring | [ ] | [x] | [ ] |
| Database | [ ] | [x] | [ ] |

### Vendor information
- **Vendor/product name:** Idus AB
- **Do we have a support contract?** Yes / No / Not sure

---

## SECTION 3: TIME OVERVIEW

**This is the most important section. Please estimate time spent on different activities.**

### Total Time
**Approximately how much total time do you spend on this system per week?**

**Normal week:** _____ hours per week

**Busiest week (month-end, year-end, etc.):** _____ hours per week

**How often are busy weeks?** _____ times per year

**What makes weeks busy?** (Check all that apply)
- [ ] Month-end closing
- [ ] Year-end closing
- [ ] Payroll processing
- [ ] Audit periods
- [ ] System updates
- [ ] Other: _____

---

### Time Breakdown

**Of the total time above, approximately how many hours per week do you spend on each category:**

*Please estimate as best you can. It's okay if totals don't match exactly.*

#### TECHNICAL OPERATIONS

| Activity | Hours per week | Examples/notes |
|----------|----------------|----------------|
| **System monitoring & health checks** | _____ | Checking if system is running, reviewing logs, checking backups |
| **Technical troubleshooting & fixing issues** | _____ | System down, error messages, performance problems |
| **System updates & patches** | _____ | Installing updates, testing patches (average per week) |
| **Integration monitoring & troubleshooting** | _____ | Fixing connections to other systems |
| **Backup verification** | _____ | Checking backups completed successfully |

**Subtotal - Technical Operations:** _____ hours/week

---

#### USER MANAGEMENT

| Activity | Hours per week | Examples/notes |
|----------|----------------|----------------|
| **Creating/removing user accounts** | 0.5 | Setting up new users, removing when people leave |
| **Password resets** | _____ | Helping users who forgot passwords |
| **Changing user permissions** | _____ | Adjusting what users can access/do |

**Subtotal - User Management:** 0.5 hours/week

---

#### USER SUPPORT

| Activity | Hours per week | Examples/notes |
|----------|----------------|----------------|
| **Technical support** | _____ | Can't log in, error messages, system slow/down |
| **Business support** | _____ | "How do I...", process questions, how to use features |

**Subtotal - User Support:** _____ hours/week

---

#### BUSINESS ACTIVITIES

| Activity | Hours per week | Examples/notes |
|----------|----------------|----------------|
| **Business configuration** | _____ | Setting up workflows, approval rules, business settings |
| **Creating reports & data exports** | _____ | Running reports, exporting data for users |
| **User training** | _____ | Training new users, training sessions |
| **Business documentation** | _____ | Writing user guides, process documentation |

**Subtotal - Business Activities:** _____ hours/week

---

#### OTHER

| Activity | Hours per week | Examples/notes |
|----------|----------------|----------------|
| **Vendor coordination** | _____ | Contacting vendor for support, meetings with vendor |
| **Meetings about this system** | _____ | Regular meetings, planning meetings |
| **Other (please specify):** | _____ | |
| _____ | _____ | |

**Subtotal - Other:** _____ hours/week

---

### TOTAL TIME CHECK

**Add up all subtotals above:** _____ hours/week

*This should roughly match your "normal week" estimate at the top of this section. If very different, please review and adjust.*

---

### Task Classification

**Of all the work you do on this system, roughly what percentage requires:**

- **Purely technical skills** (IT knowledge, not business knowledge): _____%
  - *Example: Checking server logs, applying patches, troubleshooting errors*

- **Purely business knowledge** (process knowledge, not IT skills): _____%
  - *Example: Deciding approval workflows, training users on processes, business reports*

- **Mixed** (both technical and business knowledge needed): _____%
  - *Example: Configuring integrations, complex troubleshooting*

**Total should equal 100%:** _____%

---

## SECTION 4: TECHNICAL OPERATIONS DETAIL

**Complete this section only if you spend time on technical operations (monitoring, troubleshooting, updates, backups)**

### Daily/Weekly Technical Checks

**What technical checks do you perform regularly?**

| Check | Do this? | How often? | Minutes each time |
|-------|----------|------------|-------------------|
| Check system is running/accessible | Yes / No | _____ times per _____ | _____ min |
| Verify backups completed | Yes / No | _____ times per _____ | _____ min |
| Review error logs | Yes / No | _____ times per _____ | _____ min |
| Check server disk space/resources | Yes / No | _____ times per _____ | _____ min |
| Check integration status | Yes / No | _____ times per _____ | _____ min |
| Other: _____ | Yes / No | _____ times per _____ | _____ min |

---

### Technical Issues & Incidents

**In the last 3 months, approximately:**
- **Total number of technical problems:** _____ 
  - *Technical problems = system down, can't access, error messages, performance issues*
- **Minor problems** (fixed in less than 1 hour): _____
- **Major problems** (took more than 1 hour or caused downtime): _____

**Most recent significant technical problem:**
- **What happened?** _____
- **How long to fix it?** _____ hours
- **Who helped fix it?** _____

**Do you have recurring technical problems?**
- Yes / No
- **If yes, describe:** _____
- **How often does it happen?** _____ times per _____
- **Time to fix each time:** _____ minutes

---

### System Updates & Patches

**In the last 12 months:**
- **Number of system updates/patches applied:** _____
- **Average time per update** (planning + testing + doing it): _____ hours
- **Did any updates cause problems?** Yes / No
  - **If yes, describe:** _____

**Update process:**
- **Can you test updates before applying to production?** Yes / No
- **Do updates require scheduled downtime?** Yes / No
- **Who approves updates before they're applied?** _____

---

### Backup Management

**Do you verify backups work?**
- Yes / No
- **If yes, how often?** _____
- **Time per verification:** _____ minutes

**Have you ever had to restore data from backup?**
- Yes / No
- **If yes, how long did it take?** _____ hours

---

## SECTION 5: USER ACCESS MANAGEMENT DETAIL

**Complete this section only if you spend time managing user access**

### Creating New Users
- **New user accounts per month:** 1-2
- **Time per account (technical setup):** 5 minutes
- **Who decides what access level new users need?** Department owner
- **Time to decide/approve permissions:** 2-5 minutes

### Removing Users
- **Users removed per month:** 1-2
- **How do you know when to remove someone?** Got notify from HR/Department owner
- **Time per removal:** 2-5 minutes

### Changing Permissions
- **Permission change requests per month:** Rarely
- **Time per change:** 0 minutes
- **Who decides permission levels?** Department owner

### Password Resets
- **Password reset requests per week:** None -- using same password
- **Time per reset:** 0 minutes
- **Can users reset their own passwords?** No

---

## SECTION 6: USER SUPPORT DETAIL

**Complete this section only if you provide user support**

### Support Volume

**Per week, approximately how many support requests about:**

| Request Type | Number per week | Average minutes per request |
|--------------|----------------|----------------------------|
| **Technical issues** (can't log in, errors, system down) | _____ | _____ min |
| **Business questions** ("how do I...", process questions) | _____ | _____ min |
| **Data questions** (where is data, why is this value X) | _____ | _____ min |
| **Report/export requests** | _____ | _____ min |
| **Other:** _____ | _____ | _____ min |

### Support Channels
**How do users contact you for support?** (Check all that apply)
- [ ] Email
- [ ] Phone
- [ ] Skype/other chats
- [ ] Walk up to your desk
- [ ] Other: _____

---

## SECTION 7: CURRENT IT INVOLVEMENT

### When IT is Currently Involved

**When do users currently contact IT (not you) about this system?** (Check all that apply)
- [ ] Cannot access system / Login problems
- [ ] System error messages
- [ ] Performance issues (system slow)
- [ ] Network/connectivity issues
- [ ] Never - users only contact me/my team
- [ ] Other: _____

**What does IT currently help you with for this system?**
- _____
- _____
- _____

**What do you handle vs what IT handles?**
- **Your team handles:** _____
- **IT team handles:** _____
- **Unclear/both:** _____

**How often do you need IT support for this system?**
- [ ] Never
- [ ] Rarely (few times per year)
- [ ] A few times per month
- [ ] Weekly
- [ ] Daily


---

## SECTION 8: INTEGRATIONS

### Connected Systems

**Which other systems does this one connect/integrate with?**
1. _____
2. _____
3. _____
4. _____


---

### Integration Issues

**In the last 3 months:**
- **How many times did an integration break or have problems?** _____
- **What typically breaks?** _____
- **How do you discover it's broken?** _____
- **Average time to fix integration issues:** _____ hours
- **Who do you contact for help with integrations?** _____

---

## SECTION 9: VENDOR COORDINATION

**Complete this section only if you coordinate with the software vendor**

### Vendor Interactions

**In the last 12 months, approximately:**

| Interaction Type | Number | Average time each |
|------------------|--------|-------------------|
| **Technical support tickets** (bugs, errors, system issues) | _____ | _____ hours |
| **Business/feature discussions** (how to use features, requests) | _____ | _____ hours |
| **Vendor meetings/calls** | _____ | _____ hours |

**Vendor responsiveness:** (Check one)
- [ ] Good - usually responds quickly and helpful
- [ ] Average - sometimes slow but eventually helpful
- [ ] Poor - slow or not helpful


---

## SECTION 10: BUSINESS ACTIVITIES DETAIL

**Complete this section only if you spend time on business configuration, reports, or training**

### Business Configuration
**Time spent per month on:**
- Setting up workflows, approval rules: _____ hours
- Configuring business settings: _____ hours
- Other configuration: _____ hours

### Reports & Data
**Time spent per week on:**
- Regular reports (weekly/monthly): _____ hours
- Ad-hoc data requests from users: _____ hours

**How many regular reports do you create/maintain?** _____

### User Training
**Time spent on:**
- Training each new user (business processes): _____ hours per person
- Number of new users trained per year: _____
- Other training sessions per year: _____ hours

### Documentation
**Time spent per year on:**
- Creating/updating user guides: _____ hours
- Writing process documentation: _____ hours

---

## FOR OFFICE USE ONLY

**Received date:** _____
**Reviewed by:** _____
**Follow-up needed:** Yes / No
**Notes:** _____
