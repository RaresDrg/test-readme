<h1 align='center'><b>MoneyGuard</b></h1>
<br>
 
<div align='center'>
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/HTML" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/CSS" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/JS" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/TS" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/REACT" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/REDUX" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/NODE.JS" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/EXPRESS.JS" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/MONGO.DB" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/REST.API" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/SWAGGER" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/POSTMAN" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/FIGMA" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/VITE" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/ESLINT" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/CLOUDINARY" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/RESEND" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/UPTIME.ROBOT" height="35" />
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/f_auto,q_auto/RENDER" height="35" />
</div>
<br>

<h2>Project Links</h2>
<ul>
  <li>
    <a href="https://moneyguard-pc7y.onrender.com">Live App</a>
  </li>
  <li>
    <a href="https://www.figma.com/design/b6yYlOxhk4hUJyrytJUjEs/Money-Guard--International-">Figma Design</a>
  </li>
  <li>
    <a href="https://moneyguard-server.onrender.com/api-docs">API Documentation</a>
  </li>
</ul>

<h2>Description</h2>
<div>
  <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
  <b>MoneyGuard</b>
  <span>
    is a full‑stack application that helps users keep their personal budgeting simple and organized. Its clean and modern interface provides a smooth experience for tracking daily transactions, understanding spending behavior, and staying updated on the current account balance.
  </span>
</div>

<h2>Features</h2>
<ul>
  <li>
    <b>User Authentication</b>
    <span>—</span>
    <span>
      account creation, secure login, and optional Google authentication for quick access.
    </span>
  </li>
  <li>
    <b>Password Recovery</b>
    <span>—</span>
    <span>
       easy password reset through a secure email recovery link.
    </span>
  </li>
  <li>
    <b>Transaction Management</b>
    <span>—</span>
    <span>
      adding, editing, and deleting transactions directly from the dashboard.
    </span>
  </li>
  <li>
    <b>Real‑Time Balance</b>
    <span>—</span>
    <span>
      automatic balance updates after transaction changes.
    </span>
  </li>
  <li>
    <b>Statistical Insights</b>
    <span>—</span>
    <span>
      monthly breakdown of transactions, highlighting expense distribution across categories and overall financial totals.
    </span>
  </li>
  <li>
    <b>Currency Conversion</b>
    <span>—</span>
    <span>
      instant conversion of foreign amounts into USD, using daily‑updated exchange rates.
    </span>
  </li>
</ul>

