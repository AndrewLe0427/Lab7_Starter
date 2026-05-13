Contributors: Andrew Le, Sahil Dalal

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

---

Option 1: Within a Github action that runs whenever code is pushed

Reason: Because that allows continuous testing when new features are added to ensure that the pushed code always comply with the requirements. Also, it allows automation.

---

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

---

No

Here, a end-to-end test would not be appropriate as end to end tests are aimed at testing the entire user workflow, and UI elements; rather than testing one functions/one part of the logic of an application. In this case, a Unit Test for that function would be more appropriate. 

---




