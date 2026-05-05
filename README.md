```javascript
class Developer {
  constructor() {
    this.name = "Jacob Ilagan";
    this.title = "Full Stack Developer";
    this.company = "Kenilworth Media Inc.";
    this.location = "Toronto, Ontario, Canada";

    this.education = {
      inProgress: "Advanced Diploma — Computer Programming & Analysis @ Seneca Polytechnic (2025)",
      completed: "HBA Philosophy & Political Science @ University of Toronto (2023)"
    };

    this.experience = [
      {
        role: "Full Stack Developer",
        company: "Kenilworth Media Inc.",
        period: "July 2025 – Present",
        highlights: [
          "Auth0 SSO across 3 platforms (192K users)",
          "Angular 19 standalone architecture migration",
          "GraphQL integration: VetMedTeam ↔ PathLMS",
          "Sole dev: n8n AI newsletter pipeline (RSS → AI parsing → Supabase → email) targeting 6-figure subscription revenue",
          "Flagged PCI DSS violation → proposed fix saving $20K+/yr"
        ]
      },
      {
        role: "Full Stack Developer (Freelance)",
        period: "Dec 2025 – Present",
        highlights: [
          "RAG-based AI parts recommendation system (Python/FastAPI + LangChain)",
          "Semantic search over 2,000+ products via ChromaDB/Pinecone",
          "B2B e-commerce platform w/ QuickBooks Desktop integration"
        ]
      },
      {
        role: "Full Stack Developer Intern",
        company: "Ontario Public Service",
        period: "May 2024 – Aug 2025",
        highlights: [
          "GoCloud cost estimation app (React + Cosmos DB) — 100+ estimates/month",
          ".NET + SQL Server enterprise apps — 10–20% perf improvement"
        ]
      }
    ];

    this.techStack = {
      frontend:    ["Angular 19", "React", "TypeScript", "RxJS"],
      backend:     ["C#/.NET 8", "Node.js", "FastAPI", "GraphQL"],
      ai:          ["LangChain", "RAG", "n8n", "Vector Embeddings", "ChromaDB", "Pinecone"],
      database:    ["SQL Server", "PostgreSQL", "Supabase", "MongoDB", "Cosmos DB"],
      cloud:       ["Azure", "AWS", "Docker"],
      auth:        ["Auth0", "OAuth2", "JWT", "SSO"]
    };
  }
}

const jacob = new Developer();
```
