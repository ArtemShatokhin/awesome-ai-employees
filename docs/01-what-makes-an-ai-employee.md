# What makes an AI employee (and not a chatbot)

Three properties separate an AI employee from an assistant:

1. **A standing role.** It holds a job across sessions — support triage, sales ops, a weekly brief —
   and the job description is written down somewhere you can read.
2. **Memory that survives the session.** Tuesday's decisions are available on Friday, or the employee
   relearns the same context every time.
3. **A permission model.** It reaches real tools, so something has to decide what it may do without a
   person, what waits for approval, and what it may never do.

A chatbot has none of the three. An agent framework gives you the mechanism for all three but leaves
the packaging to you. An AI employee is the packaging: role, memory, tools, review.

The fourth property, the one that decides whether a security review passes, is **who owns the
rules**. If the answer is "the vendor's console", the employee is rented. If the answer is "a file in
our repository", it is owned.
