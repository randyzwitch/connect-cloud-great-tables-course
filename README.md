<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Share Great Tables with Quarto and Posit Connect Cloud

<img src="/images/connect-cloud-great-tables.png" width=300 align=right>

_Share your great table with the world in just a few minutes._

</br>
</br>

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
  TBD-step-1-notes.
-->

## Step 1: Create a Quarto doc

_Welcome to "Share Great Tables with Quarto and Posit Cloud Connect"! :wave:_

Our first step is to make a Quarto document to put our table in.

**What is Quarto?**: A Quarto document (.qmd) is a plain-text markdown file that contains 
code chunks written in Python, R, Julia, or Observable. When you render the document, Quarto formats the markdown into a polished report and inserts the output of the code chunks.

Read more about Quarto at [quarto.org](https://quarto.org/). 

### :keyboard: Activity: Make a quarto document

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
  
2. On the < > Code tab in the header menu of your repository, select the **Add file** drop-down and click **Create new file**.

   <img src="/images/create-new-file.png" width="300"/>

4. In the **Name your file...** field, enter `table.qmd`.

5. In the **Enter file contents here** area, copy the following content to your file:

   ```
   ---
   title: "Check this out..."
   format: html
   jupyter: python3
   ---
   
   ```

   <img src="/images/my-quarto-file.png" width="600"/>
   

   Quarto files begin with a YAML header that contains metadata used to render the file. This header begins an empty Quarto doc that can be rendered to HTML and contain executable Python chunks.

7. Click **Commit changes...** in the upper right corner above the contents box. 

   <img src="/images/commit-top-of-page.png" width="600"/>

9. Then click **Commit changes** in the pop up window that appears. This will add your document to the repo.

   <img src="/images/commit-full-screen.png" width="400"/>
   
10. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://forum.posit.co/c/posit-professional-hosted/posit-connect-cloud/67) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
