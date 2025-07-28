# Network basics and DevOps 
 Find the difference between LAN, MAN, and WAN
 Search engine behind the different browsers
 What is DNS 
 different network devices like a switch, router, modem, hub and so on
 | Device                | Role in Home Setup                                     |
| --------------------- | ------------------------------------------------------ |
| **Modem**             | ISP signal receive + convert karta hai                 |
| **Router**            | Sab devices ko connect karta hai, IP assign karta hai  |
| **Switch** (optional) | Wired devices ko efficiently connect karta hai         |
| **Access Point**      | Wireless internet provide karta hai                    |
| **Firewall**          | Tumhara network secure rakhta hai                      |
| **Devices**           | Tumhare phone, laptop, TV — jo internet use karte hain |

 command to print Google IP address
 DNS tree structure 
 different Protoclos 
 Explain IP address , what is IP4 and IPv6
 OSI Model
 TCP IP model
 
# Before DevOps
  1) The development team build the code and hands it over to the operations team for deployment. 
  2) The operations team deploy the code and shares the feedback with the Development team.
  3) This process consumes time, or you can say it delays the process of completing the project

# DevOps purpose 
  1) Merge the Development Team and the Operations team.
  2) The development team write the plan according to the Project features.
  3) Start the development and put it in a single place like Git (version control). It may contain different versions.
  4) Use build tools like **Maven** or **Gradle**.
  5) Do the testing like Selenium Express.
  6) Then the Ops tasks start
  7) Deploy the code and operate
  8) For operation, tools are used like **Ansible**, **Docker**, **Kubernetes**
  9) Then monitor the application/deployment using tools like **Nagios**
  10) Last but not least, **Jenkins**, to perform all these operations automatically and combine the Dev and Ops teams.
        . Pipelines are created  to manage all the processes before going to production.

# Development life cycle
  <img width="765" height="241" alt="Screenshot 2025-07-24 at 12 39 57" src="https://github.com/user-attachments/assets/7089542c-24f4-462c-af0e-9cb0fb9c4b35" />

### Planning 
  1) The planning phase of DevOps is one of the most important phase, which decide the failure or success of the project.
  2) In this phase, all stakeholders come together and decide what needs to be built, how to build, and how to deliver.
  3) Before DevOps, the software pipeline was considered a straight line, but DevOps changed it to a continuous and dynamic process.
  4) Also called linear process (2D) and continuous process (3D)
<img width="1536" height="1024" alt="planning" src="https://github.com/user-attachments/assets/1a0a7f74-78e8-479c-9dbb-2858c003e654" />

### Designing
 1) Mixing design and coding phases blurs the distinction between software architecture (e.g., APIs, databases) and implementation, leading to poor strategic decisions.
 2) Delayed architectural decisions (e.g., database design) result in weak and inconsistent software structures, reflecting outdated 2D linear thinking.
 3) Modern DevOps pipelines are 3D, circular, and feedback-driven, integrating design, feedback, and deployment, unlike the linear Waterfall model.
<img width="1024" height="1024" alt="planningD" src="https://github.com/user-attachments/assets/fd39e19d-d43f-40f8-8a05-3869f4281764" />

### Coding 
1) Coding is seen as glamorous but is just the execution of prior planning and design, which are the real keys to success.
2) Strong planning and design make coding simple; over-crediting coding is misguided.
3) This 2D linear mindset shifts in Part 3 to a 3D DevOps pipeline with interconnected stages and continuous feedback, not a fixed start-to-end line.

### Testing 
1) Testing involves all engineers (not just QA), offering a chance to learn about testing, maintainability, and security.
2) Various methods ensure software meets expected behaviour.
3) This 2D linear pipeline shifts in Part 3 to a 3D continuous model, with testing as a dynamic, feedback-driven process.
<img width="1024" height="1024" alt="plT" src="https://github.com/user-attachments/assets/3908e69f-4721-4520-9a90-d7c75ae4a513" />

### Deploying 
 1) Traditionally, deployment/release was the operations team's domain: developers wrote code, QA tested it, and ops deployed "ready code" to customers.
 2) This linear, 2D approach gave each team a distinct stage with limited responsibility.
 3) In modern DevOps (per Part 3), the pipeline is 3D: release is a shared responsibility where development, QA, and ops collaborate via automated CI/CD pipelines, making it a continuous, collaborative process, not just an endpoint.

### Maintaining 
1) After software goes live in the production environment, it still requires active support and improvement—this is called the maintenance phase.
2) Fixing bugs reported by users
3) Adding new features based on feedback
4) Applying security patches
5) Updating for compatibility (e.g., new OS/browser support)

### Deprecating
1) When a feature or entire software becomes obsolete or is replaced by a new version, it is "deprecated"—gradually phased out of use.
2) Users are notified that the feature or software version will no longer be supported.
3) Migration plans are created (e.g., moving from an old API to a new one).
4) An end-of-life (EOL) date is announced.
5) Security support is gradually discontinued.

# Designing for DevOps
In DevOps, software is carefully planned to help users the most. Keep these three rules in mind:

**Build for Change:** Old code isn’t bad—it’s just outdated because it needs to change fast. Make software easy to update with:
  1) Independent parts
  2) Clear documentation
  3) Standard methods
  4) Easy-to-move code
     
**Keep Code Consistent:** As your team and software grow, make the code look like one person wrote it, including infrastructure code.

**Always Improve:** Use linting tools to set style rules (like adding semicolons), keeping the codebase clean and consistent, even if it’s not perfect.
