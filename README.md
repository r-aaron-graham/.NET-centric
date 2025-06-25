# 🟣 .NET Showcase – Blazor + Minimal API + CI/CD

A mini-project proving hands-on knowledge of modern .NET 8:

| Layer | Tech | Highlights |
|-------|------|------------|
| Frontend | **Blazor WebAssembly** | Runs entirely in the browser, C# end-to-end |
| API | **Minimal API** | Single-file, dependency-injected, Swagger-enabled |
| Core Logic | **Class Library** | DI-friendly, unit-tested with xUnit |
| Deployment | **Docker + AKS or GitHub Pages** | Containerized API; Blazor auto-deployed to GPages |
| CI | **GitHub Actions** | Build, test, publish artefacts |

➡️ **Live demo** (GitHub Pages):  
`https://<username>.github.io/dotnet-showcase/`

Clone & run locally:

```bash
git clone https://github.com/<username>/dotnet-showcase.git
cd dotnet-showcase
dotnet run --project src/Showcase.Api

