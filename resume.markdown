---
layout: page
title: Resume
permalink: /resume/
---
<style>
.resume .lead { font-size: 1.15em; font-weight: 700; margin: 0 0 0.3em; }
.resume h2 { margin-top: 1.6em; padding-bottom: 0.25em; border-bottom: 2px solid rgba(128,128,128,0.35); }
.resume .job { display: flex; gap: 1em; align-items: flex-start; padding: 1em; margin: 1em 0; border: 1px solid rgba(128,128,128,0.3); border-radius: 10px; }
.resume .job img { width: 64px; height: 64px; border-radius: 12px; object-fit: contain; background: #fff; flex-shrink: 0; }
.resume .job-body { flex: 1; min-width: 0; }
.resume .job h3 { margin: 0; font-size: 1.15em; }
.resume .role { font-weight: 600; margin: 0.1em 0; }
.resume .meta { opacity: 0.75; font-size: 0.9em; margin: 0 0 0.5em; }
.resume .badge { display: inline-block; padding: 0.05em 0.6em; border-radius: 999px; background: rgba(128,128,128,0.18); font-weight: 600; margin-right: 0.4em; }
.resume .job ul { margin: 0.4em 0 0 1.1em; padding: 0; }
.resume .job li { margin: 0.3em 0; }
.resume .skill-row { margin: 0.6em 0; }
.resume .skill-label { font-weight: 700; display: block; margin-bottom: 0.2em; }
.resume .tag { display: inline-block; padding: 0.1em 0.65em; margin: 0.15em 0.25em 0.15em 0; border-radius: 999px; border: 1px solid rgba(128,128,128,0.4); font-size: 0.88em; }
@media (max-width: 600px) { .resume .job { flex-direction: column; } }
</style>
<div class="resume">
<p class="lead">Senior Software Engineer | Cloud Capacity &amp; Platform Engineering</p>
<p>Contact: <a href="mailto:paulmcarrier@gmail.com">paulmcarrier@gmail.com</a></p>
<h2>Summary</h2>
<p>Senior Software Engineer with 10+ years in cloud infrastructure, DevOps, and platform engineering. Builds Python and TypeScript tooling that automatically scales a large AWS platform for high-traffic live events and streaming debuts on Disney+ and Hulu. Leads projects from PRD to delivery, performs design reviews, and mentors junior engineers.</p>
<h2>Experience</h2>
<div class="job">
<img src="/assets/img/logos/disney.jpg" alt="The Walt Disney Company logo">
<div class="job-body">
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
<div class="job">
<img src="/assets/img/logos/airtank.jpg" alt="Airtank logo">
<div class="job-body">
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
<div class="job">
<img src="/assets/img/logos/illuminate.jpg" alt="Illuminate Education logo">
<div class="job-body">
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
<div class="job">
<img src="/assets/img/logos/ziftr.jpg" alt="Ziftr logo">
<div class="job-body">
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
<div class="skill-row"><span class="skill-label">Languages</span><span class="tag">Python</span><span class="tag">TypeScript</span><span class="tag">Node.js</span><span class="tag">Bash</span></div>
<div class="skill-row"><span class="skill-label">AWS</span><span class="tag">EC2</span><span class="tag">Auto Scaling</span><span class="tag">EKS</span><span class="tag">ECS</span><span class="tag">ALB</span><span class="tag">DynamoDB</span><span class="tag">CloudFormation</span><span class="tag">CloudFront</span><span class="tag">CloudWatch</span><span class="tag">RDS</span><span class="tag">S3</span><span class="tag">VPC</span><span class="tag">Route 53</span></div>
<div class="skill-row"><span class="skill-label">Containers</span><span class="tag">Kubernetes</span><span class="tag">Docker</span><span class="tag">Nginx</span></div>
<div class="skill-row"><span class="skill-label">CI/CD &amp; Operations</span><span class="tag">GitHub Actions</span><span class="tag">PagerDuty</span><span class="tag">Atlassian</span><span class="tag">Linux</span></div>
<div class="skill-row"><span class="skill-label">Practices</span><span class="tag">Capacity planning</span><span class="tag">Auto-scaling</span><span class="tag">AI-driven development</span><span class="tag">Incident response</span><span class="tag">PCI compliance</span></div>
<h2>Education</h2>
<p><strong>Sacred Heart University</strong>, Fairfield, CT. B.S., Natural Sciences, 2011</p>
</div>