<h2>Frontend</h2>
<ul>
  <li>
    <b>Technologies</b>
    <span>—</span>
    <span>React, TypeScript, Redux Toolkit, Styled Components</span>
  </li>
  <li>
    <b>Deploy</b>
    <ul>
      <li>
        Render — hosting for the frontend as a static site.
      </li>
      <li>
        API proxy forwards all <code>/api</code> requests to the backend, ensuring same‑origin communication and preventing third‑party cookie issues.
      </li>
      <li>
        SPA rewrite rules redirect all routes to <code>/index.html</code>, supporting client‑side routing.
      </li>
    </ul>
  </li>
  <li>
    <b>Setup</b>
    <ul>
      <li>
         Vite — provides fast project setup and optimized production builds.  
      </li>
      <li>
        TypeScript Config — enforces strict type‑checking and improves project stability.
      </li>
      <li>
        ESLint Config — maintains reliable linting rules and consistent code quality.
      </li>
      <li>
        Prettier — ensures uniform formatting across the entire codebase.
      </li>
    </ul>
  </li>
  <li>
    <b>Architecture</b>
    <ul>
      <li>
        The architecture follows a clean, modular structure with a clear separation of concerns across the application.
      </li>
      <li>
        Core layers are organized using a feature‑based folder approach, keeping related functionality grouped in a predictable and intuitive way.
      </li>
      <li>
        Barrel files centralize exports, ensuring consistent and straightforward access to modules within the project.
      </li>
      <li>
        Global UI elements — modals, loaders, notifications — are mounted through dedicated portal roots to avoid interfering with the main layout, and they operate independently from the route‑level rendering tree.
      </li>
      <li>
        Responsive Context — a global context exposes device type and pixel density, allowing components to adapt layout, assets, and behavior dynamically.
      </li>
    </ul>
  </li>
  <li>
    <b>UX & Accessibility</b>
    <ul>
      <li>
        LQIP Approach — blurred low‑quality previews improve perceived loading speed and provide a smoother visual transition.
      </li>
      <li>
        Loading indicators integrated throughout the interface clarify ongoing processes and keep the experience predictable.
      </li>
      <li>
        Notifications deliver immediate feedback for key user actions, helping maintain clarity and reducing uncertainty.
      </li>
      <li>
        Transitions shape a smoother interaction flow and keep the interface fluid and natural.
      </li>
      <li>
        Animations enhance visual perception and make interactions feel more dynamic and engaging.
      </li>
      <li>
        Semantic roles and live regions are applied across the interface to ensure proper announcements and accessible navigation for assistive technologies.
      </li>
      <li>
        Keyboard navigation is fully supported, with clear focus-visible states that keep interactions predictable and accessible.
      </li>
      <li>
        Modal interactions follow accessible patterns, including controlled focus behavior, consistent dismissal rules, and full isolation from the underlying layout.
      </li>
      <li>
        Form behavior provides a clear and guided submission flow, helping users enter information confidently while the interface manages validation, limits, and action availability.
      </li>
    </ul>
  </li>
  <li>
    <b>UI & Styling</b>
    <ul>
      <li>
        Styling is managed with styled‑components, providing predictable behavior, clean component structure, and scoped styles. 
      </li>
      <li>
        Cross‑browser compatibility is achieved through modern‑normalize, custom reset rules, and manual vendor prefixes for consistent rendering across browsers.
      </li>
      <li>
        Responsive Design — built on a mobile‑first foundation, the interface adapts seamlessly across devices and screen sizes.
      </li>
      <li>
         Responsive Assets — images are served in 1x/2x resolutions and breakpoint‑specific variants for optimal visual quality on all displays.
      </li>
      <li>
        Images are manually optimized with Squoosh, converted to modern WebP formats, and compressed to achieve a balanced quality–size ratio.
      </li>
      <li>
        Videos are processed with HandBrake and re‑encoded using H.264 to ensure reduced file size and reliable cross‑browser playback.
      </li>
      <li>
        Media Delivery — all media assets are delivered through Cloudinary, benefiting from automatic format optimization, smart compression, and CDN‑level performance.
      </li>
      <li>
        Sprite Technique — all vector icons are consolidated into a single SVG sprite to reduce network requests and keep icon management consistent and efficient.
      </li>
    </ul>
  </li>
  <li>
    <b>Routing</b>
    <ul>
      <li>
        The project runs as a Single Page Application, with React Router managing all client‑side navigation.
      </li>
      <li>
        Restricted Routes — pages accessible only when the user is not authenticated, with a redirect guard preventing access once a session is active.
      </li>
      <li>
        Protected Routes — core application pages become available only after authentication, and unauthorized access is automatically redirected to the login flow.
      </li>
      <li>
        Fallback Route — any unmatched path is routed to a dedicated Not Found page, ensuring consistent handling of invalid URLs.
      </li>
    </ul>
  </li>
  <li>
    <b>State Management</b>
    <ul>
      <li>
        Redux — manages the application’s global state in a centralized way.
      </li>
      <li>
        Redux Toolkit — simplifies the Redux setup with slice‑based logic and reduced boilerplate.
      </li>
      <li>
        Redux Persist — persists the application state across sessions and page reloads.
      </li>
    </ul>
  </li>
  <li>
    <b>API Layer</b>
    <ul>   
      <li>
        The API layer operates through an Axios instance that handles all backend requests, configured with a baseURL and credential support for authenticated communication.
      </li>
      <li>
        Request Interceptor — looks for a session token in session storage and, if present, includes it in the Authorization header as a Bearer token.
      </li>
      <li>
        Response Interceptor — stores the session token if the server returns one and triggers an automatic logout when a 401 error occurs.
      </li>
      <li>
        Session Logic — the server issues secure HTTP‑Only cookies to handle authentication and assigns each browser tab a unique session identifier, ensuring a single active session per user and proper isolation across tabs.
      </li>
    </ul>
  </li>
  <li>
    <b>Other Details</b>
    <ul>
      <li>
        Local caching applies user ownership and TTL‑based invalidation to maintain fresh, isolated, and reliable client‑side data.
      </li>
      <li>
        Font and media delivery are optimized through preconnect and DNS-prefetch directives, reducing latency for Google Fonts and Cloudinary assets.
      </li>
    </ul>
  </li>
</ul>

<h2>Backend</h2>
<ul>
  <li>
    <b>Technologies</b>
    <span>—</span>
    <span>Node.js, Express, TypeScript</span>
  </li>
</ul>

<br>
<div align="center">
  <a href="https://moneyguard-pc7y.onrender.com">
    <img 
      height="80" 
      src='https://res.cloudinary.com/db73szjbz/image/upload/v1776817125/test_1_uwmdnz.png'>
  </a>
</div>


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://res.cloudinary.com/db73szjbz/image/upload/moneyguard-logo.png">
  <source media="(prefers-color-scheme: light)" srcset="https://res.cloudinary.com/db73szjbz/image/upload/moneyguard-logo-gradient.png">
  <img src="https://res.cloudinary.com/db73szjbz/image/upload/moneyguard-logo-gradient.png" width="80">
</picture>

