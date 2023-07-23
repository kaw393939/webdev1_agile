# Unit Overview - Hands-On Agile Development

In the realm of software development, agility is more than a buzzword; it's a methodology, a mindset, and for many teams, a lifeline. To understand the depth and breadth of Agile, one must journey back to the 1990s when software development was notoriously seen as slow and error-prone. Fast forward to 2001, a group of seventeen developers convened and birthed the **Agile Manifesto**. They envisioned a world where software could be delivered frequently, with a focus on collaboration and responding to change.

Today's Agile is not merely about iterative development but encompasses a holistic approach involving various roles, tools, and principles. The concept of **Arrange, Act, Assert (AAA)** testing, for instance, has revolutionized how we validate software. It simplifies test design into three clear steps, ensuring both clarity and thoroughness.

Enter tools like **Playwright**, a robust end-to-end testing solution. With Playwright, testing mirrors actual user scenarios, ensuring software doesn't just work, but works as the user expects. This focus on user-centric testing aligns beautifully with Agile's user story emphasis.

Speaking of tools, **NextJS** has emerged as a premier React framework, offering both developers and users a faster, SEO-optimized web experience. In this assignment, you'll get to dive deep into NextJS, seeing firsthand its benefits.

But development and testing are just pieces of the puzzle. **DevOps**, a culture of collaboration between development and IT operations, emphasizes the need for continuous integration and delivery. Tools like **GitHub Actions** fit snugly into this paradigm, automating workflows and ensuring consistent product quality.

Which brings us to **Quality Assurance (QA)**. Beyond just 'testing', QA is about ensuring standards. It's a proactive approach, identifying potential pitfalls before they become major issues. 

As you embark on this assignment, you're not just creating a simple web page. You're stepping into various roles: 

- The **Product Manager**, crafting user stories and defining product needs.
- The **Developer**, translating these needs into functional software.
- The **QA Specialist**, ensuring every feature works as expected.
- The **DevOps Engineer**, streamlining the development workflow with automation.

This assignment might appear basic, but it embodies the essence of modern software delivery. Master it, and you'll gain insights into multiple facets of the software industry, preparing you for diverse roles and challenges.
## Resources 

