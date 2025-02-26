## What I Learned

### 1. Environment Configuration & Validation
- Managing environment variables with `dotenv`
- Implementing strong typing and validation using `zod`
- Handling different environments (development, test, production)

### 2. TypeScript Best Practices
- Type safety and validation
- Interface definitions
- Environment type checking
- Error handling with type safety

### 3. Database Management
- Working with multiple database clients (PostgreSQL and SQLite)
- Database migrations using Knex
- Query building and data access patterns

### 4. API Development with Fastify
- Route handling
- Middleware implementation
- Cookie management
- Request/Response lifecycle
- Error handling

### 5. Testing Practices
- Unit testing with Vitest
- Integration testing with Supertest
- Test environment setup
- Database seeding for tests

### 6. Development Tools
- Code formatting with Biome
- ESLint configuration
- npm scripts for automation
- Git version control

## Functional Requirements (FR)
- (✅) **Create Transaction:** The user must be able to create a new transaction.
- (✅) **Account Summary:** The system must provide a summary (balance) of the user's account.
- (✅) **List Transactions:** The user can list all transactions that have occurred.
- (✅) **View Single Transaction:** The user can access the details of a specific transaction.

## Business Rules (BR)
- (✅) **Transaction Type:** Each transaction can be a credit (which adds to the total) or a debit (which subtracts from the total).
- (✅) **User Identification:** It is necessary to identify the user in every request, ensuring that actions and data are linked to them.
- (✅) **View Permission:** The user can only view the transactions they have created.
