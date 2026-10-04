# Portfolio Website Build Prompt — Nithish Kumar

> Fill in the [bracketed] items before pasting into your AI builder (v0, Lovable, Bolt, Cursor, Claude, etc.).

---

ROLE
You are a senior front-end engineer and product designer. Build a production-ready, highly interactive personal portfolio website for Nithish Kumar. It must not look like a template. It should look like an engineer built it to show how he builds systems.

STACK
Next.js (App Router), TypeScript, Tailwind CSS, Framer Motion, Lucide React. Use Three.js / React Three Fiber only for the hero visual, loaded with dynamic import. Responsive, accessible (WCAG AA, keyboard navigation, focus states, reduced-motion support), SEO-ready, Lighthouse 90+.

REFERENCE STYLE (match the feel of the reference video)
- Layout and motion: [describe: e.g. large hero type, scroll-driven transitions, cursor effects, marquee, bento grid]
- Typography: [e.g. grotesk display font + mono for labels]
- Overall mood: [e.g. minimal, high-contrast, lots of whitespace]
Take the interaction quality and polish from the reference, but apply it to the dark cloud-native theme below.
Reference video: https://cdn.dribbble.com/userupload/46427696/file/cffee89fe064aafdc89a239e3484a6cd.mp4

VISUAL SYSTEM
Dark futuristic cloud/DevOps/AI aesthetic: subtle glassmorphism, faint architecture-diagram grid background, restrained particles, GPU-friendly animations only.
Colors: bg #05070D, primary #00D9FF, secondary #6366F1, accent #8B5CF6, success #22C55E, text #F8FAFC, muted #94A3B8.
Gradients: cyan→blue, blue→violet, violet→pink.

CONTENT RULES (strict)
- Never invent companies, job titles, dates, certifications, metrics, GitHub stats, awards or client names.
- Anything not provided goes in a single editable file, /data/site-data.ts, as clearly marked placeholders like "[Company Name]". Hide any section whose data is still empty (metrics, certifications) instead of showing fake numbers.
- No fake skill percentages.

MY DETAILS (use as real data)
- Name: Nithish Kumar. Role: Cloud Architect · DevOps Engineer · AI Engineer. Location: India.
- Education: B.E./B.Tech student, Artificial Intelligence & Data Science, Kings College of Engineering, Punalkulam.
- Real projects (use these first, placeholders only for the rest):
  1. SmartCloud: intelligent cloud storage with tiered storage, deduplication, encryption and versioning. Node.js/Express, AWS S3, MongoDB.
  2. Secure E-commerce App: Angular, full security architecture.
  3. Department Communication App: teachers-and-students platform, React.
  4. LifeGuard: Python emergency-health application concept.
- Email / LinkedIn / GitHub / Resume: [add yours, hide any left empty]

