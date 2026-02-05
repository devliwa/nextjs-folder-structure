### 3. Advanced Project (`advanced-project/`)

**Best for:** Large applications, enterprise projects, multiple teams

```
gatherup/
├── app/                   # Next.js App Router with advanced routing
│   ├── (core)/           # Core application routes
│   ├── (public)/         # Public routes
│   └── api/              # API routes with microservice structure
├── entities/             # Domain entities (DDD approach)
│   ├── event/            # Event domain
│   ├── rsvp/             # RSVP domain
│   └── user/             # User domain
├── features/             # Feature modules
│   ├── create-event/     # Event creation feature
│   ├── host-payouts/     # Host payout feature
│   ├── rsvp-event/       # RSVP feature
│   └── search/           # Search feature
├── widgets/              # Complex UI widgets
├── shared/               # Shared infrastructure
│   ├── config/           # Configuration management
│   ├── libs/             # Shared libraries
│   │   ├── auth/         # Authentication utilities
│   │   ├── cache/        # Caching layer
│   │   ├── db/           # Database utilities
│   │   ├── http/         # HTTP client
│   │   ├── logger/       # Logging system
│   │   └── queue/        # Background job queue
│   ├── ui/               # Design system components
│   └── validation/       # Shared validation schemas
├── processes/            # Business processes
├── services/             # External service integrations
├── tests/                # Comprehensive testing
│   ├── e2e/              # End-to-end tests
│   ├── integration/      # Integration tests
│   └── unit/             # Unit tests
└── scripts/              # Build and deployment scripts
```

**Key Characteristics:**

- ✅ Domain-Driven Design (DDD) approach
- ✅ Microservice-ready architecture
- ✅ Comprehensive testing strategy
- ✅ Advanced routing with parallel routes
- ✅ Shared infrastructure layer
- ✅ Scalable for large teams
- ✅ Separation of concerns at every level
- ❌ Complex setup and learning curve
- ❌ Overkill for small projects
- ❌ Requires architectural expertise

**Dependencies:**

- Next.js 15.5.0
- Advanced routing patterns
- Comprehensive testing setup
- Infrastructure abstractions
- Design system components
