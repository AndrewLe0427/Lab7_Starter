Contributors: Andrew Le, Sahil Dalal

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

---

Option 1: Within a Github action that runs whenever code is pushed

Reason: Because that allows continuous testing when new features are added to ensure that the pushed code always comply with the requirements. Also, it allows automation, so that we don't have to manually check our code after every small change. It also ensures that different people committing to one repository meet certain standards (linting, testing, etc.).

---

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

---

No

Here, a end-to-end test would not be appropriate as end to end tests are aimed at testing the entire user workflow, and UI elements; rather than testing one functions/one part of the logic of an application. In this case, a Unit Test for that function would be more appropriate. 

---

3) What is the difference between navigation and snapshot mode
   
---

Navigation mode analyzes a page after loading, and isn't used in context of the current state; however, snapshot mode analyzes web page in current state, and is able to then find issues after some  state of particular interactions. In short, navigation mode is good for analyzing issues right after loading, snapshot mode is good for identifying targetted issues at certain states.

---

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

---

- Need a lang attribute so that a screen reader can announce the page's text in the correct language.
- Add a meta description to increase SEO
- Reduce chained critical requests to improve page load, and reduce path latency.



