# PRD: BPJSTK JMO Mobile App Revamp - JHT Claims & Payment Tracking

**Filename:** `prd-bpjstk-jmo-revamp.md`  
**Created:** July 21, 2025  
**Status:** Draft  
**Owner:** UI/UX Team  

## 1. Introduction/Overview
### Problem Statement
The current BPJSTK JMO Mobile app exhibits significant usability issues in JHT (Jaminan Hari Tua) claim submission and payment tracking flows, resulting in:
- 42% incomplete claim submissions (per Q2 2025 analytics)
- 67% support calls related to payment status inquiries
- Average 8.5 minutes completion time for claims

### Solution Approach
Redesign the user experience focusing on:
1. Streamlined JHT claim submission
2. Transparent payment tracking
3. Mobile-optimized accessibility

### Key Benefits
- Estimated 30% reduction in claim processing time
- 40% decrease in support queries
- Improved user satisfaction (target: 85%+ in post-launch survey)

## 2. Goals & Objectives
| ID | Objective | Success Metric |
|----|-----------|----------------|
| G1 | Simplify claim submission | ≤6min completion time |
| G2 | Improve payment visibility | ≤3 taps to view status |
| G3 | Enhance accessibility | WCAG 2.1 AA compliance |
| G4 | Reduce user errors | 50% fewer form resubmissions |

## 3. User Stories
### Primary Persona: "Budi" (Factory Worker, 38)
1. **Claim Submission**  
   "As a BPJSTK member, I want to submit JHT claims quickly during my lunch break so I don't need to visit the office."

2. **Payment Tracking**  
   "As a frequent claimant, I need to see all my payment histories in one place to plan my finances."

## 4. Functional Requirements
### 4.1 JHT Claim Flow
| ID | Requirement | Validation Method |
|----|-------------|-------------------|
| FR1 | 3-step process (Verify → Upload → Submit) | User testing |
| FR2 | Auto-fill known user data | A/B test |
| FR3 | Inline document scanning guidance | QA testing |

### 4.2 Payment Tracking
| ID | Requirement | Priority |
|----|-------------|----------|
| FR4 | Color-coded status badges (Green/Amber/Red) | P0 |
| FR5 | Estimated processing timeline | P1 |
| FR6 | Downloadable payment receipts | P2 |

## 5. Non-Goals
❌ Backend API modifications  
❌ New authentication system  
❌ Offline functionality  
❌ Additional benefit types beyond JHT  

## 6. Design Specifications
### Visual Style
- **Color Palette:**
  - Primary: BPJSTK Blue (#2566B1)
  - Secondary: Accessibility-verified palette
- **Typography:**
  - Headers: Inter Bold (20-24pt)
  - Body: Inter Regular (16pt min)

### Key Screens
1. Claim Dashboard
2. Document Upload Flow
3. Payment Status Tracker
4. Notification Center

## 7. Technical Constraints
- **Platforms:** Android 9+, iOS 13+
- **Limitations:**
  - Max 2MB/image upload
  - Existing API response times (avg. 1.8s)
- **Dependencies:**
  - Member database v2.3+
  - Payment gateway API v1.2

## 8. Success Metrics
| Metric | Baseline | Target |
|--------|----------|--------|
| Claim completion time | 8.5min | ≤6min |
| Support tickets | 320/month | ≤200/month |
| User satisfaction | 62% | ≥85% |

## 9. Open Questions
1. Are there legal requirements for document retention periods? (To answer by Legal Team)
2. Should we add regional language support? (Pending user research)

## 10. Timeline
```mermaid
gantt
    title Project Timeline
    dateFormat  YYYY-MM-DD
    section Phase 1
    Research       :2025-07-21, 7d
    section Phase 2
    UI Design      :2025-07-28, 14d
    section Phase 3
    Prototyping    :2025-08-11, 7d
    section Phase 4
    Documentation  :2025-08-18, 7d
    section Phase 5
    Delivery       :2025-08-25, 7d