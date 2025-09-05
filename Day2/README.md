# Day2 Azure Boards and Agile Project Management 📊

# Checkout the video below for Day2


## Azure DevOps Demo Generator
**Use these steps to load dummy data into your Azure DevOps project. We will use this data in the demo.**

1. Navigate to https://azuredevopsdemogenerator.azurewebsites.net. This utility site will automate the creation of a new Azure DevOps project within your account that is prepopulated with content (work items, repos, etc.) required for the lab. 

2. Sign in using the Microsoft account associated with your Azure DevOps subscription.


3. Accept the permission requests for accessing your subscription.

4. Select the PartsUnlimited template and click Select Template.


5. Click Create Project and wait for the process to complete.



## Azure Boards Overview 
Azure board is a project management tool to plan and track your work.

## Defining Teams and Work Items

### What is a Work Item:
A work item can track all types of activities. It could be a 
*  Task to do
*  A bug to fix,
*  An issue
or anything that we can assign to people and keep track of the progress.


## Kanban Board 📃

Kanban is a visual method for managing and optimizing work items. In simple terms, it is a visual board that helps teams keep track of their tasks and work more efficiently. It can be divided into multiple stages such as **todo, in-progress, and done**.


## Azure Boards Processes

1) **Basic**: Choose Basic when your team wants the simplest model that uses Issues, Tasks, and Epics to track work.
2) **Agile**
3) **Scrum**
4) **CMMI**

The basic process contains three work item types:
- Epics: Group your more significant items into Epics such as Website updates, Cloud migration, CICD implementation
- Issues: Further divide your Epics into Issues such as Homepage, about us page, secure sign-in
- Task: Tasks are the smallest amount of work that can be assigned to someone, for example, designing a homepage header, standardizing fonts, and fixing the homepage CSS to make it mobile responsive.



<h1>Basic Azure Board</h1>

<ul>
  <li class="epic">
    <span class="icon">👑</span>Epics
    <ul>
      <li class="epic">
        <span class="icon">👑</span>Website Updates for www.thecloudopscommunity.org
        <ul>
          <li class="issue">
            <span class="icon">📗</span>Homepage
            <ul>
              <li class="task"> <span class="icon">☑</span>Designing a homepage header </li>
              <li class="task"> <span class="icon">☑</span>Standardizing fonts </li>
              <li class="task"> <span class="icon">☑</span>Fixing the homepage CSS to make it mobile responsive </li>
            </ul>
          </li>
          <li class="issue">
            <span class="icon">📗</span>About Us Page
            <ul>
              <!-- Add specific tasks for the About Us Page -->
            </ul>
          </li>
          <li class="issue">
            <span class="icon">📗</span>Secure Sign-In
            <ul>
              <!-- Add specific tasks for Secure Sign-In -->
            </ul>
          </li>
        </ul>
      </li>
      <li class="epic">
        <span class="icon">👑</span>Cloud Migration
        <ul>
          <!-- Add specific tasks for Cloud Migration -->
        </ul>
      </li>
      <li class="epic">
        <span class="icon">👑</span>CICD Implementation
        <ul>
          <!-- Add specific tasks for CICD Implementation -->
        </ul>
      </li>
    </ul>
  </li>
</ul>


## Scrum process
**A scrum-based process typically involves below work items:**


1. **User Stories:**
   - Represents a small piece of functionality from an end user's perspective.

2. **Tasks:**
   - Breakdown of user stories into smaller, manageable tasks.

3. **Bugs:**
   - Represents defects or issues identified during development or testing.

4. **Epics:**
   - Larger bodies of work that can be broken down into multiple user stories.

5. **Features:**
   - Represents a functional group of user stories or a larger piece of work.

6. **Product Backlog:**
   - A prioritized list of all work items that must be addressed in the project - All the To-dos.

7. **Sprint Backlog:**
   - Subset of the product backlog that the Development Team commits to completing during a specific sprint - ALL the Sprint To-dos.

8. **Impediments:**
   - Obstacles or issues that hinder the progress of the team.

9. **Test Cases:**
   - Specifies conditions to validate that a particular aspect of the system works correctly.


## Defining Sprints 📅

A Sprint(also known as Iteration in Azure DevOps) is the amount of time we have to complete our tasks. Sprints help keep us focused. At the end, we can have a short retrospective meeting to share what we've accomplished. After that, we can plan the next one.
**A sprint is typically two to four weeks long**.

### Acceptance Criteria

**Acceptance criteria** in Scrum are conditions or requirements that a work item must meet to be considered complete. Meeting these criteria indicates that the work has been successfully done and can be accepted. It should clearly define when a work item will be considered as **done**.

## Important member of Agile/Scrum 🕵️‍♂️

**Various parties play distinct roles in the development process in Scrum or Agile methodologies. Here are the key stakeholders:**

**Product Owner:** The product owner represents the customer and defines the product's requirements. The owner is responsible for prioritizing the backlog and ensuring the development team works on the most valuable features.

**Scrum Master:** Facilitates the Scrum process and ensures that the team follows the agreed-upon rules and practices. The Scrum Master acts as a coach, removing impediments and helping the team continuously improve also facilitates retrospective meetings and helps the team with any blockers. The goal of a retrospective meeting is to identify 
  - what went well
  - what could be improved
  - and planning adjustments for the next sprint.

**Development Team:** This cross-functional group is responsible for delivering a potentially shippable product increment at the end of each sprint. The team self-organizes and collaborates to achieve the sprint goals.

**Stakeholders:** Individuals or groups interested in the project or product. They provide input feedback and may attend sprint reviews and demos to assess progress. Stakeholders could include customers, end-users, managers, or other teams.

**Scrum Team:** This encompasses the Product Owner, Scrum Master, and Development Team, working together to deliver a product increment.

**Customers/Users:** The ultimate product or service consumers. Their needs and feedback are crucial for shaping the product and ensuring it meets user requirements.

**Management:** Leadership and management teams may be involved to support the Scrum Team, remove organizational impediments, and align the project with overall business goals.

**External Vendors/Partners:** External entities may sometimes be involved, such as vendors providing specific components or services that integrate into the project.

It's important to note that effective communication and collaboration among these parties are fundamental to the success of Agile or Scrum projects. Roles and responsibilities may vary depending on the Agile framework or methodology used.

## References:

https://medium.com/@piyush.sachdeva055/azure-boards-and-agile-project-management-afe2a7029578

