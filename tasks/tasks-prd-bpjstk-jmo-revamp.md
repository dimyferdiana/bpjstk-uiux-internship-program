# Task List: BPJSTK JMO Mobile App Revamp  
**Filename:** `tasks-prd-bpjstk-jmo-revamp.md`  
**Parent PRD:** `prd-bpjstk-jmo-revamp.md`  

---

## Relevant Files  
- `designs/claim-flow.fig` - Figma file for JHT claim redesign  
- `designs/payment-dashboard.fig` - Payment tracking UI  
- `research/user-personas.md` - Research findings and personas  
- `prototype/main.fig` - Clickable prototype  
- `docs/style-guide.md` - Design system documentation  

---

## Tasks  

### [ ] 1.0 User Research & Audit  
  - [ ] 1.1 Conduct stakeholder interviews (2 sessions)  
  - [ ] 1.2 Create 3 user personas (Budi, Siti, Admin)  
  - [ ] 1.3 Map current JHT claim user journey  
  - [ ] 1.4 Audit existing UI against WCAG 2.1 AA  
  - [ ] 1.5 Compile findings into `research/audit-report.md`  

### [ ] 2.0 Design System Update  
  - [ ] 2.1 Define color palette (ensure contrast ≥4.5:1)  
  - [ ] 2.2 Standardize typography (Inter, 16pt min)  
  - [ ] 2.3 Create reusable components:  
    - [ ] 2.3.1 Form inputs  
    - [ ] 2.3.2 Status badges  
    - [ ] 2.3.3 Progress stepper  
  - [ ] 2.4 Document in `docs/style-guide.md`  

### [ ] 3.0 JHT Claim Flow Redesign  
  - [ ] 3.1 Simplify to 3-step process (Verify → Upload → Submit)  
  - [ ] 3.2 Design auto-fill functionality for known data  
  - [ ] 3.3 Add inline validation with error prevention  
  - [ ] 3.4 Implement document upload guidance (tooltips)  

### [ ] 4.0 Payment Tracking UX  
  - [ ] 4.1 Design dashboard with color-coded statuses  
  - [ ] 4.2 Create timeline visualization for payments  
  - [ ] 4.3 Add "Download Receipt" functionality  
  - [ ] 4.4 Implement push notification system mockup  

### [ ] 5.0 Prototype & Testing  
  - [ ] 5.1 Build clickable prototype covering:  
    - [ ] 5.1.1 Happy path (successful claim)  
    - [ ] 5.1.2 Error recovery (document rejection)  
  - [ ] 5.2 Conduct usability tests with 5 users  
  - [ ] 5.3 Iterate based on feedback (max 2 cycles)  

### [ ] 6.0 Documentation & Handoff  
  - [ ] 6.1 Compile project report (`docs/final-report.md`)  
  - [ ] 6.2 Prepare developer handoff package:  
    - [ ] 6.2.1 Design specs  
    - [ ] 6.2.2 Asset exports (SVG/PNG)  
  - [ ] 6.3 Write internship testimonials  

---

## Notes  
1. **Completion Protocol:**  
   - Mark sub-tasks as `[x]` only after:  
     1. Peer review by another intern  
     2. Approval from UI/UX Manager  
   - Parent tasks marked `[x]` only when **all** sub-tasks are complete.  

2. **Testing:**  
   - Use Figma Mirror for prototype testing.  
   - WCAG validation via Stark plugin.  

3. **Weekly Checkpoints:**  
   - Every Friday 2PM: Demo completed sub-tasks.  
   - Get "Go" approval before starting next parent task.  

--- 