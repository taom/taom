# Tao Ma

**Senior Software Engineer | AI Systems, Full-Stack Platforms, and Production Reliability**

Yorba Linda, CA | [tao@koslu.com](mailto:tao@koslu.com) | 909-732-5466 | [github.com/taom](https://github.com/taom)

I'm a software engineer with 18+ years of experience and an M.S. in Computer Science (Intelligent Robotics) from USC. I build and run mobile apps, websites, and server applications with Python, TypeScript, React, React Native, C#/.NET, SQL, AWS, and Azure. Recent work includes AI-enabled applications, LLM benchmarking and evaluation, and ticketing, payments, and subscriber-billing platforms in production.

I've led architecture and delivery for three production platforms, including a four-developer team, and I work directly with non-technical stakeholders. I handle projects from requirements and system design through deployment and ongoing support.

[Current projects](#koslu-llc) · [Earlier experience](#earlier-experience) · [Technical skills](#technical-skills) · [Education](#education)

Most of my professional contributions are in private repositories, 33 repos so far.

## Koslu LLC

**Senior Software Engineer | January 2020 - Present**

I build and operate mobile, web, and server applications for ticketing, payments, billing, telecom, real-time gaming, and AI projects. My work covers requirements, architecture, implementation, deployment, and production support.

### Technical leadership

I led architecture and delivery for Safer Seating, ClearBilling, and Oonie/Care, including a four-developer team, as project manager and architect. I set technical direction and requirements, reviewed code and mentored developers, met delivery deadlines, served as the main client contact, and owned end-to-end testing.

### Safer Seating

Safer Seating is a production event-ticketing platform covering venue seating maps, season passes, payments, digital wallet passes, email notifications, ticket printing, ticket scanning, refunds, and reporting.

I designed and operated the cloud backend on Azure, the Blazor web client, iOS and Android ticketing apps, the gate scanner, and the Stripe payment integration.

- Raised uptime from **80% to 99.99%**
- Cut checkout from **5 minutes to 15 seconds** and gate entry from **3 minutes to 5 seconds**
- Cut the error rate from **10% to 0.1%** and reporting from one week to minutes
- Supported **53,000+ tickets** across 98 games and **18,000+ gate check-ins** over the 2024–2026 seasons

### ClearBilling

ClearBilling is a subscriber-billing platform covering recurring billing and AutoPay, background jobs, reporting, and monitoring.

I implemented customer payment and receipt flows with Stripe and IPPay, recurring payments and AutoPay, nightly billing and invoice delivery, and customer reports with date filters and CSV export. I improved database models and indexes, and set up and managed a privately hosted datacenter with an automated deployment pipeline and automatic service-interruption alerts and recovery.

- Cut hosting costs by **$2,000/month**
- Cut storm recovery from **days to 3 minutes**

### Oonie and Oonie Care

Oonie is an AI-enabled location-tracking platform; Oonie Care is part of Oonie. Their intended uses include real-time family tracking, travel audits, daily habits and schedules, and AI-assisted elder care and monitoring.

I developed cross-platform location and senior-care features: real-time GPS trip tracking, live family location updates, LLM-generated driving summaries, a WebRTC-based video and voice calling stack, and a live messaging service. I also worked on model orchestration, caching, and offline workflows.

For Oonie Care, I implemented image-based text recognition for photos of medicine labels and prescriptions. It extracts names, strengths, and directions and flags unclear text. Other contributions include caregiver access, daily care tasks, and activity views.

### Public APIs

I designed and maintained public-facing APIs for Safer Seating and Oonie/Care, including API versioning, deprecation of older versions, and rate limiting for client and partner traffic.

### Finder Server

Finder Server is a real-time game-matching backend built with .NET, Blazor, SignalR, and managed databases, supporting **tens of thousands of concurrent players**. My contributions include matchmaking, session monitoring, game statistics and duration metrics, server health checks, connection logs, and cleanup of abandoned sessions.

### SCRP Assist

I automated FCC document and data-processing workflows with a Chrome extension, CSV parsing and synchronization, and connected SignalR services, cutting processing from **30 minutes to 15 seconds per item**. The extension populates and submits claim forms, parses posted claims, and synchronizes portal history with the internal system.

### Euclid EPC

Euclid EPC is a mobile and broadband network management and provisioning system. My work includes data parsing and batch processing, subscriber and device workflows, external-service API integrations, claim submission, and invoice exports.

### Model testing

I designed Python benchmarks and performance tests for local open-weight LLMs on PCs and Macs, as well as models on Hugging Face and OpenRouter, and compared them with OpenAI, Claude, and Gemini models on quality, cost, performance, limits, and features.

I built side-by-side views of provider outputs and use manual and repeatable test cases to evaluate AI application behavior.

### Bluetooth nearby discovery

I'm a co-inventor on a patent application for Bluetooth-based nearby discovery. I contributed to the technical design and wrote technical material for the application.

### Internal applications

I build internal websites, web applications, and mobile apps with React and React Native. Across my projects, I review code and use unit, integration, and end-to-end tests and source control in daily work.

## Earlier experience

### Tangerine Apps

**Software Engineer | 2015 - 2019**

I wrote Python VFX pipelines for Disney film projects to ingest and sort assets, build and manage render farms, run render scripts, generate previews, and prepare vendor handoffs. This work also covered virtual cameras and VR filmmaking tools.

For Unity/C# projects, I handled most of the programming for simulations, visualizations, VR, and AR, integrating headsets, mobile devices, and tracked inputs.

- Built a digital twin of SoFi Stadium and venue simulations for the LA 2024 Olympic bid, including stadium, archery, and UCLA Village environments
- Built a live VR gameplay showcase for *Cars 3*, broadcast on Twitter to more than one million live viewers
- Built a Unity-based digital interview experience for Forky, adapting a facial tracker to animate the character from an actor's facial expressions and speech in real time
- Created interactive film experiences for *The Jungle Book*, *Beauty and the Beast*, *Black Panther*, and *Thor: Ragnarok* across HTC Vive, Oculus, Gear VR, Google Tango, Cardboard, and Kinect
- Created photogrammetry reconstructions and visualizations for independent films

### Smartbox Mobile

**DevOps Engineer | 2012 - 2015**

- Built and operated AWS-hosted services, APIs, and application backends, including FootballHero; automated deployment, scaling, and operations
- Developed administrative tools and analytics with logging and alerts; built the GreenGlobe audit backend to import spreadsheets and handle photo and document evidence
- Connected regional wireless providers' CRM, customer-care, point-of-sale, and back-office systems through API gateways

### NTCH CA / ClearTalk

**Systems Engineer | 2007 - 2012**

I built and supported software for subscriber management, payments, billing, reporting, and dealer services, and integrated service gateways and operational tools for wireless-provider workflows.

### University of Southern California

**Web Developer (student position) | 2006 - 2007**

I built websites for the chemical engineering, materials science, and petroleum engineering programs, working directly with faculty and department staff.

## Technical skills

- **AI systems and evaluation:** OpenAI, Claude, and Gemini APIs; local open-weight LLMs; model orchestration; LLM benchmarking and evaluation on quality, speed, and cost; agent workflows; repeatable test cases
- **Languages and frameworks:** Python, TypeScript, JavaScript, C#, SQL, Java, HTML/CSS; React, React Native/Expo, Node.js, .NET/ASP.NET Core, Blazor, .NET MAUI, Entity Framework, Unity
- **Cloud and infrastructure:** AWS (Bedrock, EC2, S3, Aurora, Lambda, SNS, SQS, IAM, MediaLive); Azure (App Service, SignalR, Notification Hubs); Cloudflare (DNS, Email, CDN, Workers, Pages, D1, TURN); load balancing, managed databases, deployment automation; Windows, Linux, macOS
- **Payments and billing:** Stripe, IPPay, recurring billing, AutoPay, refunds, receipts, reconciliation and reporting
- **Data and performance:** SQL, MongoDB, SQLite, REST APIs, batch processing, data pipelines, query optimization, caching, logging, monitoring
- **Engineering and security:** Docker, security scanning, attack mitigation, code review, unit, integration, and end-to-end testing; source control (Git, GitHub, Perforce, SVN, Azure DevOps)

## Education

- **University of Southern California:** Master of Science in Computer Science (Intelligent Robotics), 2005 - 2007
- **Southeast University, China:** Bachelor of Science in Automation, 2001 - 2005
