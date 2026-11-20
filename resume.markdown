---
layout: resume
title: Resume
permalink: /resume/
hide_masthead: true
---
<style>
.resume { --line: rgba(128,128,128,0.3); --maroon: #862633; }
.resume .hero { position: relative; animation: hero-in 0.5s cubic-bezier(0.22, 1, 0.36, 1) both; background: linear-gradient(135deg, #1f2937, #111827); color: #fff; border-radius: 16px; padding: 3.2em 1.5em 1.5em; display: flex; gap: 1.2em; align-items: center; margin-bottom: 1.4em; }
.resume .hero img { view-transition-name: pm-avatar; width: 92px; height: 92px; border-radius: 50%; object-fit: cover; border: 3px solid rgba(255,255,255,0.3); flex-shrink: 0; }
.resume .hero h1 { view-transition-name: pm-name; width: fit-content; margin: 0; font-size: 1.8em; color: #fff; }
.resume .hero p { margin: 0.2em 0 0; opacity: 0.85; color: #fff; }
.resume .hero a { color: #fff; text-decoration: underline; }
.resume .hero a.back { position: absolute; top: 0.9em; left: 1.2em; text-decoration: none; font-size: 0.9em; font-weight: 600; opacity: 0.85; }
.resume .hero a.back:hover { opacity: 1; text-decoration: underline; }
@keyframes hero-in { from { opacity: 0; transform: translateY(-12px); } to { opacity: 1; transform: none; } }
@media (prefers-reduced-motion: reduce) { .resume .hero { animation: none; } }
.resume h2 { margin: 1.6em 0 0.7em; font-size: 0.85em; letter-spacing: 0.12em; text-transform: uppercase; opacity: 0.7; }
.resume .card { display: flex; gap: 1.1em; padding: 1.1em; margin-bottom: 1em; border: 1px solid var(--line); border-left-width: 6px; border-radius: 12px; }
.resume .card img { width: 84px; height: 84px; object-fit: contain; flex-shrink: 0; }
.resume .card-body { flex: 1; min-width: 0; }
.resume .card h3 { margin: 0; font-size: 1.15em; }
.resume .role { font-weight: 600; margin: 0.1em 0; }
.resume .meta { opacity: 0.75; font-size: 0.9em; margin: 0 0 0.5em; }
.resume .badge { display: inline-block; padding: 0.05em 0.6em; margin-right: 0.4em; border-radius: 999px; background: rgba(128,128,128,0.2); font-weight: 600; }
.resume .card ul { margin: 0.4em 0 0 1.1em; padding: 0; }
.resume .card li { margin: 0.3em 0; }
.resume .tag { display: inline-block; padding: 0.1em 0.7em; margin: 0.15em 0.25em 0.15em 0; border: 1px solid rgba(128,128,128,0.4); border-radius: 999px; font-size: 0.88em; }
.resume .edu { background: var(--maroon); color: #fff; border-radius: 14px; padding: 1.3em; display: flex; align-items: center; gap: 1.3em; flex-wrap: wrap; }
.resume .edu .logo { background: #fff; border-radius: 10px; padding: 0.6em 1em; }
.resume .edu .logo img { height: 62px; display: block; }
.resume .edu p { margin: 0; color: #fff; }
@media (max-width: 600px) { .resume .hero, .resume .card { flex-direction: column; } }
</style>
<div class="resume">
<div class="hero">
<a class="back" href="/">&larr; Home</a>
<img src="/assets/img/headshot.png" alt="Paul M. Carrier">
<div>
<h1>Paul M. Carrier</h1>
<p>Senior Software Engineer | Cloud Capacity &amp; Platform Engineering</p>
<p><a href="mailto:paulmcarrier@gmail.com">paulmcarrier@gmail.com</a></p>
</div>
</div>
<p>Senior Software Engineer with 10+ years in cloud infrastructure, DevOps, and platform engineering. Builds Python and TypeScript tooling that automatically scales a large AWS platform for high-traffic live events and streaming debuts on Disney+ and Hulu. Leads projects from PRD to delivery, performs design reviews, and mentors junior engineers.</p>
<h2>Experience</h2>
<div class="card" style="border-left-color:#113ccf">
<img src="/assets/img/logos/disney.jpg" alt="The Walt Disney Company logo">
<div class="card-body">
<h3>The Walt Disney Company</h3>
<p class="role">Senior Software Engineer, Capacity Management</p>
<p class="meta"><span class="badge">Nov 2021 – Present</span>Remote</p>
<ul>
<li>Build and maintain Python and TypeScript tooling that scales Disney's cloud platform, running on AWS EKS and ECS.</li>
<li>Automate capacity for 2,000+ AWS resources, making thousands of scaling adjustments per day across Auto Scaling Groups, ECS services, EKS pods, ALB LCUs, and DynamoDB read/write capacity.</li>
<li>Lead scaling for high-traffic tentpole events, including NFL games, the Oscars, election coverage, WWE, UFC, and major Disney+ and Hulu premieres.</li>
<li>Lead projects end to end, from PRD through design, implementation, and delivery.</li>
<li>Perform design reviews and mentor junior engineers on the team.</li>
<li>Use an AI-driven development workflow to deliver tooling faster.</li>
</ul>
</div>
</div>
<div class="card" style="border-left-color:#e03127">
<img src="/assets/img/logos/airtank.jpg" alt="Airtank logo">
<div class="card-body">
<h3>Airtank Inc.</h3>
<p class="role">Senior Operations Engineer</p>
<p class="meta"><span class="badge">Nov 2018 – Nov 2021</span>Remote (Peterborough, NH)</p>
<ul>
<li>Built and maintained the infrastructure stack (Kubernetes, Elasticsearch, DynamoDB) for Ziftrshop, a headless, API-driven enterprise e-commerce platform.</li>
<li>Reduced cost and deployment time by building and maintaining CI/CD pipelines and tooling.</li>
<li>Supported client and internal infrastructure in the cloud and on premises.</li>
<li>Drove DevOps culture across the company through policy change and hands-on work.</li>
<li>Managed on-call schedules and incident response for developers and operations staff.</li>
<li>Maintained PCI compliance for internal projects and supported customers as a sales engineer.</li>
</ul>
</div>
</div>
<div class="card" style="border-left-color:#f08a1c">
<img src="/assets/img/logos/illuminate.jpg" alt="Illuminate Education logo">
<div class="card-body">
<h3>IO Education / Illuminate Education</h3>
<p class="role">Senior DevOps Engineer</p>
<p class="meta"><span class="badge">Jan 2017 – Nov 2018</span>Remote (Atlanta, GA / Irvine, CA)</p>
<ul>
<li>Supported AWS infrastructure and guided 5 development teams across separate product lines.</li>
<li>Maintained CI/CD pipelines and took part in the on-call support rotation.</li>
<li>Acted as operations liaison in product planning meetings.</li>
</ul>
</div>
</div>
<div class="card" style="border-left-color:#2fb67c">
<img src="/assets/img/logos/ziftr.jpg" alt="Ziftr logo">
<div class="card-body">
<h3>MyVBO / Ziftr LLC</h3>
<p class="role">DevOps Engineer</p>
<p class="meta"><span class="badge">Jul 2015 – Dec 2016</span>Remote (Merrimack, NH)</p>
<ul>
<li>Supported AWS application infrastructure and built automation (Chef, Jenkins, OpsWorks) for continuous delivery.</li>
<li>Managed incident response and led recovery during major service interruptions.</li>
<li>Maintained PCI compliance documentation and verified security standards through penetration testing.</li>
</ul>
</div>
</div>
<h2>Skills</h2>
<div>
<span class="tag">Python</span><span class="tag">TypeScript</span><span class="tag">Node.js</span><span class="tag">Bash</span><span class="tag">EC2</span><span class="tag">Auto Scaling</span><span class="tag">EKS</span><span class="tag">ECS</span><span class="tag">ALB</span><span class="tag">DynamoDB</span><span class="tag">CloudFormation</span><span class="tag">CloudFront</span><span class="tag">CloudWatch</span><span class="tag">RDS</span><span class="tag">S3</span><span class="tag">VPC</span><span class="tag">Route 53</span><span class="tag">Kubernetes</span><span class="tag">Docker</span><span class="tag">Nginx</span><span class="tag">GitHub Actions</span><span class="tag">PagerDuty</span><span class="tag">Atlassian</span><span class="tag">Linux</span>
</div>
<h2>Education</h2>
<div class="edu">
<div class="logo"><img src="/assets/img/logos/shu.png" alt="Sacred Heart University logo"></div>
<p><strong>Bachelor of Science, Natural Sciences</strong><br>Fairfield, CT · 2011</p>
</div>
</div>
