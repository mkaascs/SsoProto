# 🔐 SSO gRPC Service - Proto + Go

Protobuf-first authentication service for microservices architecture. Provides both the API contract and Go server implementation.

**gRPC Service:**
- `Auth.Login` - User authentication with JWT tokens
- `Auth.Register` - New user registration
- `Auth.IsAdmin` - Role-based access control

**Tech Stack:**
- 🏗️ **Protocol Buffers** - API definition
- ⚡ **Go gRPC** - High-performance implementation
- 🔐 **JWT Tokens** - Stateless authentication
- 📦 **Go Module** `mkaascs.v1.sso/ssov1`

---