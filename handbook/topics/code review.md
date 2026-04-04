# Code Reviews


Code reviews are a process where **developers examine each other’s code before it is merged into the main branch.** While they are often associated with finding bugs, their role is much broader. Code reviews help **ensure consistency** across the codebase, **improve readability**, and make it **easier for the team to maintain and build on existing work**.

In our team, where different developers have been working in different ways, code reviews are an important step toward creating **a more consistent and reliable development process**. They act as a checkpoint before code reaches production, helping to **reduce defects** and **improve overall quality**.

---

#### Why Code Reviews Matter

- Catch bugs early before they reach production  
- Improve code quality and readability  
- Ensure consistent standards across the team  
- Encourage knowledge sharing  
- Reduce dependency on individual developers  

Code reviews should be seen as part of the development process, not an optional extra.

---

#### Key Guidelines (Best Practices)

- <ins>Review for overall quality, not just bugs:</ins>
A good review looks at more than whether the code works. It should also consider:

    - Is the code easy to understand?  
    - Is the structure clear and logical?  
    - Will it be easy to maintain in the future?  
    
    Reviewers should also check that appropriate tests are included.

<br>

- <ins>Keep pull requests small:</ins>
Smaller pull requests are easier to review and understand. They:

    - Reduce the chance of missing issues  
    - Speed up the review process  
    - Make feedback more focused  

    Large changes are more likely to be skimmed or delayed.

<br>

- <ins>Follow team standards, not personal preference:</ins>
Code reviews should be based on agreed standards rather than individual opinions.  
To avoid unnecessary debates:

    - Use linters and formatters for style  
    - Agree on conventions as a team  
    - Focus feedback on meaningful issues  

<br>

- <ins>Prioritise timely reviews:</ins>
Reviews should be done quickly to avoid blocking progress. As a guideline:

    - Aim to review within 24 hours  
    - Treat reviewing as part of normal work  
    - Avoid letting pull requests sit for long periods  
    
    Delays in reviews can slow down the entire team.

<br>

- <ins>Use reviews as a learning opportunity:</ins>
Code reviews are a good way to share knowledge:

    - Explain why changes are needed  
    - Share better approaches or patterns  
    - Help less experienced developers improve  

    This helps build a stronger and more consistent team over time.

<br>

- <ins>Use a simple checklist:</ins>
A structured approach makes reviews more effective. Reviewers should check:

    - Correctness – does the code work as expected?  
    - Readability – is it easy to understand?  
    - Maintainability – will it be easy to modify later?  
    - Testing – are there sufficient tests?  
    - Security – are there any obvious risks?  

---

#### Bad Practices to Avoid

- <ins>Treating code reviews as optional:</ins> Skipping reviews leads to inconsistent code and more bugs reaching production.

<br>

- <ins>Large, complex pull requests:</ins>
Big changes are harder to review properly and often lead to missed issues or delays.

<br>

- <ins>Slow or ignored reviews:</ins>
When reviews take too long:

    - Developers are blocked  
    - Work piles up  
    - Team productivity drops 

<br>

- <ins>Focusing on minor issues (nitpicking):</ins>
Spending too much time on small style issues can:

    - Slow down the process  
    - Frustrate developers  
    - Distract from more important problems 

<br>

- <ins>Approving without proper review:</ins>
Approving code without fully understanding it defeats the purpose of the process and increases the risk of defects.

<br>

- <ins>Lack of clear standards:</ins>
If the team does not agree on coding standards, reviews become inconsistent and can lead to unnecessary disagreements.

---

#### Code Review Workflow 
***A typical code review process looks like this:***

1. Developer creates a pull request  

2. Reviewer is assigned  

3. Code is reviewed using a checklist  

4. Feedback is given  

5. Changes are made  

6. Code is approved  

7. Changes are merged into the main branch  
 
 ---

#### Common Themes from Research 

Across the articles and discussions reviewed, several common points appeared:

##### 1. Code reviews are about more than finding bugs 

They play a key role in improving code quality, maintainability, and consistency. They also help prevent future issues, not just fix current ones. 

 

##### 2. Collaboration is a major benefit 

Code reviews encourage communication and shared ownership of the codebase. This reduces reliance on individual developers and helps spread knowledge across the team. 

 

##### 3. Poorly managed reviews can slow teams down 

Many developers highlighted delays as a common problem. When reviews take too long or are not prioritised, they can become a bottleneck. 

 

##### 4. Clear standards improve the process 

Teams that define clear expectations for code reviews tend to have more efficient and consistent outcomes. 

 

##### 5. Human factors matter 

The tone and approach used in reviews can affect team morale. Reviews should be constructive and respectful, not overly critical. 

---

#### References 

[Code Institute - The Importance of Code Reviews](https://codeinstitute.net/global/blog/the-importance-of-code-reviews/)  
  
[FinTech Weekly - Why Every Development Team Needs a Code Review Strategy](https://www.fintechweekly.com/magazine/articles/why-every-development-team-needs-a-code-review-strategy )   

[Browser Stack - Understanding Code Review and its Benefits](https://www.browserstack.com/guide/code-review-benefits )   

[Reddit - Three ways to explain the benefits of code reviews to a non-technical audience](https://www.reddit.com/r/ExperiencedDevs/comments/vcqh68/three_ways_to_explain_the_benefits_of_code/ )  
 

[Reddit - Code review taking forever because everyone's busy and reviews get deprioritized, sound familiar?](https://www.reddit.com/r/ExperiencedDevs/comments/1qxf5ws/code_review_taking_forever_because_everyones_busy/)  
  

[Reddit - Opinions on code review](https://www.reddit.com/r/ExperiencedDevs/comments/1mo0q47/opinions_on_code_review/)  
 

 