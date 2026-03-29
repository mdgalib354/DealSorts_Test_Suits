# DealSorts: Comprehensive QA Test Suite (300+ Test Cases)

## Project Overview
**DealSorts** is a high-performance **social-commerce platform** designed to bridge the gap between local businesses and value-seeking customers. 

The platform functions as a real-time "deal hub" where businesses post time-sensitive offers and "Stories," while customers use a personalized discovery engine to follow brands, save discounts, and communicate with merchants via a secure internal messaging system.

-----------

## Testing Objectives
As the QA Engineer for this project, I developed a master testing architecture to ensure platform stability, data integrity, and a seamless mobile experience. My strategy focused on:

* Role-Based Access Control (RBAC): Ensuring strict data siloing between Customer, Business, and Admin roles.
* Security Gating: Implementing and verifying a proprietary URL filtering system within the Messaging module to prevent phishing and platform poaching.
* Mobile-First UX: Validating touch targets, gesture navigation (swipes), and network resilience for "on-the-go" users.
* Real-Time Sync: Testing WebSocket-driven notifications and live badge updates.

-----------

## Repository Structure

| File/Folder | Description |

DealSorts Full Test Suite.xlsx | DealSorts Sanity Test Suite Strategy.xlsx

The full source of truth. A multi-tab spreadsheet containing 300+ detailed test cases across all 9 modules. |
Markdown versions of high-priority test cases (Auth, Messaging, Mobile UX) for instant browser viewing. |
A 20-point "Pulse Check" is used to verify daily deployment. |
Standardized reporting format used to communicate defects to the development team. |

-----------

## Modules Tested
1.  Authentication & Identity: Social logins, session fixation, and password recovery.
2.  Feed & Discovery: 3-column grid stability, lazy loading, and "Story" modal logic.
3.  Interaction & Engagement: Gated social actions (Likes/Comments/Ratings).
4.  Navigation & Global UI: Sticky headers, search accuracy, and profile dropdowns.
5.  Sidebar Utility: Complex filtering logic and sorting persistence.
6.  Messaging & Notifications: URL regex filtering, real-time delivery, and blocking logic.
7.  Profile Functionality: CRUD operations for offers and business tier management.
8.  Static & Business Pages: Pricing table logic and Help Center form validation.
9.  Mobile-Specific UX: Haptic feedback, keyboard overlays, and orientation changes.

-----------

## Methodology & Tools
* Test Design: Risk-Based Testing (RBT), Black-Box Testing, Boundary Value Analysis.
* Testing Types: Functional, Regression, Smoke, UI/UX, Security, and Compatibility.
* Documentation: Microsoft Excel, GitHub Markdown.
* Process: Agile/Scrum environment simulation.

-----------

## Contact
Asadullah Al-Galib  - QA Engineer  
www.linkedin.com/in/mdgalibhossain4  
mdgalibhossain4@gmail.com
