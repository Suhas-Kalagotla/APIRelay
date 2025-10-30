# APIRelay

it is an API testing framework designed to make testing REST, SOAP, and GraphQL APIs easier.

It Focuses on dependency parameter resolution, encryption/decryption and HMAC generation

## 🤝 Contributing

Contributions are welcome!  
To get started:

1. Fork this repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes and commit (`git commit -m "Add feature X"`)
4. Push to your fork and open a Pull Request

More detailed contribution guidelines will be available soon in **CONTRIBUTING.md**.

## Roadmap

- [ ] **Setup Infrastructure**
  - [ ] Initialize **MERN + TypeScript** backend
  - [ ] Setup **React + TypeScript** frontend
  - [ ] Configure database (**mysql**) and environment variables

- [ ] **Architecture & Database Design**
  - [ ] Define clear module boundaries for frontend, backend, and test engine
  - [ ] Design scalable database schema for users, APIs, and test configurations
  - [ ] Document architecture in `/docs/architecture.md`

- [ ] **User Authentication**
  - [ ] Implement user **Sign Up / Sign In** with JWT authentication
  - [ ] Add encrypted password storage

- [ ] **Auto Header Generation**
  - [ ] Implement automatic header population (Auth tokens, timestamps, HMACs)

- [ ] **API Testing Engine**
  - [ ] Build core engine to execute REST, SOAP, and GraphQL requests
  - [ ] Support running tests via CLI and frontend UI

- [ ] **Parameter Dependency Resolution**
  - [ ] Implement logic to automatically resolve dependent parameters
  - [ ] Example: if an API requires a `sessionToken` fetched from `getSessionToken`,  
         the framework should auto-fetch and inject it dynamically into the dependent API.

- [ ] **Reporting and Logs**
  - [ ] Display execution summary in the frontend dashboard

- [ ] **Future Enhancements**
  - [ ] Plugin support for custom encryption algorithms

## Community

Join the discussion and help shape APIRelay’s roadmap!

- Share ideas and feedback via GitHub Issues
- Contribute bug fixes and new features
- Collaborate with developers who care about secure and reliable APIs

