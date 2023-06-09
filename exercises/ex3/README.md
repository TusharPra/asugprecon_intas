# Create Business Solution Request  

In this part of the exercise, you are taking the persona of a Business User. As a Business User, you need to create a Business Request for a new interface that needs to be developed. You will be doing so using the Integration Assessment Tool and using the standard default questionnaire provided by SAP.

## Steps for creating Buisness Solution Request

Run through the following steps from the Integration Assesement Tool Landing Page:

1. Select “Request” and then select “Business Solution Request”
<br><img src="/exercises/ex3/images/1.0_Ex3_Create_Request.PNG" width=80% height=80%>

2. Select “Create” – This is to create a new “Business Solution Request”
<br><img src="/exercises/ex3/images/1.1_Ex3_Create_Business_Request.PNG" width=80% height=80%>

3. Enter name of “Business Solution Request”: **Order2Cash_XX** where **XX** stands for your group number
<br><img src="/exercises/ex3/images/1.2_Ex3_Name_Business_Request.PNG" width=40% height=40%> 

4. Enter the information in the fields:
    1. Which master and/or transactional data will be exchanged?: **Customer and O2C Process**
    2. To which business process does your integration scenario belong to?: **Order2Cash**
    3. What is the planned business go-live date?: Pick relevant date from the drop-down. **Dec, 31, 2023**
    4. What is the business criticality of this integration scenario?: **Medium**

    Select "Next Step"
<br><img src="/exercises/ex3/images/1.3_Ex3_General_Request_Information.PNG" width=80% height=80%>

5. Select "Create"
<br><img src="/exercises/ex3/images/1.4_Ex3_Interface_Request_Information.PNG" width=80% height=80%>

6. Enter the Interface Request as below:
    1. Name: **Order2Cash**
    2. Source Application Instance: From drop down select **S4HANA_OP**. **Note:** This is the On-Premise system which was configured earlier
    3. Target Application Instance: From drop down select **C4C**. **Note:** This is the On-Premise system which was configured earlier
    4. Style: “Process Integration”

    Select "Create"<br>
    Then Select "Next Step"
<br><img src="/exercises/ex3/images/1.5_Ex3_Interface_Request_Details_Information.PNG" width=80% height=80%>

7. This is where Business User can upload any Business related documents. This is an optional step

    Select "Done"
<br><img src="/exercises/ex3/images/1.6_Ex3_Attachments_Request_Information.PNG" width=80% height=80%>

8. Select "Submit". This would create a Business Solution Request
<br><img src="/exercises/ex3/images/1.7_Ex3_Submit_Request_Information.PNG" width=80% height=80%>

9. On successful submission of the Business Solution Request, the request goes in **Requirement Analysis**
Select **Requests** to go to the Integration Tool Landing Page
<br><img src="/exercises/ex3/images/1.8_Ex3_Request_Submit_Complete.PNG" width=80% height=80%>
    
## Summary

You should now have created a Business Solution Request.

Now, we create an Interface Request based on the Business Solution Request. Continue to - [Create Interface Request](/exercises/ex4)

