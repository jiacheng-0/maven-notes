# maven notes
 
## Introducing Maven

https://www.linkedin.com/learning/introducing-maven

3 default maven **lifecycles** are 

- Default
- Clean
- Site



Which is an example of a **tools plugin** used by Apache Maven?

- Compilation
- Installation
- Deployment
- Validation



**Packaging** Plugins

- JAR
  - The standard Java way
- WAR
  - **W**eb application **AR**chive
- EAR
- SHADE



### 2. Build - Plugins

#### Core

- deploy
  - Deploy the built artifact to the remote repository
  - linkedin learning: 
    - takes the packaged artifact + metadata and push it to internal or external repositories 
    - "Deploy your artifact that is installed in your local .m2 repo to a central repository."

#### Tools

- release
  - Release the current project - updating the POM and tagging in the SCM
  - build and release project
  - change version
  - tagging things in SCM
  - releasing project to organisation repo



### 3. Dependencies

#### Compile scope

















