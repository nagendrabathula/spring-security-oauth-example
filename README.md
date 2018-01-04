# Spring Security OAuth Example

- `spring-security-client` - Client Project which has the UI 
- `spring-security-auth-server` - Has the Authorization Server and Resource Server
- `http://localhost:8082/ui` - REST end point for UI which will take you to the secure URI `http://localhost:8082/ui/secure` after logging into the auth server `http://localhost:8081/auth/login`
- `First Url`:`http://localhost:8081/auth/login`
- `UserName`:Peter
- `Password`:peter
- `Second Url`:`http://localhost:8082/ui`.
- After Login to OAuth This Url will take you to the secure URI  `http://localhost:8082/ui/secure` with message Like 'Spring Security OAuth Example - Secured   Welcome to TechPrimers! Peter'
