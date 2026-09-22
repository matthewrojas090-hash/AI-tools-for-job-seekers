# AI Offer Comparison and Decision Organizer

Compare job offers and late-stage opportunities using confirmed facts, personal priorities, and clearly labeled uncertainty—without allowing AI to make the decision for you.

## What this tool does

This workflow helps job seekers:

- Organize multiple offers in one consistent format
- Separate guaranteed compensation from variable or uncertain value
- Compare role scope, manager support, learning, flexibility, and commute
- Identify missing or conflicting information
- Build questions for recruiters and hiring managers
- Consider personal priorities without exposing unnecessary private information
- Document tradeoffs and decision deadlines
- Create a negotiation-preparation brief based on verified information
- Make the final decision using human judgment

AI organizes the information you provide. It cannot determine the true value of equity, predict company success, guarantee career growth, or know which opportunity will make you happiest.

## Appropriate use

Use this workflow when you have:

- Two or more written offers
- One offer and another late-stage interview process
- A current role and a new opportunity to compare
- Different compensation structures that are difficult to compare
- Important unanswered questions before a decision deadline

Do not upload complete offer letters, tax documents, identity documents, background-check information, bank information, home addresses, signatures, or confidential employer materials into an external AI system.

## What you need

Gather only the information needed for your comparison:

- Company and role labels
- Role title and level
- Work location and required schedule
- Base salary
- Confirmed bonus terms
- Equity type and stated grant information
- Vesting schedule
- Benefits information
- Paid time off
- Start date
- Decision deadline
- Reporting structure
- Role responsibilities
- Learning or advancement information
- Travel or commute requirements
- Confirmed conditions or contingencies
- Questions that remain unanswered

Use `Unknown` when something has not been confirmed. Do not ask AI to estimate missing compensation or assign a guaranteed value to private-company equity.

## Personal-priorities template

Rank only the factors you are comfortable sharing. You may use general labels instead of explaining private circumstances.

```text
MY PRIORITIES

Priority 1:
Importance: Essential / High / Medium / Low
What meeting this priority would look like:

Priority 2:
Importance: Essential / High / Medium / Low
What meeting this priority would look like:

Priority 3:
Importance: Essential / High / Medium / Low
What meeting this priority would look like:

Additional considerations:
- Role scope:
- Manager and team:
- Learning and advancement:
- Stability and risk tolerance:
- Work arrangement:
- Commute or travel:
- Schedule flexibility:
- Benefits:
- Start timing:
- Other:

Information I do not want included in the output:
```

## Offer-input template

Repeat this template for every opportunity.

```text
OPPORTUNITY LABEL:

STATUS
Written offer received: Yes / No
Current interview stage:
Decision deadline:
Start date:
Conditions or contingencies:

ROLE
Title:
Level:
Reporting to:
Main responsibilities:
Team information:
Confirmed success expectations:
Advancement information:
Learning opportunities:

WORK ARRANGEMENT
Location:
Onsite, hybrid, or remote:
Required onsite days:
Expected schedule:
Travel requirement:
Estimated commute:
Relocation requirement or support:

COMPENSATION
Base salary:
Sign-on payment:
Guaranteed bonus:
Variable or performance bonus:
Commission or incentive terms:
Equity type:
Equity grant information:
Vesting schedule:
Exercise price or terms, if applicable:
Compensation information still unclear:

BENEFITS
Health coverage information:
Retirement contribution or match:
Paid time off:
Leave programs:
Other confirmed benefits:
Benefit costs or details still unknown:

EVIDENCE
Source for compensation information:
Source for role information:
Source for work-arrangement information:
Verbal statements that need written confirmation:
Missing or conflicting information:

QUESTIONS OR CONCERNS
Questions for the recruiter:
Questions for the hiring manager:
Known tradeoffs:
Other factual notes:
```

## Copy-and-paste AI prompt

