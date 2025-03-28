---
layout: minimal
title: "🧮 Grading: Readings and Sample Rubric Creation"
---

# 🧮 Grading: Readings and Sample Rubric Creation
{:.no_toc}

<!-- <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script> -->
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3.0.1/es5/tex-mml-chtml.js"></script>

### Reading

First, complete the following three readings:
- Goodrich, [Understanding Rubrics](https://www.ascd.org/el/articles/understanding-rubrics).
- [Grader Evaluation of Student Work](https://drive.google.com/file/d/1lXkv-faD79K14HXdM8xbExKzXtEVIh81/view).
- [Gradescope's Grading Submissions guide](https://help.gradescope.com/article/5uxa8ht1a2-instructor-assignment-grade-submissions).

---

### Sample Grading (due Tuesday, April 30th)

Now, you'll grade a math solution, like the kinds you'd see in DSC 40A (in fact, it's adapted from a real 40A homework problem from a few years ago). A rubric isn't provided for you – you'll have to create it yourself. To submit your work, answer the questions in the Gradescope form below.

[Submit here by Tuesday, April 30th](https://www.gradescope.com/courses/759123/assignments/4407023/){: .btn .btn-purple }

You may wonder why you're being asked to grade a math problem despite not tutoring for DSC 40A or DSC 40B. The answer is that the process of creating a rubric is quite similar regardless of the medium!

---

Suppose you're operating a fruit stand near La Jolla Cove. Your stand only accepts cash, so you don't have access to digital receipts of all of your transactions.

**Part A (4 points)**

You want to keep track of the mean transaction price so far during the day. Instead of writing down the price of each transaction and re-calculating the mean every time someone makes a purchase, you want to come up with a way to only keep track of the mean transaction price. Let $$x_i$$ represent the price of the $$i$$th transaction (e.g. the 5th transaction of the day is $$x_5$$). We define
$$\mu_n$$ to be the mean of the first $$n$$ transactions; that is, $$\mu_n = \frac{1}{n} \sum_{i=1}^n x_i$$.

Determine a formula for $$\mu_{n+1}$$ that only uses the variables $$\mu_n$$, $$n$$, and $$x_{n+1}$$. (Hint: Start by writing out the definition of $$\mu_{n+1}$$.)

**Part B (1 point)**

Why does the above result imply that you don't need to store the values of all transactions individually?

**Part C (2 points)**

So far, you've sold 7 items and the mean transaction price (including the 7th item) is \$12. How much would your **next** transaction price have to be in order for your new mean transaction price to be \$14?

---

We're not going to provide you with the solution or the rubric (though feel free to message on Slack if you're unsure of the answer). What we have provided you with below are three (real) student solutions to all three parts. Your job is to create a rubric for all three parts and score all three submissions using your rubric. Specific formatting details are provided in the Gradescope submission form.

When crafting your rubric, you should assume that students are required to show their work, and not just provide an answer.

<details markdown="block">
<summary>Student submission 1</summary>

<center><img src="https://dsc-courses.github.io/dsc95-2023-sp/weeks/images/student-1.png" width="50%"></center>

</details>

<details markdown="block">
<summary>Student submission 2</summary>

<center><img src="https://dsc-courses.github.io/dsc95-2023-sp/weeks/images/student-2.png" width="50%"></center>

</details>

<details markdown="block">
<summary>Student submission 3</summary>

<center><img src="https://dsc-courses.github.io/dsc95-2023-sp/weeks/images/student-3.png" width="50%"></center>

</details>