### General Required Readings - YOU REALLY NEED TO READ THIS
- [Agile Manifesto](https://agilemanifesto.org/iso/en/manifesto.html) - Do some research on the people that signed it they are legends and key names known by software professionals.  

- [Continuous Integration - Martine Fowler](https://martinfowler.com/articles/continuousIntegration.html) Basically this is the founding document of why DevOps exists and how software is made.

- [Google and Automated Testing Case Study](https://itrevolution.com/articles/case-study-automated-testing-google/)

- [Arrange, Act, and Automated Assert Testing Pattern](https://www.qawolf.com/blog/intro-to-aaa)

### General Required Videos - YOU REALLY NEED TO WATCH THESE

- [Agile Overview in 5 minutes](https://www.youtube.com/watch?v=1iccpf2eN1Q)
- [Agile and Automated Testing](https://www.youtube.com/watch?v=t6GgTWlkhXw&t=13s)
- [Agile and Devops](https://www.youtube.com/watch?v=kBKuXEBP7ho)
- [Agile User Stories and Story Points Simple Explanation](https://www.youtube.com/watch?v=ogV2r9579WI)
- [How to write User Stories](https://www.youtube.com/watch?v=Fw98L-kcRpc)
- [Acceptance Criteria](https://www.youtube.com/watch?v=DavPyEFeEFw)
- [CI/CD and Test Driven Development Explained with Facts and Case studies really important, its what all of this is about really](https://www.youtube.com/watch?v=llaUBH5oayw)
- [Test Drivin Development (TDD) and Agile](https://www.youtube.com/watch?v=uGaNkTahrIw)
- [Playwright - Watch The Whole 4 video Playlist](https://www.youtube.com/watch?v=Xz6lhEzgI5I&list=PLQ6Buerc008dhme8fC80zmhohqpkA0aXI)
- [Setting Up GitHub for Project Managmement](https://www.youtube.com/watch?v=YVFa5VljCDY)
- [Setting Up GitHub Actions Basics](https://www.youtube.com/watch?v=mFFXuXjVgkU&t=67s)
- [Learn GitHub Actions 90 MInutes to DevOps fame and fortune $$](https://www.youtube.com/watch?v=TLB5MY9BBa4)

#### Additional Resources:

-  [Comprehensive Resource for Agile produced by Atlasian that makes Jira](https://www.atlassian.com/agile/project-management/user-stories) - You need to really know this to work in software today, it would be like trying to play baseball and  never saw the game played.  Jira is major project managment software used industry and you will probably use it one day and this is really a great one stop shop to explain a lot of ideas.  I would read all of the links in the left hand side, so you have the vocabulary to impress on an interview and not get lost in a meeting.

- [Comprehensive Guide on Playwright wiith TypeScript](https://www.lambdatest.com/blog/playwright-end-to-end-testing/)- You probably need to read this because it does a good job explaining typescript in general and a bunch of different ways to use Playwright.

### Templates
- [User Story and Acceptance Template](userstory_acceptance_template.md)


## Assignment Instructions



To streamline and enhance this development process, you'll employ GitHub issues. These issues will act as tickets for each feature, ensuring a transparent workflow. Here's how:

- **Open Issues for Each Task**: Each requirement, like the "Hello Professor" heading, gets its own issue.
- **Label Appropriately**: Use labels like 'feature', 'documentation', or custom labels like 'Technical Feature' to categorize issues.
- **Assign and Review**: Designate an assignee for each issue. Specify reviewers for the eventual code.
- **Milestones**: Group related issues under milestones like "Homepage Features".
- **Document Progress**: Within issues, maintain a record of steps, troubleshooting, or snippets related to that feature.
- **Link PRs to Issues**: Each pull request should be linked to its respective issue for clarity.
- **Checklists for Complexity**: Break down multifaceted issues into manageable task lists within the issue itself.
- **Automate with Actions**: Use GitHub Actions for tasks like auto-closing issues when the linked PR is merged.
- **Discussion Threads**: Use the issue's comment section for feedback, discussions, or clarifications.
- **Reference and Close via Commits**: Use commit messages like "Fixed #123" to reference and potentially close related issues.

Remember to create a branch for each step, push to GitHub, open a pull request, review, merge, and then update locally. Document each step in the GitHub wiki of your repository.
### Required Features

**Overview** Create one GitHub Issue for each feature.  Create 2 labels (technical & user) to categorize your issues, assign the task to yourself and see what notificatiion you receive in your email.  Create **Two**  milestones (progress towards a goal) such as a milestone for the intial technical setup features 1-3 and a milestone for the 2 user features, add any information you find helpful to your issues as you go, link thhe pull request to the issue, check out using the discussion feature, and use commit messages to close issues. 

## **Technical Feature 1: NextJS Setup** 



**Objective:** Initialize a single-page NextJS website.

1. **Task:**  
   - Compose a technical user story detailing the need for a NextJS website with one initial page.
      - **Read** [Writing User Stories](https://www.altexsoft.com/blog/user-stories/)
   
2. **Task:**  
   - Draft acceptance criteria to validate that the NextJS site runs smoothly and is primed for additional development.

   - **Read** [Writing Acceptance Criteria](https://www.altexsoft.com/blog/business/acceptance-criteria-purposes-formats-and-best-practices/)

3. **Task:**  
   - Establish a blank homepage using NextJS within the project repository.
   - **Read** [NextJS Tutorial](https://nextjs.org/learn/basics/create-nextjs-app)

---

## **Technical Feature 2: Playwright Integration** 

**Objective:** Incorporate Playwright for automated project testing.

1. **Task:**  
   - Construct a technical user story outlining a developer's need for Playwright to automate project testing.

2. **Task:**  
   - Formulate acceptance criteria to ascertain that the site returns a 200 status code when the root ("/") route is accessed.

3. **Task:**  
   - Integrate Playwright into the project and devise your inaugural test employing the Arrange, Act, Assert (AAA) testing approach.
   - **Read** [How to Install PlayWriight](https://debbie.codes/blog/getting-started-with-playwright-testing/)
   - **Read** [How to write PlayWright Tests](https://www.lambdatest.com/blog/playwright-end-to-end-testing/)
   - **Reference** [Playwright Reference](https://playwright.dev/docs/intro)  - You need this to find the reference for [Locators](https://playwright.dev/docs/locators) <-how you target HTML and [Assertions](https://playwright.dev/docs/test-assertions) <- How you test.  You also need to read and watch the video about the [UI mode](https://playwright.dev/docs/test-ui-mode), [GitHub action](https://playwright.dev/docs/ci-intro), [Tracer View](https://playwright.dev/docs/trace-viewer-intro), [Test Generator](https://playwright.dev/docs/codegen-intro), the [Best practices](https://playwright.dev/docs/best-practices), and [Configuration](https://playwright.dev/docs/test-configuration).  

---

## **Technical Feature 3: GitHub Actions Integration** 

**Objective:** Ensure Playwright tests are successful before merging pull requests using GitHub Actions.

1. **Task:**  
   - Pen a technical user story expressing the necessity for Playwright tests to succeed prior to merging any pull request.

2. **Task:**  
   - Draft acceptance criteria that delineate how to verify the successful completion of the user story.

3. **Task:**  
   - Incorporate the GitHub Action as specified in your user story and validate its functionality using your acceptance criteria.
   - **Read**[Great Article on GitHub actions](https://playwright.dev/docs/test-configuration)

## **Technical Feature 4: GitHub Actions and Deployment Integration** 

**Objective:** Ensure Playwright tests pass, and if successful, deploy the site to GitHub Pages or Vercel when the master branch is updated.

1. **Task:**  
   - Compose a technical user story detailing the need for Playwright tests to pass before deploying updates to the master branch. Also, explain the requirement to auto-deploy to GitHub Pages or Vercel upon successful test results and master branch update.

2. **Task:**  
   - Define acceptance criteria that clarify the process of verifying both successful test execution and successful deployment to GitHub Pages or Vercel.

3. **Task:**  
   - Set up a GitHub Action as detailed in your user story, ensuring it checks for Playwright test success and triggers a deployment to GitHub Pages or Vercel. Subsequently, validate its implementation with your acceptance criteria.

---

## **User Feature 1: "Web Page Title"** 

**Objective:** Implement a "Hello Professor" web page title.

1. **Task:**  
   - Craft a user story specifying the requirement for a "Hello Professor" web page title.

2. **Task:**  
   - Define acceptance criteria for the "Hello Professor" web page title.

3. **Task:**  
   - Design Playwright tests, applying the AAA testing technique.

4. **Task:**  
   - Embed the "Hello Professor" web page title using NextJS and ensure it passes the Playwright tests.

---

## **User Feature 2: Display "Hello Professor" as an H1 Title** 

**Objective:** Feature "Hello Professor" in large bold font using an h1 tag.

1. **Task:**  
   - Generate a user story emphasizing the need to display "Hello Professor" as a prominent h1 title.

2. **Task:**  
   - Create acceptance criteria to validate the presence and correct formatting of the "Hello Professor" h1 tag.

3. **Task:**  
   - Design a Figma mockup showcasing the homepage with "Hello Professor" in large bold font.

4. **Task:**  
   - Formulate Playwright tests based on the AAA testing principle.

5. **Task:**  
   - Implement the "Hello Professor" h1 title in NextJS and confirm it aligns with the Playwright tests.

### Grading

Each of the above 5 features is worth 20 points in the assignment, this is not an all or nothing assignment.


**Note:** You might want to challenge yourself to figure out a method for testing step #9 by automaticly running playwright tests, after deploymnet but having a specific test to go to the site's deployed URL.



Your task is to implement this with the NextJS project provided, write Playwright tests to check that both requirements are met, and 

**Topics**
- Agile Documentation
- Acceptance Testing Documentation
- AAA Testing Pattern
- Devops (GitHub Workflows)
- Playwright end-to-end (e2e) testing

## Workflow 


