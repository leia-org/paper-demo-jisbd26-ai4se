# *Learning Enabling Intelligent Assistants for Software Engineering Training* - Supplementary material

This repository contains the supplementary material of the paper entitled "Learning Enabling Intelligent Assistants for Software Engineering Training", submitted to JISBD 2026.

## 🤖  **LEIA Class Diagram Modeling**

**LEIA** (Learning-Enabling Intelligent Assistant) is an AI-powered tool designed to simulate realistic process domain expert interviews for training students to gather the information needed to build an accurate process model or diagram classes. In this article we will discuss conceptual modeling skills that can be trained using it.

## 🎥 Video

🔗 Link to the [video](https://www.youtube.com/watch?v=ntK06DXiK6o) that screencasts and demonstrates the tool. 

## 🧪 User trial

Feel free to test the tool by your self [here](https://pre.workbench.leia.ovh/?email=_test_dm2512&code=RMJCVVJ1025HR0YMH). You will be redirected to a page using both a test email and code. Start the conversation and try to speak with the agent in order to model the diagram. Once you feel ready to go, model it in mermaid using any editor or the given one. When finished, just send the solution.

In this exercise you will act as an interviewer to extract the requisites for a festival access control and cashless payment management platform. You will interact with Ada Lovelace, which is an AI Agent designed to act as festival operations and guests-services manager. The interview will take place in LEIA platform. Use English to communiacte with her, and try to use your own voice for a better UX. Your goal is to model a Class Diagram using mermaid sintax, which will correspond to the database conceptual model needed by the app. You will have the oportunity to do that once you feel that you have finished with your interview. In case you are not familiar with mermaid, there is an example class diagram so you avoid starting from zero. Good luck and enjoy yourself. 

* **<a href="https://pre.workbench.leia.ovh/?email=_test_dm2512&code=RMJCVVJ1025HR0YMH" target="_blank">Demo Link</a>** to the interview exercise. 
* **Exercise Code**: RMJCVVJ1025HR0YMH
* **<a href="https://pre.workbench.leia.ovh/spectate/69a96a43fef1617ef502b25d?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzZXNzaW9uSWQiOiI2OWE5NmE0M2ZlZjE2MTdlZjUwMmIyNWQiLCJ0eXBlIjoic3BlY3RhdGUiLCJyZXBsaWNhdGlvbklkIjoiNjkyODkwZGUxMzA3MGM2MTlmYzkyZWVhIiwiaWF0IjoxNzcyNzEyMDI4LCJleHAiOjE4MDQyNDgwMjh9.fQjAeNfXwC70_GcmNjW-qrX_qO3Qz72gZ6dNaRH40XA" target="_blank">Interview example</a>** for this exercise.

Here you will find the solution for the exercise. However, you will also find it at the end of your evaluation process once you submit your solution

![Exercise solution](process-exercises/ticket-manager/solution.svg)


## 📝 List of other available exercises

In order to try the BPM-LEIA, which is another tool to practice BPM skills, we already have developed the following examples that correspond with exercises present in the book **Fundamentals of Business Process Management** [[1]]([README.md#-references). [[2]]([README.md#-references])

### Assessing loan application process (*Exercise 3.2, page 84. Process model solution, page 109.*)
* **<a href="https://workbench.leia.ovh?email=_test_b25&code=RMCFIG25GZ3NKRNUH" target="_blank">Demo Link</a>** to the interview exercise on the _loan application process_. 
* **Exercise Code**: RMCFIG25GZ3NKRNUH
* **Process**: Assessing loan application process

    ![Assessing loan application process in BPMN](process-exercises/assessing-loan-application/assessing-loan-application-process-model.png)

    A loan application is approved if it passes two checks: (i) the applicant’s loan risk assessment, done automatically by a system, and (ii) the appraisal of the property for which the loan has been asked, carried out by a property appraiser. The risk assessment requires a credit history check on the applicant, which is performed by a financial officer. Once both the loan risk assessment and the property appraisal have been performed, a loan officer can assess the applicant’s eligibility. If the applicant is not eligible, the application is rejected, otherwise the acceptance pack is prepared and sent to the applicant.



### Order fulfillment process (*Example 3.4, solution in Figure 3.6, page 83.*)

* **<a href="https://workbench.leia.ovh?email=_test_b25&code=RMCEHF59FZAUNSP5O" target="_blank">Demo Link</a>** to the interview exercise on the _order fulfillment process_. 
* **Exercise Code**: RMCEHF59FZAUNSP5O
* **Process**: Order fulfillment process

    ![Order fulfillment process in BPMN](process-exercises/order-fulfillment/order-fulfillment-process-model.PNG)

    The order fulfillment process starts whenever a purchase order has been received from a customer. The first activity that is carried out is checking if the product is in stock, otherwise the process completes by rejecting the order. Further, if the product is in stock, the product is requested from the warehouse and the order is  confirmed. Afterwards, the requested product is shipped (after the shipment address is received so that the product can be shipped to the customer) while the invoice is emitted and the payment is received. Afterwards, only when the shipment is completed and the payment has been received, the order is archived and the process completes.



### Order-to-cash process (*Example 3.6, solution in Figure 3.12, page 90.*)

* **<a href="https://workbench.leia.ovh?email=_test_b25&code=RMCFPP2K7QUKS58CC" target="_blank">Demo Link</a>** to the interview exercise on the _order-to-cash process_. 
* **Exercise Code**: RMCFPP2K7QUKS58CC
* **Process**: Order-to-cash process

    ![Order-to-Cash process in BPMN](process-exercises/order-to-cash/order-to-cash-process-model.png)

    The order fulfillment process starts whenever a purchase order has been received from a customer. If the product requested is not in stock, it needs to be manufactured before the order handling can continue. To manufacture a product, the required raw materials have to be ordered. Two preferred suppliers provide different types of raw materials. Depending on the product to be manufactured, raw materials may be ordered from either Supplier 1 or Supplier 2, or from both. Once the raw materials are available, the product can be manufactured and the order can be confirmed. On the other hand, if the product is in stock, it is retrieved from the warehouse before confirming the order. In either case, the process continues normally and the order is  confirmed. Afterwards, the requested product is shipped (after the shipment address is received so that the product can be shipped to the customer) while the invoice is emitted and the payment is received. Afterwards, only when the shipment is completed and the payment has been received, the order is archived and the process completes.



### ISP billing process (*Exercise 4.5, page 125. Process model solution, page 143.*)

* **<a href="https://workbench.leia.ovh?email=_test_b25&code=RMCHR18X9DBGERCO5" target="_blank">Demo Link</a>** to the interview exercise on the _internet service provider billing process_. 
* **Exercise Code**: RMCHR18X9DBGERCO5
* **Process**: Internet service provider billing process

    ![Internet service provider billing process in BPMN](process-exercises/isp-billing/isp-billing-process-model.png)

    An Internet Service Provider's (ISP) billing process begins when the ISP sends an invoice by email to the customer on the first working day of each month (Day 1). On Day 7, the customer has the full outstanding amount automatically debited from its bank account. If an automatic transaction fails for any reason, the customer is notified on Day 8. On Day 9, the transaction that failed on Day 7 is re-attempted. If it fails again, on Day 10 a late fee is charged to the customer’s bank account. At this stage, the automatic payment is no longer attempted. On Day 14, the Internet service is suspended until payment is received. If the payment is still outstanding on Day 30, the account is closed and a disconnection fee is applied. A debt-recovery procedure is then started.

## ✍️ Authors

José Antonio Parejo<sup>1</sup>
<br>Pablo Fernández<sup>1</sup>
<br>Daniel Galván<sup>1</sup>

_Affiliations:_
<br><sup>1</sup> SCORE Lab, Universidad of Sevilla, Sevilla, Spain

## 📖 References

\[1\] Dumas, M., La Rosa, M., Mendling, J., & Reijers, H. A. (2018). Fundamentals of Business Process Management (2nd ed.). Springer

\[2\] The extra examples were originally published [here](https://github.com/leia-org/paper-demo-bpm25) for Bedilia Estrada-Torres, José Antonio Parejo, Armando Fox and Pablo Fernandez (2025). A Training Framework for BPM Modeling Interviews
Based on LLM Assistants.

<hr>
