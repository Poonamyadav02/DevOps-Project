# DevOps Project  

##  Overview  
This repository contains the complete DevOps Project setup, including branching strategy, pull request workflow, version tags, and task documentation.  

##  Branches  
- **main** – Stable production-ready code  
- **dev** – Development branch  
- **feature/** – Feature-specific branches (example: `feature/setup`)  

##  Workflow  
1. Develop features in `feature/*` branches  
2. Create a pull request to merge `feature/*` → `dev`  
3. Test in `dev`  
4. Merge `dev` → `main` when stable  

##  Tech Stack  
- Git / GitHub  
- Jenkins  
- Terraform  
- Docker  
- AWS  

##  How to Contribute  
1. Fork the repo  
2. Clone your fork  
3. Create a new branch: `git checkout -b feature/your-feature`  
4. Commit changes  
5. Push to your fork  
6. Create a Pull Request  

##  Versioning  
We use Git tags for versioning. Example:  
```bash
git tag -a v1.0 -m "Initial version"
git push origin v1.0
