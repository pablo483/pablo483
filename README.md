<div align="center">

  <!-- Animated Hero Banner (non-clickable) -->
  <a id="hero-banner">
    <img src="./assets/hero-banner.svg" width="100%" alt="Sudarshan GC — Software Engineer (Java Backend)" />
  </a>

  <br />

  <!-- Top Prominent Contact, Portfolio & Resume Cards -->
  <p align="center">
    <a href="https://pablo483.github.io/">
      <img src="./assets/card-portfolio.svg" height="44" alt="Live Portfolio: pablo483.github.io" />
    </a>&nbsp;
    <a href="https://pablo483.github.io/Sudarshan_GC_CV.pdf">
      <img src="./assets/card-cv.svg" height="44" alt="Resume / CV: View 1-Page PDF" />
    </a>&nbsp;
    <a href="https://www.linkedin.com/in/sudarshan-gc-8323a5442/">
      <img src="./assets/card-linkedin.svg" height="44" alt="LinkedIn: Sudarshan GC" />
    </a>&nbsp;
    <a href="mailto:sudarshangc580@gmail.com">
      <img src="./assets/card-email.svg" height="44" alt="Email: sudarshangc580@gmail.com" />
    </a>&nbsp;
    <a href="https://github.com/pablo483?tab=repositories">
      <img src="./assets/card-github.svg" height="44" alt="GitHub: @pablo483" />
    </a>
  </p>

  <a id="divider-top"><img src="./assets/divider.svg" width="100%" alt="" /></a>

  <!-- Structured Tech Stack Bento Grid (non-clickable) -->
  <h3>Tech Stack</h3>

  <p align="center">
    <a id="tech-stack">
      <img src="./assets/tech-stack.svg" width="100%" alt="Tech Stack: Backend & Security, Databases & Persistence, Caching & Event Streaming, Cloud, DevOps & Testing" />
    </a>
  </p>

  <a id="divider-experience"><img src="./assets/divider.svg" width="100%" alt="" /></a>

  <!-- Professional Experience -->
  <h3>Experience</h3>

</div>

### CAS Total Services
**Dec 2025 – Present** · *Kathmandu, Nepal*  
*(Joined as Intern &rarr; Retained &amp; Promoted to Software Engineer)*

#### Software Engineer
**Jun 2026 – Present**

Continued full-time at CAS Total Services after completing the internship. Built Trade Finance banking forms and workflows on Newgen iBPS for commercial banking. Key work:

- **Trade Finance lifecycle** — built digital forms for Letters of Credit (LC issuance, amendments, cancellation, closure) and bills processing (lodgement, acceptance, realization)
- **Form logic in Java & JS** — wrote field validations and conditional show/hide rules driven by LC types (Export LC vs. CAD), payment terms, and workflow stages
- **Dynamic banking calculations** — automated calculations for tolerances, maximum credit amounts, dynamic charges (flat vs. percentage), and FX currency conversions
- **Maker-checker workflows** — developed approval routing across banking desks (Maker to RM to SWIFT) with decision logging and audit trails
- **SWIFT MT700 mapping** — mapped form fields to SWIFT message standards to enable automated, compliant message generation
- **T24 Core Banking API integration** — connected forms with Temenos T24 REST APIs, debugging JSON payload mapping and resolving strict field lockouts

#### Software Engineering Intern
**Dec 2025 – May 2026**

Started as intern at CAS Total Services, building Loan Origination System (LOS) forms and credit appraisal workflows for SME lending on the Newgen iBPS platform. Key work:

- **SME loan origination screens** — built application and appraisal forms to capture borrower financials, collateral details, and credit scoring
- **Validation logic** — wrote Java and JavaScript rules to verify eligibility thresholds and enforce mandatory documentation checks
- **Approval workflows** — configured multi-level maker-checker routing across Loan Officers, Risk Managers, and Credit Committees
- **Audit tracking & documents** — implemented document checklist verifications, decision audit trails, and automated sanction letter generation

<div align="center">

  <a id="divider-projects"><img src="./assets/divider.svg" width="100%" alt="" /></a>

  <!-- Featured Projects Bento Table -->
  <h3>Featured Projects</h3>

</div>

<table>
  <tr>
    <td colspan="2">
      <h4>
        <a href="https://github.com/pablo483/Inventory-SAAS">Multi-Tenant Inventory Management SaaS</a>
        &nbsp;<code>Flagship Architecture</code>
      </h4>
      <p>
        Production-style multi-tenant SaaS isolating organizations, stock transactions, reconciliation reports, and subscription plans.
        Features custom <code>TenantInterceptor</code> context isolation, <b>Flyway</b> migrations, <b>Redis</b> caching + Pub/Sub + sorted-set leaderboards,
        <b>Bucket4j</b> token-bucket rate limiting, <b>Prometheus</b> metrics, <b>k6</b> load scripts, and a 3-replica <b>Nginx + Docker Compose</b> stack paired with a React/TypeScript UI.
      </p>
      <p>
        <code>Java 17</code> <code>Spring Boot 3.5</code> <code>MySQL</code> <code>Flyway</code> <code>Redis</code> <code>Bucket4j</code> <code>Docker &amp; Nginx</code> <code>Prometheus &amp; k6</code> <code>React / TS</code>
        &nbsp;—&nbsp; <a href="https://github.com/pablo483/Inventory-SAAS"><b>View Repo →</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/pablo483/Ecommerce_Cloud">Ecommerce_Cloud</a></h4>
      <p>
        Multi-vendor e-commerce REST API supporting <code>ADMIN</code>, <code>VENDOR</code>, and <code>USER</code> roles with <b>Cloudinary</b> multipart image uploads,
        paginated filtering/search, admin approval workflows, <b>Redis</b> caching, and daily <code>@Scheduled</code> low-stock vendor email alerts.
      </p>
      <p>
        <code>Java 17</code> <code>Spring Boot 3.4</code> <code>MongoDB</code> <code>JWT</code> <code>Redis</code> <code>Cloudinary</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/pablo483/external-api-integration">external-api-integration</a></h4>
      <p>
        Event-driven third-party API gateway (Weather &amp; Currency) using reactive <code>WebClient</code>, <b>Redis</b> TTL read-through caching,
        and isolated asynchronous <b>Apache Kafka</b> audit event producer/consumer streams with manual offset commits.
      </p>
      <p>
        <code>Java 17</code> <code>Spring Boot 3.5</code> <code>WebClient</code> <code>Kafka</code> <code>Redis</code> <code>Docker</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/pablo483/online-quiz-backend">online-quiz-backend</a></h4>
      <p>
        Online quiz &amp; automatic grading API (<a href="https://github.com/pablo483/Online-Quiz-Frontend">Frontend Repo</a>) with hierarchical categories,
        JWT + UUID refresh tokens, and <code>UserAttemptLog</code> tracking that prevents duplicate wrong-option guesses.
      </p>
      <p>
        <code>Spring Boot 3.5</code> <code>MySQL</code> <code>JPA</code> <code>JWT</code> <code>React 19</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/pablo483/UserOnboarding-API-Cookie">UserOnboarding-API-Cookie</a></h4>
      <p>
        Security-focused onboarding service featuring email verification links, BCrypt hashing,
        <code>HttpOnly</code> <code>SameSite=Lax</code> cookie JWTs, and database-backed refresh token rotation to prevent replay attacks.
      </p>
      <p>
        <code>Java</code> <code>Spring Boot</code> <code>MySQL</code> <code>Spring Security</code> <code>JWT Cookies</code>
      </p>
    </td>
  </tr>
</table>