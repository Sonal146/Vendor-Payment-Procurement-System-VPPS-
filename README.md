# Vendor Payment & Procurement System (VPPS) — Anonymized Version 

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/33c6d869-143b-42f6-92c2-98699adf81ad" />


>  

  # Vendor Payment & Procurement System (VPPS) - Real-World Business Analysis Project

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Business Analysis](https://img.shields.io/badge/Domain-Business%20Analysis-blue.svg)](https://github.com)
[![Real Project](https://img.shields.io/badge/Project-Real%20World-green.svg)](https://github.com)
[![Documentation](https://img.shields.io/badge/Documentation-Complete-brightgreen.svg)](https://github.com)

> **IMPORTANT DISCLOSURE:** This repository contains documentation from a **real-world business analysis project** that was successfully implemented in a production environment. Due to contractual obligations and confidentiality agreements, all sensitive data including company names, personal information, financial figures, vendor details, and proprietary system information has been anonymized, altered, or replaced with representative placeholders while maintaining the authentic structure and methodology of the original project.

## The Brief

 Cre8iveSkill’s procurement and vendor-payment workflow was a major operational constraint that directly affected cash flow, vendor trust, and production continuity. The finance team was spending roughly 120 hours per month on invoice processing — manually matching invoices to purchase orders, routing approvals via email, and executing payments — which created delays and missed opportunities for early-payment discounts. I led the design and delivery of the Vendor Payment & Procurement System (VPPS) to integrate procurement with production, automate invoice processing, introduce demand-driven PO generation, and surface real-time cashflow visibility for management. My role spanned the full BA lifecycle: stakeholder interviews across finance, procurement, production and vendors; as-is process mapping to quantify delays and rework; authoring a BRD with explicit acceptance criteria and business rules; and translating requirements into prioritized user stories for development sprints. The solution architecture combined electronic invoice submission, automatic PO matching, intelligent approval workflows, duplicate-invoice detection, reconciliation reports and bank transfer automation — all designed to reduce manual effort, improve vendor predictability, and enable data-driven procurement decisions.

## The Challenge

The problem was multi-dimensional and immediate. Operationally, invoices routinely sat in inboxes for 5–7 days before being processed; duplicate invoices and inconsistent approval routing created rework and payment errors. Vendors complained about unpredictable payment timing, often waiting 30–60 days despite agreed terms, which strained supplier relationships and reduced negotiation leverage. Financial leadership lacked reliable cashflow visibility and could not confidently answer questions about monthly vendor obligations or forecast short-term payables. Procurement operated largely disconnected from production demand: when orders increased, procurement did not adjust automatically, causing missed volume discounts and supply-chain vulnerability. I quantified the impact: finance burned substantial monthly hours on low-value processing, early-payment discounts were being lost (estimated at $XX,XXX annually — placeholder), and vendor on-time payment hovered around 65%. The mandate was clear: build an auditable, integrated system to shorten invoice cycle time, capture discounts, improve vendor payment reliability, and provide management with accurate payables forecasting — while preserving operational continuity and winning vendor buy-in.

## Our Approach (Process, Analysis & Design)

I approached VPPS with a diagnostics-first methodology that combined gap analysis, market analysis and a stakeholder-driven SWOT to ensure we solved root causes and delivered rapid value. First, I ran a gap analysis comparing current procurement and AP capability against a target operating model: timed walkthroughs, BPMN process maps and a capability matrix revealed concrete governance, data and control shortfalls. Next, I performed a market analysis and competitor scan to see how supplier portals, DMS integrations and early-pay platforms structure submission, matching and discount flows; those insights guided feature prioritization and UX choices. I then facilitated a SWOT workshop with finance, procurement and production stakeholders to surface strengths we could leverage, weaknesses to mitigate, opportunities (capture early discounts, negotiate volume rates) and threats (supplier churn). Using this evidence I authored a quantified business case, prioritized a backlog for iterative delivery, co-designed validation rules for invoice matching, and specified an architecture emphasizing observability: invoice ingestion → PO-matching engine → approval workflows → cashflow dashboards → automated payment execution. Traceability matrices ensured each requirement mapped to a test and UI element, preserving fidelity through development.

## The Value and Outcome I Delivered

The VPPS rollout delivered measurable operational and financial improvements that fundamentally changed procurement behaviour. Invoice processing time decreased by 78%, dramatically reducing manual reconciliation and freeing finance to focus on analysis rather than data entry. Vendor on-time payment improved from 65% to 94%, which stabilized supplier relationships and improved supply predictability. We captured early-payment discounts that had previously slipped through the process (placeholder $XX,XXX — replace with actual), and integrating procurement with production demand enabled better negotiation that achieved an approximate 12% volume discount with key suppliers. Real-time cashflow dashboards provided management with short-term forecasting and payables visibility, while reconciliation reports and audit trails simplified dispute resolution and compliance. Beyond these headline metrics, VPPS converted procurement from a reactive admin activity into a measured, strategic capability: improved forecasting accuracy, stronger vendor confidence, direct cost savings, and a repeatable operating model for future automation initiatives.


##  Project Background

This repository showcases the complete business analysis lifecycle for the **Vendor Payment & Procurement System (VPPS)**, a comprehensive back-end automation initiative that was designed and implemented to centralize procurement processes, vendor onboarding, 3-way matching (PO/GRN/Invoice), payment scheduling, and optimized payment-run generation.

### Real-World Context
- **Project Type:** Enterprise-level process automation and digital transformation
- **Industry:** Creative services (embroidery digitizing, vector graphics, custom patches)
- **Project Duration:** 7 months (December 2024 - September 2025)
- **Project Investment:** $##0,000 implementation budget
- **Business Impact:** 43% payment cycle reduction, 95% automation rate, $##0,000 annual savings

### Data Confidentiality Statement
In compliance with professional ethics and contractual obligations:
-  **Real methodology and processes** are accurately represented
-  **Authentic project structure** and documentation standards maintained
- **Genuine business analysis techniques** and deliverables showcased
- **Company names, personal data, and financial specifics** have been anonymized
- **Proprietary system details and vendor information** have been altered
-  **Sensitive business relationships and contracts** have been redacted

##  Project Overview

### Business Challenge
The organization faced significant operational inefficiencies in their manual procurement and payment processes:
- Manual 3-way matching requiring 4-6 hours daily
- Extended payment cycles averaging 30 days
- Data silos across procurement, operations, and finance
- Limited vendor visibility into order status and payments
- High error rates in reconciliation processes

### Solution Approach
**VPPS** was designed as a cloud-native, microservices-based system to automate the complete procurement-to-payment lifecycle:
- **Centralized vendor management** with digital onboarding
- **Intelligent 3-way matching** with ML-powered automation
- **Optimized payment processing** with early discount capture
- **Self-service vendor portal** for real-time visibility
- **Comprehensive audit trails** for compliance

### Achieved Business Outcomes
- **Payment Cycle Reduction:** 30 → 17 days (43% improvement)
- **Automation Rate:** 95% of payment runs processed automatically
- **Error Reduction:** 50%+ decrease in manual reconciliation errors
- **Cost Savings:** $##0,000 annual operational improvements
- **ROI Achievement:** 3-year NPV of $##3,000 with 2.5-year payback

##  Repository Structure

```
VPPS-Business-Analysis/
├──  README.md                           # This comprehensive project guide
├──  LICENSE                             # MIT License with confidentiality notice
│
├──  01-Core-Documents/
│   ├──  Project_Charter.pdf             # Executive project definition
│   ├──  BRD_VPPS_Complete.pdf           # Business Requirements (PDF)
│   ├──  BRD_VPPS_Detailed.md            # Business Requirements (Markdown)
│   ├──  FRD_VPPS_Complete.pdf           # Functional Requirements (PDF)
│   ├──  FRD_VPPS_Complete.md            # Functional Requirements (Markdown)
│   ├──  SDD_VPPS_Complete.pdf           # System Design (PDF)
│   ├──  SDD_VPPS_Architecture.md        # System Design (Markdown)
│   ├──  TPD_VPPS_Complete.pdf           # Test Plan (PDF)
│   ├──  TPD_VPPS_TestPlan.md            # Test Plan (Markdown)
│   ├──  PIG_VPPS_Complete.pdf           # Implementation Guide (PDF)
│   └──  PIG_VPPS_Implementation.md      # Implementation Guide (Markdown)
│
├──  02-Technical-Specifications/
│   ├──  MySQL_DDL_VPPS_v1.sql          # Complete database schema
│   ├──  JIRA_UserStories_VPPS.csv       # 27 development-ready user stories
│   ├──  UAT_TestCases_VPPS.xlsx         # 20 comprehensive test scenarios
│   ├──  AS-IS_VPPS_Process.xml          # Current state BPMN workflow
│   ├──  TO-BE_VPPS_Process.xml          # Future state BPMN workflow
│   └──  BI_Specification.md             # Business intelligence requirements
│
├──  03-Visual-Assets/
│   ├──  AS-IS_VPPS.png                  # Current manual process diagram
│   ├──  TO-BE_VPPS.png                  # Automated process flow diagram
│   ├──  ERD_VPPS.png                    # Database entity relationship diagram
│   ├── Portal_Wireframe.png            # Supplier portal interface mockup
│   ├──  PaymentRun_UI.png               # Payment processing UI wireframe
│   └──  BI_Dashboard.png                # Business intelligence dashboard mockup
│
└──  04-Documentation/
    ├──  Project_Methodology.md          # BA methodology and approach used
    ├──  Metrics_and_KPIs.md             # Success metrics and measurement
    ├──  Lessons_Learned.md              # Project insights and recommendations
    └── Glossary.md                     # Technical terms and definitions
```

##  Business Analysis Methodology

### Requirements Engineering Approach
This project demonstrates expertise in comprehensive requirements management:

**1. Stakeholder Analysis & Engagement**
- Identified 15+ key stakeholders across finance, procurement, operations
- Conducted structured interviews and workshops for requirement elicitation
- Implemented continuous stakeholder feedback loops throughout project lifecycle

**2. Requirements Documentation & Traceability**
- **Business Requirements Document (BRD):** High-level business needs and objectives
- **Functional Requirements Document (FRD):** Detailed feature specifications and acceptance criteria
- **Complete traceability matrix:** BRD → FRD → User Stories → Test Cases → Implementation

**3. Process Analysis & Optimization**
- **Current State Analysis:** Comprehensive AS-IS process mapping using BPMN 2.0
- **Future State Design:** TO-BE process optimization with automation opportunities
- **Gap Analysis:** Quantified improvement opportunities and business impact assessment

### Technical Business Analysis
**1. System Architecture & Design**
- **Microservices Architecture:** Cloud-native design with independent service scaling
- **API-First Approach:** RESTful service contracts with comprehensive error handling
- **Security Framework:** RBAC, encryption, audit trails, and compliance considerations

**2. Data Architecture & Management**
- **Database Design:** Normalized MySQL schema with 16+ tables, procedures, and triggers
- **Data Integration:** ERP synchronization, banking file formats, marketplace APIs
- **Performance Optimization:** Indexing strategies, partitioning, and caching design

**3. Quality Assurance Strategy**
- **Comprehensive Test Planning:** 390+ test cases covering functional, performance, and security
- **Risk-Based Testing:** Prioritized testing approach focusing on high-impact scenarios
- **User Acceptance Testing:** Business-driven validation with clear acceptance criteria

##  Professional Capabilities Demonstrated

### Core Business Analysis Skills
-  **Requirements Elicitation & Documentation:** Comprehensive stakeholder engagement and structured requirement capture
-  **Process Mapping & Optimization:** BPMN 2.0 modeling with quantified improvement analysis
-  **Stakeholder Management:** Multi-level engagement strategy from executives to end users
-  **Gap Analysis & Solution Design:** Current state assessment with future state planning
-  **Business Case Development:** ROI analysis, cost-benefit evaluation, risk assessment
-  **User Story Writing:** Agile-ready development stories with comprehensive acceptance criteria

### Technical Analysis Skills
-  **System Architecture Analysis:** Microservices design, cloud-native architecture planning
-  **Database Design & Modeling:** Normalized schema design with performance optimization
-  **API Specification:** RESTful service contracts with comprehensive documentation
-  **Integration Planning:** ERP, banking, and third-party system integration design
-  **Security Requirements:** RBAC design, data protection, compliance framework
-  **Performance Analysis:** Scalability planning, capacity requirements, load testing strategy

### Project Management & Implementation
-  **Project Planning:** Phase-wise implementation roadmap with timeline and milestones
-  **Risk Management:** Comprehensive risk identification, assessment, and mitigation planning
-  **Change Management:** User adoption strategy, training programs, resistance management
-  **Quality Assurance:** Testing strategy, defect management, quality metrics framework
-  **Benefits Realization:** Success metrics tracking, ROI measurement, continuous improvement

### Industry Knowledge & Domain Expertise
-  **Procurement & Supply Chain:** End-to-end procurement process optimization
-  **Financial Systems:** Payment processing, cash flow management, financial controls
-  **ERP Integration:** Enterprise system connectivity and data synchronization
-  **Vendor Management:** Supplier relationship management, performance tracking
-  **Compliance & Audit:** Financial regulations, audit trail requirements, SOX compliance

##  Technical Architecture Highlights

### System Design Principles
- **Cloud-Native Architecture:** Kubernetes orchestration with auto-scaling capabilities
- **Microservices Pattern:** Independent services for vendor management, PO processing, matching, payments
- **Event-Driven Architecture:** Asynchronous processing with RabbitMQ message queues
- **API-First Design:** Comprehensive REST APIs with OAuth 2.0 security

### Technology Stack
- **Backend:** Java 17, Spring Boot 3.x, MySQL 8.0, Redis, RabbitMQ
- **Frontend:** React 18, Redux Toolkit, Material-UI, responsive design
- **Infrastructure:** Docker, Kubernetes, AWS/Azure cloud services
- **Integration:** SFTP, ISO 20022 banking standards, ERP REST APIs
- **Monitoring:** Prometheus, Grafana, ELK stack for comprehensive observability

### Database Design Excellence
- **16+ normalized tables** with proper relationships and constraints
- **Stored procedures and functions** for business logic encapsulation
- **Comprehensive indexing strategy** for query performance optimization
- **Audit trail implementation** with complete transaction history
- **Data partitioning strategy** for scalability and maintenance

##  Business Impact & Success Metrics

### Quantified Business Outcomes
- **43% Payment Cycle Reduction:** From 30 days to 17 days average processing time
- **95% Automation Achievement:** Automated processing rate for standard payment runs
- **50% Error Reduction:** Decrease in manual reconciliation errors and exceptions
- **$180,000 Annual Savings:** Operational cost reduction through process efficiency
- **3-Year NPV: $285,000** with 2.5-year payback period

### Operational Excellence Metrics
- **Response Time:** <3 seconds for 95% of web portal requests
- **System Availability:** 99.5% uptime during business hours
- **User Adoption:** 80% active user adoption within 6 months
- **Processing Capacity:** 500+ payments per run, 1,000+ invoices per day
- **Integration Success:** Real-time ERP sync, daily banking file transmission

### Process Improvement Results
- **Manual Effort Reduction:** 2.5 FTE equivalent time savings
- **Vendor Satisfaction:** Enhanced portal experience and real-time visibility
- **Financial Controls:** Comprehensive audit trails and compliance reporting
- **Scalability Achievement:** 10x growth capacity without proportional cost increase
- **Innovation Platform:** Foundation for future digital transformation initiatives

##  Implementation Approach

### Phased Delivery Strategy
**Phase 1: Foundation (Months 1-2)**
- Infrastructure setup, security framework, vendor management module

**Phase 2: Core Processes (Months 3-4)**
- Purchase order management, GRN processing, basic invoice handling

**Phase 3: Advanced Automation (Months 5-6)**
- 3-way matching automation, payment processing, supplier portal

**Phase 4: Go-Live & Optimization (Month 7)**
- Production deployment, hypercare support, performance tuning

### Risk Management & Mitigation
- **Technical Risks:** Early POC development, dedicated integration specialists
- **Adoption Risks:** Comprehensive change management and user training programs
- **Integration Risks:** Parallel testing environments and fallback procedures
- **Timeline Risks:** Agile methodology with regular milestone tracking

##  Key Performance Indicators (KPIs)

### Financial KPIs
- **Payment Cycle Time:** Target ≤17 days (achieved 43% reduction)
- **Early Payment Discount Capture:** Target ≥80% utilization
- **Cost per Transaction:** Target 50% reduction
- **Working Capital Improvement:** $###,000 cash flow optimization

### Operational KPIs
- **3-Way Match Automation Rate:** Target ≥95% (achieved)
- **Exception Resolution Time:** Target ≤2 days average
- **System Response Time:** Target <3 seconds (95th percentile)
- **User Adoption Rate:** Target ≥80% within 6 months

### Quality KPIs
- **Processing Error Rate:** Target 50% reduction (achieved)
- **Invoice Accuracy Rate:** Target ≥95% automated validation
- **Vendor Portal Adoption:** Target ≥80% active usage
- **Audit Compliance:** Target 100% audit trail completeness

##  Learning Outcomes & Best Practices

### Business Analysis Best Practices Applied
1. **Early Stakeholder Engagement:** Continuous involvement throughout project lifecycle
2. **Iterative Requirements Refinement:** Agile approach with regular feedback cycles
3. **Comprehensive Documentation:** Full traceability from business needs to implementation
4. **Risk-Based Approach:** Focus on high-impact, high-probability risk mitigation
5. **User-Centric Design:** Emphasis on user experience and adoption strategy

### Technical Implementation Excellence
1. **Security-First Architecture:** Comprehensive security controls at all layers
2. **Performance-Oriented Design:** Scalable architecture with monitoring and optimization
3. **Integration-Ready Framework:** API-first approach with standardized interfaces
4. **Quality-Embedded Process:** Comprehensive testing strategy with automation
5. **Maintainable Codebase:** Clean architecture with proper documentation

### Project Management Insights
1. **Phased Implementation:** Risk mitigation through incremental delivery
2. **Change Management:** Proactive user adoption and training strategy
3. **Benefits Realization:** Clear metrics and continuous monitoring
4. **Vendor Management:** Strategic partnership approach with banking and ERP providers
5. **Continuous Improvement:** Post-implementation optimization and enhancement

##  Documentation Standards

### Professional Documentation Approach
- **Industry Standards:** Following established BA methodologies and frameworks
- **Comprehensive Coverage:** Complete project lifecycle documentation
- **Implementation-Ready:** All specifications ready for development team use
- **Quality Assurance:** Peer-reviewed documents with stakeholder approval
- **Version Control:** Proper document management and change tracking

### Document Quality Metrics
- **Requirements Coverage:** 100% functional requirement documentation
- **Traceability:** Complete mapping from business needs to test cases
- **Acceptance Criteria:** Clear, measurable success criteria for all features
- **Technical Specifications:** Detailed API contracts and database design
- **Testing Coverage:** 390+ test cases across functional, performance, and security domains

##  Confidentiality & Compliance

### Professional Ethics Compliance
This project documentation has been prepared in strict accordance with professional business analysis ethics and confidentiality requirements:

** What IS Included (Authentic):**
- Real business analysis methodology and techniques
- Authentic project structure and documentation standards
- Genuine problem-solving approaches and solution design
- Actual implementation strategies and risk management
- True business impact assessment and benefits realization

** What IS NOT Included (Anonymized/Altered):**
- Real company names, brands, or identifying information
- Actual personal names, contact information, or employee details
- Genuine financial figures, budgets, or sensitive business metrics
- Proprietary system names, vendor relationships, or contracts
- Specific business processes that could reveal company identity

### Data Protection Measures
- **Complete Anonymization:** All sensitive identifiers replaced with generic placeholders
- **Data Transformation:** Financial figures scaled and randomized while maintaining realistic proportions
- **Process Generalization:** Business processes described in generic industry terms
- **System Abstraction:** Technical implementations described without proprietary details
- **Relationship Masking:** Business partnerships and vendor relationships anonymized

##  Portfolio Value & Professional Recognition

### Career Development Impact
This real-world project demonstrates:
- **Enterprise-Level Experience:** Large-scale digital transformation leadership
- **Cross-Functional Collaboration:** Successful stakeholder management across departments
- **Technical Business Analysis:** Bridge between business needs and technical implementation
- **Measurable Business Impact:** Quantified ROI and operational improvement delivery
- **Industry Best Practices:** Application of established BA methodologies and frameworks

### Professional Competencies Validated
- **Strategic Thinking:** Business case development and solution architecture
- **Analytical Skills:** Process analysis, gap identification, and optimization design
- **Communication Excellence:** Stakeholder engagement and requirements documentation
- **Technical Proficiency:** System design, database architecture, and API specification
- **Project Leadership:** Implementation planning, risk management, and change leadership

### Industry Recognition Potential
- **Methodology Excellence:** Demonstration of professional BA standards and practices
- **Innovation Application:** Creative use of technology for business process improvement
- **Results Achievement:** Proven track record of delivering measurable business value
- **Professional Growth:** Evidence of senior-level business analysis capabilities
- **Knowledge Sharing:** Contribution to BA community through methodology documentation

##  Professional Contact & Collaboration

**Lead Business Analyst:** Sonal M. Khobragade  
**Location:** Nagpur, Maharashtra, India  
**Specialization:** Business Process Analysis & Digital Transformation  

### Professional Expertise Areas
- **Requirements Engineering & Management**
- **Process Optimization & Automation**
- **System Integration & Architecture Analysis**
- **Data Analytics & Business Intelligence**
- **Project Implementation & Change Management**
- **Stakeholder Engagement & Communication**

### Collaboration Opportunities
- **Consulting Engagements:** Business analysis and process improvement projects
- **Training & Mentoring:** BA methodology and best practices sharing
- **Peer Collaboration:** Joint projects and knowledge exchange initiatives
- **Industry Participation:** Conference presentations and professional community involvement
- **Open Source Contribution:** Methodology frameworks and template sharing

##  Usage & Attribution Guidelines

### Educational & Professional Use
This repository is designed for:
- **Portfolio Demonstration:** Showcasing business analysis capabilities
- **Learning Resource:** Understanding real-world BA project structure
- **Template Reference:** Methodology and documentation standards
- **Professional Development:** Best practices and techniques illustration
- **Academic Research:** Case study for business analysis education

### Attribution Requirements
When using this work for reference or inspiration:
-  **Credit Original Author:** Acknowledge Sonal M. Khobragade as the lead business analyst
-  **Reference Source:** Link back to original repository for full context
-  **Respect Confidentiality:** Maintain anonymized status of all data and identifiers
-  **Professional Ethics:** Use responsibly for educational and professional development purposes
-  **Quality Standards:** Maintain documentation quality and professional presentation

### Prohibited Uses
-  **Commercial Exploitation:** Direct commercial use without permission
-  **Data Speculation:** Attempting to reverse-engineer original company information
-  **Misrepresentation:** Claiming work as your own or misattributing authorship
-  **Confidentiality Breach:** Attempting to identify real entities or relationships
-  **Professional Misconduct:** Using for purposes that violate professional ethics

##  Project Statistics

### Documentation Metrics
- **Total Files:** 29 comprehensive business analysis documents
- **PDF Documents:** 5 professional presentation-ready files (2.35 MB)
- **Technical Specifications:** 5 implementation-ready documents
- **Visual Assets:** 6 professional diagrams and mockups
- **Code Artifacts:** 1,200+ lines of SQL DDL, 27 user stories, 390+ test cases

### Project Scope Metrics
- **Timeline:** 7-month implementation (28 weeks)
- **Budget:** $###,000 total project investment
- **Team Size:** 12+ core team members across multiple disciplines
- **Stakeholders:** 15+ engaged stakeholders from executive to operational levels
- **Business Impact:** $###,000 annual savings with $###,000 3-year NPV

### Documentation Coverage
- **Business Requirements:** 100% functional requirement documentation
- **Technical Specifications:** Complete system architecture and database design
- **Process Documentation:** BPMN 2.0 current state and future state workflows
- **Testing Strategy:** 390+ test cases across all testing categories
- **Implementation Planning:** Comprehensive phased rollout with risk mitigation

##  Conclusion

This repository represents a complete, real-world business analysis project that successfully delivered significant business value through digital transformation. While all sensitive and proprietary information has been carefully anonymized to respect confidentiality agreements, the authentic methodology, professional documentation standards, and proven results showcase the highest levels of business analysis excellence.

The project demonstrates not just theoretical knowledge, but practical application of business analysis skills in a complex, enterprise-level implementation that achieved measurable business outcomes and established a foundation for continued organizational growth and innovation.

**Ready to explore the world of professional business analysis?** Start with the `01-Core-Documents/` folder to understand the complete project lifecycle, then dive into the technical specifications and visual assets to see how business requirements translate into implementation-ready solutions.

---

## License & Legal Notice

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

**Professional Confidentiality Notice:** This repository contains documentation derived from a real business project with all sensitive, proprietary, and personally identifiable information properly anonymized in compliance with professional ethics and contractual obligations. The methodology, structure, and outcomes represent authentic professional business analysis work while maintaining complete data privacy and confidentiality.


##  Professional Contact

**Sonal M. Khobragade**  
Business Analyst | Data Analytics Professional  
ksonal055@gmail.com 
 www.linkedin.com/in/sonal-mk 
 
 Nagpur, Maharashtra, India



