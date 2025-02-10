# Dataworks_Automation_Agent
An LLM-powered automation agent for executing operational and business tasks, integrating into CI pipelines, and ensuring security constraints while automating routine workflows.

# Features
✅ Accepts plain-English task descriptions and executes automation steps.  
✅ Supports file processing, data extraction, formatting, LLM-based analysis, and API interactions.  
✅ Implements security measures (restricted file access, no deletions).  
✅ Exposes API endpoints:
   - **`/run?task=<task description>`** - Executes a task.
   - **`/read?path=<file path>`** - Retrieves file contents.
✅ Containerized using Docker for easy deployment.  

# Installation & Usage
Clone the repository and set up the environment:

```bash
git clone https://github.com/disha471/Dataworks_Automation_Agent.git
cd Dataworks_Automation_Agent

