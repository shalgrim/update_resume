# New Resume Sections

## PROFESSIONAL SUMMARY

- Backend engineer specializing in API development and partner integrations
- 8+ years at Zapier delivering enterprise features and backend systems using Python, Django, and AWS
- M.A. in Computational Linguistics with background in natural language processing and machine learning
- Experience spans API design, data engineering, and maintaining critical integrations with external partners

## WORK EXPERIENCE

**Zapier, Remote**                                                                January 2017 – October 2025
*Senior Engineer, Backend (2023-2025) | Integrations Engineer (2019-2023) | Data Engineer (2017-2019)*

- **Founded data engineering function** as Zapier's first Data Engineer, building production Apache Airflow infrastructure on AWS, establishing ETL pipelines ingesting from diverse sources (MySQL databases, REST APIs, SaaS platforms) into Redshift, coordinating with Matillion to organize data warehouse in star schema, and creating data quality framework ("Assertion Machine") enabling cross-organizational analytics.

- **Developed machine learning systems** for support operations: built supervised learning classifiers in Python to categorize and score email difficulty, reducing False Discovery Rate from 6-8% to under 2%; created `/FDR` Slack command for real-time model performance monitoring; deployed ticket difficulty classifier to Kubernetes.

- **Maintained strategic partner integrations** for dozens of apps including Zoom, Slack, Facebook Lead Ads, and Gmail, collaborating directly with partner engineering teams; rescued Zoom integration during pandemic by identifying bugs, migrating code to Zapier control, and shipping New Meeting Registrant trigger (#10 overall feature request); uncovered Slack API bugs through high-volume usage during their API migration, strengthening partnership.

- **Architected firehose webhook handling** for CLI-based integrations, enabling Zapier platform apps to process account-level event streams from services like Zoom and Slack that don't support per-user webhook subscriptions, unlocking functionality previously limited to monolith-based integrations.

- **Delivered enterprise platform features** using Python, Django, and DRF: shipped Alerts system from concept to production as part of Enterprise SKU with optimized performance (reduced p90 from 7s to 3.5s through caching and parallel GraphQL); migrated Notification Rules' heaviest email traffic to Knock for improved resilience, observability, and customization; led QA and architected synchronization layer for Multi-Product Folders (Org Service) to maintain consistency between local database and distributed permissions API.

- **Championed AI adoption**, recognized as organizational leader in Claude Code usage, producing training demos and evangelizing AI-assisted development practices that accelerated code reviews, skills test evaluations, and development workflows across engineering teams.

- **Contributed to open source and engineering quality**: submitted accepted pull requests to Django core; implemented disaster recovery plans across services; enhanced testing frameworks; established infrastructure best practices including SonarQube deployment with comprehensive documentation.

- **Developed technical leadership** through mentoring engineers on complex PRs, leading architectural discussions, and conducting technical interviews; recognized for knowledge sharing through documentation, presentations (DjangoCon, internal talks), and cross-team collaboration.

---

## Technology Stack to Add/Update

**Programming Languages**: Python, Java, C#, SQL, XML, C++, XAML, Golang
**Frameworks/Packages**: Django, Django REST Framework (DRF), cTAKES (UIMA), GATE, Mallet, NLTK, libSVM, pytest
**Infrastructure/Cloud**: AWS (SQS, Lambda, RDS, CloudWatch), Apache Airflow, Kubernetes, CDK, Terraform
**Databases**: PostgreSQL, Redshift, SQL Server, Oracle, MySQL, Microsoft Access, Entity Framework
**Tools**: Looker, Datadog, Grafana, OpenSearch, OpenAPI, SonarQube

---

## Notes for Integration

1. Replace the old CAREER OBJECTIVE section with the new PROFESSIONAL SUMMARY
2. Add the Zapier work experience as the first entry under WORK EXPERIENCE
3. Update the TECHNOLOGY EXPERIENCE section with the expanded technology stack
4. Consider whether to keep all the older NLP positions or condense them since they're 10+ years old
5. You may want to remove or significantly shorten the NLP PROJECTS section since it's from 2009
