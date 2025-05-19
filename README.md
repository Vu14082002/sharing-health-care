# Sharing Health Care

This repository is a monorepo that integrates three main services to provide a comprehensive health care platform:

## Submodules

- **chat-service**
  Real-time chat service for patient-doctor and internal communication.
  [Source](https://github.com/Vu14082002/chat-service)

- **health-care**
  Core backend service for health care management, including patient records, appointments, and more.
  [Source](https://github.com/Vu14082002/health-care)

- **health-care-bot**
  AI-powered chatbot for health care support and automation.
  [Source](https://github.com/Vu14082002/health-care-bot)

## Getting Started

1. Clone the repository with submodules:
   ```bash
   git clone --recurse-submodules <repo-url>
   ```

2. Follow the setup instructions in each submodule’s `README.md` to run the services.

## Project Structure

```
chat-service/        # Real-time chat microservice (Node.js)
health-care/         # Main backend service (Python)
health-care-bot/     # AI chatbot service (Java)
```

## License

See individual submodules for license information.
