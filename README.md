# Ibrahim Issa

Backend-focused software engineer building APIs, data pipelines, and LLM-powered systems in Python and TypeScript, interested in healthcare.

### What I work on

- LLM and agentic systems: tool calling, multi-agent workflows, structured extraction, MCP, OpenAI / Anthropic APIs
- Backend and data: FastAPI, Node.js, PostgreSQL, ETL/ingestion pipelines, Kafka, RabbitMQ
- Healthcare tech: HL7 v2, FHIR, DICOM, EMR integrations, HIPAA-compliant PHI handling and audit trails
- Infrastructure: AWS (ECS, Lambda, S3), Temporal, Docker, Kubernetes, CI/CD

### Projects

| Project | Stack | Description |
| --- | --- | --- |
| [Healthcare Intake Orchestration Workflow](https://github.com/Ibrahimango02/healthcare-referral-pipeline) | Python · Temporal · HL7 · FHIR · Anthropic API · AWS Lambda | Temporal workflow that ingests HL7/FHIR referrals, runs an LLM agent step to extract fields, validates results via AWS Lambda, and writes records to a FHIR server, with durable retries and human-review signals. |
| [Chest X-Ray Diagnostic Tool](https://github.com/Ibrahimango02/X-Ray-Assist) | Python · PyTorch · FastAPI · React · DICOM | Medical imaging tool with async DICOM processing queues and a React UI with attention-map visualization, backed by a PyTorch model for three chest conditions (89% accuracy on 50,000+ X-rays). |
| [Al-Mahir Academy Portal](https://github.com/Ibrahimango02/almahir-portal) | TypeScript · Next.js · React · Supabase · Tailwind CSS · Vercel | Management portal for an online academy with role-based areas for admins, teachers, students and parents: recurring classes and timezone-aware scheduling with conflict checks, attendance and session reports, invitation-based onboarding, and invoicing and teacher payments. |
