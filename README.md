**Global Finance Report**

This report has been developed using Claude-based automation.

Claude was used to:
- Generate DAX measures
- Suggest and apply changes to the report after integration
- Recommend visualizations based on the dataset and business requirements

The report is designed to provide insights into financial performance through optimized data modeling and automated enhancements.

---

## Project Structure

After Git integration with Microsoft Fabric, the repository is organized as follows:
## CI/CD Pipeline

A CI/CD pipeline has been implemented to enable efficient version control, collaboration, and automated deployment of the Power BI/Fabric assets.

### Process Overview

1. **Development**
   - Reports and datasets are created and updated in the Fabric workspace.
   - Claude automation assists in generating measures and improving report design.

2. **Version Control (Git Integration)**
   - Workspace is connected to a GitHub repository.
   - All changes (reports, datasets) are synced and stored as code in structured folders.

3. **Commit & Sync**
   - Changes are committed from Fabric to GitHub using the Git integration feature.
   - Maintains version history and traceability.

4. **CI/CD Workflow**
   - GitHub acts as the central repository for managing changes.
   - Pipelines (if configured with GitHub Actions/Azure DevOps) can:
     - Validate changes
     - Trigger deployments
     - Automate testing and updates

5. **Deployment**
   - Updates from Git can be pulled into Fabric workspaces.
   - Ensures consistency across environments (Dev/Test/Prod).

---

## Key Benefits

- ✅ Version control for Power BI reports and datasets  
- ✅ Automated and structured deployment process  
- ✅ Improved collaboration across teams  
- ✅ Reduced manual effort using automation  
- ✅ Scalable solution aligned with enterprise practices  

---

## Notes

- Dashboards are not fully version-controlled; underlying reports and datasets are tracked.
- Changes in Fabric workspace can be synced with Git using Git integration.
