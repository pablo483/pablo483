<div align="center">

  <!-- Animated Hero Banner -->
  <a href="https://pablo483.github.io/">
    <img src="./assets/hero-banner.svg" width="100%" alt="Sudarshan GC — Software Engineer (Java Backend)" />
  </a>

  <br />

  <!-- Top Prominent Contact & Portfolio Cards -->
  <p align="center">
    <a href="https://pablo483.github.io/">
      <img src="./assets/card-portfolio.svg" height="48" alt="Live Portfolio: pablo483.github.io" />
    </a>&nbsp;
    <a href="https://www.linkedin.com/in/sudarshan-g-c-8323a5442/">
      <img src="./assets/card-linkedin.svg" height="48" alt="LinkedIn: Sudarshan GC" />
    </a>&nbsp;
    <a href="mailto:sudarshangc580@gmail.com">
      <img src="./assets/card-email.svg" height="48" alt="Email: sudarshangc580@gmail.com" />
    </a>&nbsp;
    <a href="https://github.com/pablo483?tab=repositories">
      <img src="./assets/card-github.svg" height="48" alt="GitHub: @pablo483" />
    </a>
  </p>

  <img src="./assets/divider.svg" width="100%" alt="" />

  <!-- Structured Tech Stack Bento Grid -->
  <h3>Tech Stack</h3>

  <p align="center">
    <img src="./assets/tech-stack.svg" width="100%" alt="Tech Stack: Backend & Security, Databases & Persistence, Caching & Event Streaming, Cloud, DevOps & Testing" />
  </p>

  <img src="./assets/divider.svg" width="100%" alt="" />

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
