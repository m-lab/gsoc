# Google Summer of Code 2026

Welcome to M-Lab's Google Summer of Code page! We're excited to have you here and look forward to working with talented contributors from around the world.

## About Measurement Lab (M-Lab)

Measurement Lab (M-Lab) [https://www.measurementlab.net/](https://www.measurementlab.net/) is an open source project with contributors from civil society organizations, educational institutions, and private sector companies dedicated to:
- Providing an open, verifiable measurement platform for global network performance
- Hosting the largest open Internet performance dataset on the planet
- Creating visualizations and tools to help people make sense of Internet performance


## Why Participate with Us?

- **Mentorship**: Work closely with experienced developers and active community members
- **Real Impact**: M-Lab's tools are used by a large community of researchers, policymakers, and open Internet advocates. Your contributions can become a core part of M-Lab's tools.
- **Skill Development**: Gain hands-on experience with Python, JavaScript and other Web technologies, large datasets (SQL, BigQuery)
- **Open Source**: All work is open source and publicly available

## Getting Started

### 1. Familiarize Yourself with Our Project

Before applying, we strongly encourage you to:

- Explore our [main repository](https://github.com/orgs/m-lab/repositories) and the repositories of the proposed projects (see below)
- Visit our [website](https://www.measurementlab.net/) and read about our [activities](https://www.measurementlab.net/about/), [news](https://www.measurementlab.net/blog/), and documentation of our [tools](https://www.measurementlab.net/tests/) and [data](https://www.measurementlab.net/data/)
- Join our communication channels:
  - Mailing list: [link](https://groups.google.com/a/measurementlab.net/g/discuss)

### 2. Make Your First Contribution

We highly value applicants who have already contributed to our project. Here's how to get started:

1. **Find a good first issue**: Look for issues tagged with `good-first-issue` or `gsoc-starter`
2. **Introduce yourself**: Comment on the issue expressing your interest
3. **Submit a pull request**: Even small contributions (documentation, bug fixes, tests) are valuable
4. **Engage with the community**: Ask questions, help others, participate in discussions

### 3. Develop Your Proposal

A strong proposal should include:

- **Personal Information**: Name, contact details, time zone, GitHub username
- **Background**: Your relevant experience, skills, and courses
- **Project Selection**: Which project idea(s) interest you and why
- **Project Plan**: 
  - Clear objectives and deliverables
  - Weekly timeline with milestones
  - Technical approach and implementation details
  - Testing strategy
  - Documentation plan
- **Availability**: Expected hours per week, any planned absences
- **Why You**: What makes you a good fit for this project
- **Post-GSoC**: Your plans for continued involvement

### 4. Submit Your Application

- Application period: Feb 19 to Mar 31 (see official [timeline](https://developers.google.com/open-source/gsoc/timeline))
- Submit through the [official GSoC website](https://summerofcode.withgoogle.com/)
- Deadline: 31 March 2026
- You may submit up to 3 proposals total (across all organizations)

## Communication Guidelines

- **Be respectful**: Follow our Code of Conduct
- **Be patient**: Mentors are volunteers and may take time to respond
- **Be proactive**: Don't wait to be told what to do
- **Ask smart questions**: Show what you've already tried
- **Use public channels**: So others can learn and help too

## Project Ideas

Below are project ideas for GSoC 2026. These are starting points - we encourage you to propose your own ideas or variations on these themes!

**Difficulty Levels:**
- 🟢 Easy (90 hours) - Good for first-time GSoC participants
- 🟡 Medium (175 hours) - Requires some project familiarity
- 🔴 Hard (350 hours) - Complex projects requiring deep expertise

---

### Project 1: Modernize Murakami Python Codebase

**Difficulty**: 🟡 Medium (175 hours)  
**Mentor(s)**: Pavlos Sermpezis, Roberto D'Auria, Simone Basso
**Skills Required**: Python 3.10+, Docker, Poetry, Git, CI/CD (GitHub Actions), Network measurement

- [Murakami GitHub Repository](https://github.com/m-lab/murakami)

---

### Project 2: IQB Analytics Dashboards - ISP Performance Insights and Comparisons

**Difficulty**: 🔴 Hard (350 hours)  
**Mentor(s)**: Pavlos Sermpezis, Roberto D'Auria, Simone Basso  
**Skills Required**: Python, Data Visualization (Plotly), Streamlit, Pandas  
**Skills Preferred**: Geographic data visualization, BigQuery/SQL, UX/UI design, Statistics  
**Detailed Description**: [link](./gsoc2026_project2_IQB_dashboards.md)

---

### Project 3A: Enhanced Speed Test Results with Insights and Comparisons (Medium)

**Difficulty**: 🟡 Medium (175 hours)  
**Mentor(s)**: Pavlos Sermpezis, Roberto D'Auria, Simone Basso  
**Skills Required**: JavaScript, Angular.js, HTML/CSS, REST APIs  

#### Description

M-Lab's speed test at speed.measurementlab.net is one of the most widely used open-source Internet measurement tools globally. Currently, after running a test, users receive basic metrics (download/upload speeds, latency) but limited context about what these numbers mean or how they compare to others. This project enhances the results page to provide actionable insights and meaningful comparisons.

You'll extend the speed test interface to calculate and display IQB (Internet Quality Barometer) scores based on test results, explain what the results mean for different use cases (streaming, gaming, video calls), and show how the user's performance compares to their ISP's average and regional benchmarks. This makes the speed test results more meaningful and helps users understand their Internet quality in practical terms.

#### Resources

- [M-Lab Speed Test Repository](https://github.com/m-lab/mlab-speedtest)
- [Speed Test Website](https://speed.measurementlab.net)
- [IQB project](https://github.com/m-lab/iqb)
- [NDT Protocol Documentation](https://www.measurementlab.net/tests/ndt/)

---

### Project 3B: Enhanced Speed Test with User Authentication and History Dashboard (Hard)

**Difficulty**: 🔴 Hard (350 hours)  
**Mentor(s)**: Pavlos Sermpezis, Roberto D'Auria, Simone Basso  
**Skills Required**: JavaScript, HTML/CSS, REST APIs, Authentication (OAuth/Firebase Auth), Database design, Data visualization, Security best practices

#### Description

This extended version of Project 3A includes all the features from the medium project (IQB scores, insights, comparisons) plus a comprehensive user authentication system and personalized dashboard for tracking measurement history over time.

Users will be able to create accounts, run tests while logged in, and access a personal dashboard showing their historical test results, trends over time, comparisons across different locations/networks, and personalized recommendations. This transforms the speed test from a one-time measurement tool into a long-term monitoring solution that helps users track their Internet quality, identify patterns, and make informed decisions about their service.

You'll implement secure user authentication, design a database schema for storing user measurements, build a personal dashboard with rich visualizations, ensure privacy compliance (GDPR, data retention policies), and maintain the existing functionality for anonymous users who don't want to create accounts.

#### Resources

- [M-Lab Speed Test Repository](https://github.com/m-lab/mlab-speedtest)
- [Speed Test Website](https://speed.measurementlab.net)
- [IQB project](https://github.com/m-lab/iqb)
- [NDT Protocol Documentation](https://www.measurementlab.net/tests/ndt/)

---


## Selection Criteria

We evaluate proposals based on:

1. **Prior engagement**: Contributions to our project, community participation
2. **Proposal quality**: Clear goals, realistic timeline, technical soundness
3. **Communication**: Clarity, responsiveness, professionalism
4. **Relevant experience**: Skills and background relevant to the project

## Frequently Asked Questions

### Can I work on multiple projects?

No, GSoC allows you to work on only one project. However, you can submit proposals for up to 3 different projects across all organizations.

### I'm a beginner. Can I still apply?

Absolutely! We have projects for all skill levels. Start with our "good first issues" and don't hesitate to ask questions.

### What programming languages do I need to know?

This depends on the project. See individual project descriptions for required and preferred skills.

### Do I need to make contributions before applying?

While not mandatory, prior contributions significantly strengthen your application and help you understand our workflow.

### What happens if I can't complete the project?

Communication is key. If you face challenges, reach out to your mentors immediately. We're here to help you succeed.

### Can I apply if I'm not a student?

GSoC is open to new open-source contributors who are 18 years or older. You don't need to be enrolled in a university.

---

**Good luck with your application!** 🚀
