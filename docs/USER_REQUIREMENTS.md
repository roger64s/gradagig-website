# Gradagig Website — User Requirements

## 2026-08-09

- Create a modern, professional, and accessible landing page for Gradagig using Tailwind CSS.
- Use the Grad-a-gig logo from the Docs folder and match the website colors to the logo.
- Add a clear, styled "Product Demos" section that includes:
  - A **MOC Workflow Demo** card with a button to open the MOC dashboard.
  - An explanation that the MOC dashboard is an outcome-based workflow for transparent project tracking.
- Update the team titles so that:
  - Vaideeswaran and Rajiv are listed as **Mentor/Advisor** before their CRO/CTO roles.
  - Srirajan is listed as **Founder**.
- Push the website code to the `gradagig-website` GitHub repository.
- Deploy the website to Vercel.
- The MOC workflow demo should not require any login.
- Add the MOC project to the workspace.
- Improve the MOC demo so it is mobile-friendly, similar to the CRM demo.
- Fix font size issues in the MOC dashboard so it is presentable on mobile.
- Update the website link to point to the correct deployed MOC demo URL.
- Confirm that GitHub and gradagig.com are updated.

## 2026-08-10

- Add the **CodeWithKris** brand and content from the old Gradagig PDF to the new website.
- Use the file `Gradagig_CodewithKris_Short` as content reference.
- Use `Kris_theJumbo_Mascot.png` from the Docs folder as the mascot/logo.
- Preview changes before uploading to the live website.
- Add **CodeWithKris** as a page in the main menu.
- Remove "Built with" or "Technology Partner" references because the product is still in prototyping phase.
- Include content from pages 4–8 of `Gradagig_CodewithKris_Short.pdf`.
- On the landing page, place the CodeWithKris logo next to the Gradagig name.
- Ensure the footer on all pages uses the original Gradagig logo with a black background, not a white background.
- Replace the `Gradagig_Social_Impact_logo.png` in the footer with the original black-background logo across all pages.
- Ensure all images on the CodeWithKris page are fully visible and not cropped at the top or bottom.
- Remove the number "4" from the image where it appears.
- In the "Outcome Based Delivery" section, place the social impact image to the right of the heading, aligned with the text, and sized to match the heading font.
- Include the social impact image on all relevant pages.
- Make the CodeWithKris page consistent with the rest of the site by integrating it as a section instead of a separate HTML page if needed.
- Align all section titles consistently across pages.
- Keep the CodeWithKris logo properly sized and aligned.
- Update GitHub and close the project when changes are complete.
- Create a token-usage summary document and store it in the Docs folder.
- Create a project summary with a pie chart showing percentage of man-hours spent on planning, researching, coding, testing, and rework.
- Create similar summary charts for the MOC Workflow and CRM Automation projects.
- Store all project summaries in their respective Docs folders under `C:\projects\`.
- Push all summary documents to GitHub so they are available on the home computer.

## 2026-08-11

- Add a prominent "Product/Service Demo" section for business clients near the top of the main landing page, above the fold.
- Confirm GitHub and gradagig.com are updated after each change.
- Embed the demo video on the main landing page as a small expandable video instead of linking to a separate page.
- Move the video to the right side of the "Knowledge Based Work..." section.
- Remove the "Join the Cooperative" and "Explore the Model" buttons.
- Replace them with two buttons:
  - **Register your interest**
  - **See Demo** — link to the `#demos` section
- Make sure the "See Demo" link opens the demos section correctly at `https://gradagig.com/#demos`.
- Remove the "Submit Product Backlog" button.
- Ensure each button links to a distinct action.
- Fix the form so it opens when a relevant button is clicked.
- Provide a summary of tokens used with a pie chart for internal tracking.

## 2026-08-13

- Investigate why the gradagig.com website is not loading.
- Fix the registration forms so that client, student, and talent submissions actually send email notifications.
- Send all registration form notifications to `roger.s@gradagig.com`.
- Add a dedicated `/thank-you.html` page that users see after submitting any registration form.

## 2026-08-15

- Add "ZERO RISK" text overlay on top of the video frame in the hero section.
- Style: "ZERO RISK" in gold/yellow bold font, "(SourceCode Escrow)" in white normal font.
- Position the text above the video thumbnail, inside the light teal border area.
- Preview changes locally before committing to GitHub.
- Deploy changes to Vercel and update documentation.
- Add "See Metrics" button in hero section linking to interactive charts page.
- Add "Project Metrics" card to Product Demos section.
- Create interactive Chart.js page (`docs/charts.html`) with:
  - Pie chart for time distribution
  - Bar chart for lines of code by date
  - Stacked bar chart for effort breakdown by category
  - Line chart for hours spent by date
  - Category bar chart for total LOC
  - Data labels showing values on all charts
  - Different colors for each dashboard stat card
- Update PROJECT_SUMMARY.md with:
  - Tab-separated tables for Excel copy-paste
  - Hours and LOC metrics matching HubSpot CRM format
  - Visual charts section
- Preview changes locally first and update GitHub only after an explicit `Close Project` request.
- Keep numeric labels visible on all project-metrics charts, with readable font sizing and contrast.

## 2026-08-17

- Link the “Open CRM Demo” button to `https://crm-demo-ai-worklow.vercel.app/`.
- Add a Blog item to the site navigation and a “Read Blog” hero button beside “See Metrics”.
- Publish the Tata Sons blueprint blog post and link its supporting PDF for visitors to open on the website.
- Center “Zero Risk” in red below the Grad-a-Gig name in the header.

## 2026-08-18

- Remove the Kris the Jumbo logo from the top banner on all pages while keeping the CodeWithKris content available on the homepage.
- Replace “Minorities” with “Students” throughout the website and reduce the hero heading size so it fits mobile screens.
- Format the hero heading into three lines: “Knowledge-Based Work for”, “Persons with Disabilities,”, and “Students and Women” on desktop and mobile.
- Make the hero action buttons compact in both desktop and mobile layouts.
- Rename registration menu and button labels to “Join” throughout the website.
- Shorten the hero action labels to “Demo”, “Metrics”, and “Blog”.
- Remove the duplicate Join links from the desktop and mobile top menus, keeping the top-right Join button.
- Align the desktop navigation closer to the top-right Join button.
- Keep “Cooperative business model inspired by Amul” in both desktop and mobile views.
- On mobile, keep “inspired by Amul” on the second line of the badge.
- Remove the decorative dot before the Amul badge text on desktop and mobile.
- Display only “Earn while you learn” in yellow/gold text wherever it appears in visible page copy.
- Amend the hero supporting copy to emphasize results-based delivery and payment on delivery.
- Keep “AI-assisted” together without a line break in the hero copy.
- Place each donut chart percentage label inside its relevant colored segment and remove the separate legend below it.
- Curve each donut segment label along its segment and use matching segment colors for the label fonts.
- Increase the donut size and label font for easier reading without changing the curved orientation.
- Increase the donut ring thickness to improve visual clarity.
- Match the donut chart labels to the supplied reference image with centered curved text, matching colors, and readable contrast.
- Keep the complete “28% Reliability” label visible inside the coral segment.
- Center the `32% Learning` label within the yellow segment and keep it slightly toward the outer edge without clipping.
- Preview the final website in both desktop and mobile layouts before closing the project.
- Keep daily LOC, hours, and effort metrics updated with estimated values when exact tracking is unavailable.
- Apply the same estimated daily metrics format to Grad-a-Gig, MOC Workflow, CRMAutomation, and all future projects.

