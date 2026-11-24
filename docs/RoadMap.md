LEARN QURAN WITH AI - ROADMAP
==============================================================================


1. PHASES
------------------------------------------------------------------------------

  Phase   Implementation             Learning focus
  -----   ------------------------   ------------------------------------------
    1     Next.js, TypeScript        Clean architecture
    2     PostgreSQL, migrations     DDIA: data modeling, indexes
    3     FastAPI                    API contracts, concurrency
    4     AI model serving           Inference, embeddings, RAG
    5     AI evaluation              Accuracy, hallucinations, latency
    6     Stripe                     Webhooks, transactions, idempotency
    7     Redis, background jobs     DDIA: caching, consistency, queues
    8     Docker, CI/CD              Deployment, observability, reliability


2. TECH STACK
------------------------------------------------------------------------------

  Layer              Technology
  ----------------   ---------------------------------------------------------
  Frontend           Next.js, TypeScript strict mode, Tailwind CSS
  Backend            Next.js Route Handlers
  AI service         FastAPI, Python, Pydantic
  Model inference    PyTorch, ONNX Runtime where appropriate
  Database           PostgreSQL
  ORM                Drizzle
  Vector search      pgvector
  Caching            Redis
  Background jobs    Celery
  Authentication     Auth.js
  Payment            Stripe
  Object storage     S3-compatible storage
  API contracts      OpenAPI
  Testing            Vitest, Playwright, Pytest
  Observability      OpenTelemetry, Sentry
  Infrastructure     Docker, Nginx
  CI/CD              GitHub Actions


3. ENGINEERING PRINCIPLES
------------------------------------------------------------------------------

  Priority       Implementation
  ------------   -------------------------------------------------------------
  Speed          SSR, streaming, caching, connection pooling,
                 optimized inference
  Flexibility    Modular architecture, dependency injection,
                 model abstraction
  Quality        Strict typing, automated testing, linting, AI evaluations
  Scalability    Stateless services, async processing,
                 independent AI workers
  Security       RBAC, rate limiting, input validation, secret management,
                 webhook verification


4. OPEN SOURCE FILES
------------------------------------------------------------------------------

  File                  Purpose
  -------------------   -------------------------------------------------------
  README.md             Project overview and setup instructions
  LICENSE               Legal usage and distribution permissions
  CONTRIBUTING.md       Guidelines for contributors
  SECURITY.md           Vulnerability reporting policy
  CODE_OF_CONDUCT.md    Community behavior guidelines
  CHANGELOG.md          Release history
  docs/adr/             Architecture decision records
