```javascript
class Developer {
  constructor() {
    this.name = "Jacob Ilagan";
    this.title = "Full Stack Developer";
    this.company = "Kenilworth Media Inc.";
    this.location = "Toronto, Ontario, Canada";
    
    this.education = {
      inProgress: {
        credential: "Advanced Diploma",
        program: "Computer Programming & Analysis",
        school: "Seneca Polytechnic",
        graduation: "December 2025"
      },
      completed: {
        credential: "Honours Bachelor of Arts (HBA)",
        school: "University of Toronto",
        major: "Philosophy & Political Science",
        graduation: "2023"
      }
    };
    
    this.journey = {
      origin: "Philosophy & Political Science @ University of Toronto",
      pivot: "Discovered programming combines logic, creativity, and impact",
      approach: "Apply philosophical reasoning to system design and debugging",
      perspective: "Question assumptions, think systematically, write clearly",
      result: "Building enterprise solutions serving 1,500+ users"
    };
    
    this.workExperience = [
      {
        role: "Full Stack Developer",
        company: "Kenilworth Media Inc.",
        period: "July 2025 - Present",
        project: "VetMedTeam Platform",
        description: "Enterprise continuing education platform for veterinary professionals",
        impact: "1,000+ active users",
        highlights: [
          "Auth0 SSO integration across multiple platforms",
          "GraphQL API connecting VetMedTeam ↔ PathLMS",
          "Angular 19 modernization (235 files, 17K+ lines refactored)",
          "RACE/VHMA compliance tracking systems"
        ]
      },
      {
        role: "Full Stack Developer",
        company: "Ontario Public Service",
        period: "2024 - 2025",
        project: "GoCloud Platform",
        description: "Government cloud infrastructure management",
        impact: "500+ government users",
        highlights: [
          "Azure cost calculator with real-time pricing",
          "Secure cloud infrastructure management tools"
        ]
      }
    ];
    
    this.techStack = {
      frontend: ["Angular 19", "React", "TypeScript", "JavaScript"],
      backend: ["C#", ".NET 8", "Node.js", "Python"],
      database: ["SQL Server", "PostgreSQL", "Entity Framework"],
      cloud: ["Azure", "AWS", "Docker"],
      architecture: ["Clean Architecture", "RESTful APIs", "GraphQL"],
      auth: ["Auth0", "OAuth2", "JWT"]
    };
  }
}

const jacob = new Developer();
```
