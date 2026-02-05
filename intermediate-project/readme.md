### 2. Intermediate Project (`intermediate-project/`)

**Best for:** Medium-sized applications, small teams, production apps

```
gatherup/
├── app/                   # Next.js App Router with route groups
│   ├── (auth)/           # Authentication routes
│   ├── (dashboard)/      # Protected dashboard routes
│   ├── (marketing)/      # Public marketing routes
│   └── api/              # API routes
├── features/             # Feature-based organization
│   ├── events/           # Event-related functionality
│   ├── rsvp/             # RSVP functionality
│   └── users/            # User management
├── server/               # Server-side logic
│   ├── auth/             # Authentication configuration
│   ├── db/               # Database schema and client
│   ├── mutations/        # Database mutations
│   ├── queries/          # Database queries
│   └── services/         # Business logic services
├── ui/                   # Shared UI components
├── lib/                  # Utility functions
└── tests/                # Test files
```

**Key Characteristics:**

- ✅ Feature-based organization
- ✅ Clear separation of client/server code
- ✅ Database layer abstraction
- ✅ Testing infrastructure
- ✅ Authentication integration
- ✅ Payment processing
- ❌ More complex to set up
- ❌ Requires understanding of patterns

**Dependencies:**

- Next.js 15.5.0
- NextAuth.js for authentication
- Prisma ORM with PostgreSQL
- Stripe for payments
- UploadThing for file uploads
- Vitest for testing