```text
You are helping me organize a factual comparison of job offers or late-stage opportunities.

Use only the information I provide. Do not invent compensation, benefits, equity value, company performance, promotion timelines, manager quality, job security, deadlines, or employer intentions.

Do not provide legal, tax, investment, immigration, or financial advice. Do not choose an offer for me. Do not calculate a probability of success or claim to know which opportunity is objectively best.

My priorities:

[PASTE THE COMPLETED PERSONAL-PRIORITIES TEMPLATE]

Opportunity information:

[PASTE EACH COMPLETED OFFER-INPUT TEMPLATE]

Complete the following:

### 1. Information-quality and privacy review

Separate the information into:

- Confirmed written terms
- Confirmed role or interview information
- Verbal statements needing written confirmation
- Missing information
- Conflicting information
- Estimates or assumptions that must not be presented as facts
- Private or unnecessary information that should be removed

### 2. Side-by-side comparison

Create this table:

| Category | Opportunity A | Opportunity B | Opportunity C, if supplied | Evidence status | Important uncertainty |
|---|---|---|---|---|---|

Include only applicable categories:

- Current status
- Decision deadline
- Role and level
- Scope and responsibilities
- Reporting structure
- Base salary
- Guaranteed payments
- Variable compensation
- Equity terms
- Benefits
- Paid time off
- Work arrangement
- Commute or travel
- Start date
- Learning opportunities
- Advancement information
- Conditions or contingencies

Keep guaranteed, variable, and uncertain compensation separate.

### 3. Compensation evidence review

Create these sections:

1. Guaranteed cash supported by written terms
2. Variable compensation with confirmed rules
3. Equity information exactly as supplied
4. Benefits that may have financial value but require verification
5. Missing information needed for a responsible comparison

Do not assign a guaranteed cash value to equity. Do not assume a bonus will be earned. Do not calculate after-tax pay unless I provide an approved method and separately confirm that I understand it is only an estimate.

### 4. Priority alignment

For each of my stated priorities, create this table:

| Priority | Importance | Opportunity evidence | Alignment | Missing information | Question to resolve |
|---|---|---|---|---|---|

Use these alignment labels:

- Supported: The supplied facts show alignment
- Partially supported: Some evidence exists, but important details are missing
- Not supported: The supplied facts conflict with the stated priority
- Unknown: There is not enough evidence

Do not create a total score unless I explicitly request one. If I request a score, show the assumptions and keep the written evidence beside it.

### 5. Role and career tradeoffs

For each opportunity, organize:

- Scope I would own
- Skills I could use
- Skills I could develop
- Information about manager or team support
- Advancement statements that are confirmed
- Risks or constraints supported by facts
- Claims that still need verification

Do not predict promotions, company growth, layoffs, manager behavior, or future job satisfaction.

### 6. Practical-life comparison

Compare only the information supplied for:

- Required location
- Onsite expectations
- Commute or travel
- Schedule
- Start date
- Flexibility
- Benefits
- Other stated priorities

Do not ask for or infer health information, family status, caregiving responsibilities, disability, age, religion, or other protected or highly personal information. Use the priorities I voluntarily provided without explaining why I have them.

### 7. Questions to ask

Create two concise lists for each opportunity:

- Questions for the recruiter about written terms, process, benefits, or deadlines
- Questions for the hiring manager about scope, expectations, support, team, and decision authority

Prioritize questions that could materially change the comparison. Do not ask questions already answered by confirmed information.

### 8. Decision-risk review

Flag:

- Deadlines that overlap
- Verbal promises without written confirmation
- Unclear variable-compensation rules
- Equity information that could be misunderstood
- Different titles with unclear level equivalence
- Work-arrangement expectations that may conflict
- Contingencies or conditions
- Missing benefits information
- Assumptions that are influencing the comparison

For each item, state the evidence and a reasonable human follow-up.

### 9. Negotiation-preparation brief

Using only confirmed information, create a preparation brief containing:

- What I value about the opportunity
- The specific term or question I want to discuss
- The factual reason it matters to my decision
- The clarification or change I may request
- Acceptable alternatives I supplied
- Information I should confirm in writing

Do not invent competing offers, deadlines, market data, leverage, relationships, or personal circumstances. Do not write threats or misrepresent my situation.

### 10. Decision summary

Create a neutral summary containing:

- Strongest evidence-supported advantage of each opportunity
- Most important evidence-supported tradeoff of each opportunity
- Uncertainties that could change the comparison
- My highest-priority unanswered questions
- The decision deadline for each opportunity
- The next three actions I should consider

Do not name a winner or tell me what to choose.

### 11. Human decision worksheet

Finish with these reflection questions:

1. Which opportunity best supports my essential priorities based on confirmed evidence?
2. Which tradeoffs am I willing—and unwilling—to accept?
3. Which assumptions am I treating as facts?
4. What information could materially change my decision?
5. Which commitments should I obtain in writing?
6. Have I spoken with qualified tax, legal, immigration, or financial professionals where needed?
7. Can I explain my decision in my own words without relying on an AI score?

Finish with this reminder:

“AI organized the information you supplied. Verify every term against the written offer and official benefit materials, seek qualified advice when needed, and make the final decision using your own priorities and judgment.”
```

