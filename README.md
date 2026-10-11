        # .NET ECS Career Lab

        Project-based interview prep aligned to [career-lab-master-plan](https://github.com/umairrafi/muhammad-umair-portfolio/blob/main/docs/career-lab-master-plan.md) and [complete catalog](https://github.com/umairrafi/muhammad-umair-portfolio/blob/main/docs/career-lab-complete-catalog.md).

        ## Who this is for

        - Backend engineers building public proof for job switch (UAE/GCC — 25k AED framing in master plan §6)
        - Developers mapping **engineering-profile** evidence to buildable labs (no employer secrets)

        ## Prerequisites

        [devops-career-lab](https://github.com/umairrafi/devops-career-lab) weeks 1–3 · [payments-career-lab](https://github.com/umairrafi/payments-career-lab) concepts

        ## Capstone: PayRail Service

        Evolving codebase in [`capstone/payrail-service/`](capstone/payrail-service/) — run instructions in capstone README.

        ## Roadmap

        | Week | Topic | Folder | Objective |
        |------|-------|--------|-------------|
        | **1** | Layered ASP.NET Core | [week-01-layered-aspnet](weeks/week-01-layered-aspnet/) | Api/Service split, OpenAPI/Scalar |
| **2** | Dapper + MySQL | [week-02-dapper-mysql](weeks/week-02-dapper-mysql/) | Reader/writer pattern |
| **3** | Two-level cache | [week-03-redis-cache](weeks/week-03-redis-cache/) | Memory + Redis TTLs |
| **4** | Health live/ready | [week-04-health-checks](weeks/week-04-health-checks/) | ECS/ALB probes |
| **5** | Docker + ECR | [week-05-docker-ecr](weeks/week-05-docker-ecr/) | Multi-stage Dockerfile |
| **6** | Terraform ECS | [week-06-terraform-ecs](weeks/week-06-terraform-ecs/) | Fargate service + workspaces |
| **7** | Strangler routing | [week-07-strangler-routing](weeks/week-07-strangler-routing/) | ALB rule narrative |
| **8** | Capstone + k6 | [week-08-capstone-k6](weeks/week-08-capstone-k6/) | Load smoke baseline |

        ## Weekly structure

        ```
        week-NN-slug/
        ├── README.md
        ├── 01-lessons/
        ├── 02-hands-on/
        ├── 03-exercises/
        └── 04-capstone-project/
        ```

        ## Start here

        ```bash
        cd weeks/week-01-layered-aspnet
        cat README.md
        ```

        ---

        Built by [Muhammad Umair Virk](https://muhammad-umair.pages.dev) · Backend · UAE