SECTIONS (in order)
1. Nav: sticky transparent, wordmark "NITHISH KUMAR", links Home, About, Skills, Experience, Projects, Architecture, Certifications, Contact. Animated hamburger on mobile.
2. Hero: H1 "Building Cloud Infrastructure. Automating Everything. Engineering Intelligent Systems." Subtext: "I'm Nithish Kumar — a Cloud Architect, DevOps Engineer, and AI Engineer focused on building scalable infrastructure, reliable deployment systems, and intelligent applications." Pulsing badge "● Available for opportunities". CTAs: "View My Work", "Let's Connect", and a text link "Download Resume". Visual: animated pipeline Developer → Git → CI/CD → Containers → Kubernetes → Cloud → Monitoring → AI Services, with glowing animated connectors.
3. About: "Engineering at the intersection of Cloud, Automation & AI". Profile card, plus an Engineering Philosophy block: "Automate repetitive work. Design for scale. Build for failure. Measure everything. Use AI where it creates real leverage."
4. Skills: interactive ecosystem of animated cards grouped by Cloud, DevOps, Programming, AI Engineering, Observability, Databases. Use the skill lists below. Only list a skill as strong if marked so in site-data.ts.
5. Architecture Playground (the showpiece): three clickable diagrams, where clicking a node opens a short explanation. (a) Highly Available Web App: Users → CDN → Load Balancer → Kubernetes → Microservices → Redis → PostgreSQL → Object Storage. (b) Production AI App: User → Frontend → API Gateway → AI App → RAG Pipeline → Embedding Model → Vector DB → LLM → Response. (c) Modern DevOps Platform: Developer → GitHub → CI → Testing → Docker Build → Registry → Kubernetes → ArgoCD → Production. Simplified vertical layout on mobile.
6. "From Commit to Production": animated pipeline CODE → BUILD → TEST → SECURITY SCAN → CONTAINERIZE → PUSH IMAGE → DEPLOY → MONITOR. Each stage has an icon, a one-line explanation, and a hover/tap tooltip with tools (e.g. Security Scan: Trivy · SonarQube · Snyk; Deploy: Kubernetes · Helm · ArgoCD; Monitor: Prometheus · Grafana · OpenTelemetry).
7. "Engineering with AI": cards for AI Agents, RAG, LLM Applications, Intelligent Automation, AI APIs, Document Intelligence, AI-powered DevOps, Developer Productivity Tools. Include an interactive AI terminal that types out `$ nithish-ai --analyze architecture` and then shows: ✓ High availability detected, ✓ Auto-scaling configured, ✓ CI/CD pipeline detected, ⚠ Database backup strategy recommended.
8. Featured Projects: premium cards with Problem, Solution, Architecture, Technologies, Key achievements (placeholder if unknown), GitHub button, Live Demo button only if a URL exists.
9. Experience: vertical timeline with fields [Company], [Role], [Start–End], responsibilities, technologies, achievements. Placeholders only; include an education entry from my details.
10. Certifications: cards grouped by AWS / Azure / GCP / Kubernetes / Terraform / DevOps / AI-ML. Show only provided ones, otherwise one placeholder card.
11. "Building in Public": GitHub repos, languages, stars via the public GitHub API (public data only, cached, graceful fallback). Username: [add].
12. Metrics: animated counters only for real values; hidden if empty.
13. "Engineering Notes": blog cards (title, description, date, category, Read Article) with placeholder posts across Kubernetes, AWS, Terraform, CI/CD, Cloud Security, RAG, AI Agents, System Design.
14. Interactive terminal: commands help, about, skills, projects, contact, whoami, role, focus, status, with a typing effect. Optional/collapsed on mobile.
15. Contact: "Let's Build Something Reliable." / "Have a cloud architecture challenge, automation problem, or AI idea? Let's talk." Form (Name, Email, Message) with validation, a honeypot and rate limiting, and button "Start a Conversation". Show only the links I provide.
16. Footer: name, tagline, social links, "Designed & engineered by Nithish Kumar", "● Systems operational".

SKILLS DATA
Cloud: AWS, Azure, Google Cloud, Cloud Architecture, Serverless, Networking, IAM, Load Balancing, Auto Scaling.
DevOps: Docker, Kubernetes, Terraform, Ansible, Jenkins, GitHub Actions, GitLab CI/CD, ArgoCD, Helm, IaC.
Programming: Python, JavaScript, TypeScript, Bash, SQL.
AI: Generative AI, LLM Apps, AI Agents, RAG, Vector Databases, Prompt Engineering, AI APIs, Model Integration, AI Automation.
Observability: Prometheus, Grafana, ELK, OpenTelemetry, CloudWatch.
Databases: PostgreSQL, MySQL, MongoDB, Redis.

ANIMATION
Scroll reveals, card hover glow, animated connectors, terminal typing, subtle floating nodes and particles, animated gradients. Respect prefers-reduced-motion. No heavy effects on mobile. Don't overuse animation.

SEO
Title: "Nithish Kumar | Cloud Architect · DevOps Engineer · AI Engineer". Description: "Nithish Kumar is a Cloud Architect, DevOps Engineer and AI Engineer focused on scalable cloud infrastructure, automation, DevOps platforms and intelligent applications." Add Open Graph, Twitter cards, JSON-LD Person schema, sitemap.xml, robots.txt, semantic HTML.

PERFORMANCE
Dynamic-import Three.js and heavy diagrams, next/image, next/font, no layout shift, no horizontal scroll on mobile, cards stack vertically.

DELIVERABLE
Full file tree, all code, and a short README explaining how to edit /data/site-data.ts and deploy to Vercel. Build in this order: layout + design system → hero → architecture playground → pipeline → remaining sections → SEO/accessibility pass.