## Fictional example

### Priorities

```text
Priority 1: Technical recruiting leadership scope
Importance: High
What meeting this priority would look like: Own strategy and remain involved in searches

Priority 2: Predictable hybrid schedule
Importance: Essential
What meeting this priority would look like: No more than two required onsite days

Priority 3: Manager support
Importance: High
What meeting this priority would look like: Confirmed weekly one-on-ones and clear first-90-day expectations
```

### Synthetic opportunity information

```text
OPPORTUNITY LABEL: Northstar Labs
Written offer received: Yes
Decision deadline: October 2
Title: Lead Technical Recruiter
Base salary: $165,000
Variable bonus: Target 10%; payout rules not supplied
Equity: Private-company option grant; value not established
Work arrangement: Hybrid, two required onsite days
Role scope: Own senior engineering searches and help develop recruiting processes
Manager support: Weekly one-on-ones confirmed verbally
Missing information: Bonus plan, equity terms, and written onsite expectation

OPPORTUNITY LABEL: Bluebird Systems
Written offer received: Yes
Decision deadline: September 30
Title: Senior Talent Partner
Base salary: $175,000
Variable bonus: None listed
Equity: Restricted stock units with a four-year vesting schedule; share value not included in this example
Work arrangement: Hybrid, three required onsite days
Role scope: Own senior engineering searches; no recruiting-program ownership confirmed
Manager support: First-90-day plan included in written offer materials
Missing information: Current share-value reference and advancement expectations
```

### Example priority-alignment output

| Priority | Importance | Northstar Labs | Bluebird Systems | Information needed |
|---|---|---|---|---|
| Technical recruiting leadership scope | High | Supported by confirmed search and process ownership | Partially supported; search ownership confirmed, program scope unknown | Ask Bluebird about process ownership |
| Predictable hybrid schedule | Essential | Partially supported; two days stated verbally | Not supported; three required days confirmed | Ask Northstar to confirm schedule in writing |
| Manager support | High | Partially supported; weekly meetings stated verbally | Supported by written first-90-day plan | Confirm Northstar cadence and onboarding expectations |

The example does not identify a winner. Northstar appears more aligned with the stated schedule and leadership priorities, but important terms remain verbal or incomplete. Bluebird provides stronger written onboarding evidence and higher guaranteed base salary, while requiring an additional onsite day.

## Optional recruiter-question prompt

After verifying the comparison, use this prompt:

```text
Draft a concise, appreciative message asking the recruiter to clarify the items below.

Opportunity:
What I value about the role:
Confirmed offer terms:
Questions that remain:
Decision deadline:

Do not invent competing offers, urgency, conversations, or personal circumstances. Keep the tone collaborative. Separate requests for clarification from negotiation requests. Ask for material commitments in writing.
```

## Review guidance

Before relying on the output:

1. Compare every compensation term with the written offer.
2. Verify benefits through official materials or the appropriate company representative.
3. Keep verbal statements labeled until confirmed in writing.
4. Do not treat private-company equity as guaranteed cash.
5. Confirm deadlines and extension requests directly with the recruiter.
6. Review tax, legal, immigration, or investment questions with qualified professionals.
7. Remove private information before saving or sharing the comparison.
8. Make the final decision yourself.

## Responsible-AI and privacy safeguards

- Remove names, addresses, signatures, and personal contact information.
- Do not upload complete offer letters or confidential documents into an unapproved AI system.
- Do not provide bank, tax, identity, background-check, medical, immigration, or family information.
- Do not ask AI to predict company success, layoffs, promotion, or job satisfaction.
- Do not treat equity, bonuses, commissions, or benefits as guaranteed value.
- Do not allow a numeric score to hide missing information or personal tradeoffs.
- Do not fabricate competing offers or negotiation leverage.
- Verify every material term against official sources.
- Use employer-approved or personally trusted systems with appropriate privacy controls.
- Keep the final career decision under human control.

## Intended impact

This workflow is designed to reduce manual comparison, expose missing information, and help job seekers ask better questions before a deadline. It does not guarantee a better offer, successful negotiation, or employment outcome.

## Disclaimer

This resource provides general organizational support. It is not financial, tax, investment, legal, immigration, benefits, or career advice. Consult qualified professionals when those issues affect your decision.

All organizations, roles, compensation figures, dates, and examples are fictional and synthetic.
