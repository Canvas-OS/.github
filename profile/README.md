# Hello, welcome to Canvas:OS 👋

### Why We Exist
We're here to help organisations find flow and perform at their best. 

### What We Do
Canvas:OS is an organisational improvement platform, with a range of interactive charts, tools, and templates to create a holistic picture of your organisation from purpose to practice.

### How We Do It

## 🛠️ Languages and Frameworks

- **TypeScript** - Over 90% of the project is written in TS because it's cool to be safe
- **Next.js** - React framework with App Router for server-side rendering and lots of good stuff OOTB
- **React** - UI library and state management
- **Tailwind CSS** - The user friendly CSS framework
- **Drizzle ORM** - Type-safe database ORM for PostgreSQL ops

## 📦 Key Packages

### Visualisation
- **D3.js** - Library for custom charts. Currently using the packed circles, sunburst, and force-directed charts
- **Chart.js** - For simpler read only charts
- **Material UI** - Dynamic tables
- **Mermaid** - User generated charts in the rich text editor

### Content Creation
- **TipTap** - Rich text editor
- **Novel** - Notion style WYSIWYG package to extend Tiptap
- **Mistral** - LLM powered autocomplete
- **TLDraw** - Infinte sketch canvas

### Testing
- **Vitest** - Unit testing framework with TypeScript support
- **Playwright** - End-to-end testing

### Communication
- **Pusher** - Real-time WebSocket communication for chat and notifications

### UI & Components
- **Radix UI** - Accessible UI primitives
- **Lucide React** - Icon library
- **React Hook Form** - Performant forms with minimal re-renders
- **React DnD** - Drag and drop for the chart content manager
- **React Colorful** - Tidy little colour picker

## 🌐 3rd Party Services

- **Vercel** - Hosting platform with edge functions and analytics
- **Neon Database** - Serverless PostgreSQL database with automatic scaling
- **Pusher** - Real-time messaging and WebSocket infrastructure
- **Upstash Redis** - Serverless Redis for caching and rate limiting
- **Semgrep** - Static analysis security scanning
- **Stripe** - Payment processing and subscription management
- **SendGrid** - Email and marketing automation
- **Notion API** - [Public integration]([url](https://www.notion.com/integrations/135d872b594c80a6adb40037ac517711)) for auth and workspace sharing
- **Microsoft Graph** - Partner integration for auth and AD directory syncing
- **Google** - Auth and directory syncing

## 🔄 GitHub Actions

### Continuous Integration
- **Vitest Runner** - Automated unit and integration testing on push/PR
- **Playwright E2E** - End-to-end testing suite
- **CodeCov Integration** - Test coverage reporting and analysis

### Security & Compliance
- **Semgrep Security Scanning** - Daily security vulnerability scans
- **CodeQL Analysis** - GitHub's semantic code analysis
- **Dependabot** - Dependency updates and security patches

### Database
- **AWS Backup** - Daily PostgreSQL backups to S3 with 30-day retention

## 🔒 Security

### Encryption
- **Message Encryption** - Transit and storage encryption using webcrypto for community messaging
- **Notification Encryption** - Transit and storage encryption of team notifications and alerts

### Access Control
- **Cloudflare Turnstile** - Bot protection and cleaner CAPTCHA alternative for signup
- **Vercel Firewall** - Edge-level request filtering and DDoS protection
- **NextAuth.js** - Secure auth with Notion, Google, and Microsoft providers

### Rate Limiting & Monitoring
- **CSRF Protection** - Cross-site request forgery prevention
- **Input Sanitisation** - DOMPurify for secure HTML content handling

## ✨ Key Capabilities

### Interactive Charts
- **BYOD Charts** - Bring Your Own Data charting with CSV upload (integrations coming soon...)
- **Org Charts** - Configurable org chart
- **Custom Notion Charts** - Dynamic charts synced with Notion databases
- **Notion Workspace Map** - Interactive packed circle chart with the page and db hierarchy within a teamspace
- **Notion Database Relations** - DB relationship mapping using the force-directed chart
- **Embeddable** - Embeddable as iframe

### Canvases
- **Interactive Drawing** - Performant Canvases using tlDraw
- **Canvas Persistence** - Event based auto save
- **Embeddable** - Embeddable canvas creations (read only for now)

### Community Channels
- **Real-time Chat** - Channel-based messaging with a rich text editor
- **Channels** - Unlimited channel creation and access management
- **Notifications** - Real-time message notifications

### Content Editor
- **Rich Text Editor** - Advanced content editing with TipTap and Novel
- **Template System** - Editable content templates

### Assessments
- **Team Health Checks** - Simple, repeatable team health checks
- **OS Scans** - OS health assessment
- **Analytics Dashboard** - Results charts, tables, and trend insights

---

Built with ❤️ by Harry Tucker
