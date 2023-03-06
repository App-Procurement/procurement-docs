- [Create  Purchase Request](#create-purchase-request)
- [Track  Purchase Request](#Track-purchase-request)
- [Approve Purchase Request](#Approve-purchase-request)
# Create  Purchase Request
<h2>Actor</h2>
<ul>
  <li>Admin</li>
  <li>Approver</li>
  <li>Requestor</li>
</ul>
  <h2>Use Case Description</h2>  
  <p>
  This use case allows the requester to create a new request for products, services, or contracts, attach relevant documents, and submit it for approval. The approver can then review the request and either approve or reject it. 
  </p>
   <h2>Trigger</h2>
  <p>The requester needs to create a new request for a product, service, or contract</p>
  <h2>Pre Condition<h2>
   <ol>
   <li>The requester is logged into the system.</li>
   <li>The requester has the necessary permissions to create a new request.</li>
   <li>The requester has the required information, such as the expected delivery date, department, location, and request type, to create the request.</li>
   </ol>
   <h2>Post Condition</h2>
   <ol>
   <li>If the request is approved, the system will initiate the necessary actions to fulfill the request.</li>
   <li>The user will be able to access the request and track its progress</li>
   <li>If the request is rejected, the requester will receive a notification explaining the reason for rejection.</li>
   </ol>
   <h2>Normal Flow</h2>
   <ol>
   <li>The user clicks on the "Create new request" button, which opens the "New create request" form.</li>
   <li>The user selects the Desired delivery date, department, location, and request type.</li>
   <li>The user enters a note to provide a reason for the request.</li>
    <li>The user clicks on the "Add items" button to browse the internal catalogue and select the required products or services. Alternatively, the user can click on the "Add Custom item" button to manually add a single order line or click on the "Import item" button to import bulk orders through a CSV file.</li>
   <li>The user can click on the "Attach documents" button to upload any relevant documents related to the procurement request.</li>
   <li>Once all the required information is entered, the user clicks on the "Submit" button.</li>
   <li>The status of the request changes from "draft" to "pending," and the request is submitted for approval.</li>
   </ol>
   <h2>Alternative Flow</h2>
   <ol>
   <li>If the approver rejects the request, the user can modify the request based on the feedback provided by the approver and resubmit the request for approval</li>
   <li>If the approver approves the request, the procurement process can continue, and the requested items or services can be procured.</li>
   </ol>

    [Figma Link](https://www.figma.com/proto/UKoZ5CtwRdEfwWAQezbpkz/Synectiks-procurement?page-id=2082%3A6113&node-id=5948%3A18704&viewport=394%2C663%2C0.04&scaling=scale-down-width&starting-point-node-id=5948%3A19947)


# Track Purchase Request

<h2>Actor</h2>
<ul>
  <li>Admin</li>
  <li>Approver</li>
  <li>Requestor</li>
</ul>
  <h2>Use Case Description</h2>  
  <p>
  The user wants to view the details of a specific request to gain more insight into its status and contents.
  </p>
   <h2>Trigger</h2>
  <p>The user clicks on a specific request in the table on the request screen. </p>
  <h2>Pre Condition<h2>
   <ul>
   <li>The user is authenticated and authorized to view the request details.</li>
   </ul>
   <h2>Post Condition</h2>
   <ul>
   <li>The user can view all the information related to the request, including its status, items, attachments, comments, supplier information, and activity logs.</li>
   </ul>
   <h2>Normal Flow</h2>
   <ol>
   <li>The user clicks on a specific request in the table on the request screen.</li>
   <li>The system opens the request details page.</li>
   <li>The user sees the Request No, tags related to that request, and tabs for request overview, attachments, comments, supplier info, and activity logs.</li>
    <li>The user clicks on the request overview tab.</li>
   <li>The system displays the request details, including Requestor name, Location, Delivery Date, Creation Date, request type, department, Item, Final Approver, and total request amount.</li>
   <li>The system displays the Order line item table with the fields Name, Category, supplier, quantity, unit, price, and total cost.</li>
   <li>The user clicks on the attachments tab.</li>
   <li>The system displays all the attachments related to the request in a table with fields like File name, file size, date uploaded, and Uploaded by.</li>
   <li>The user clicks on the comments tab.</li>
   <li>The system displays all the comments related to the request. </li>
   <li>The user clicks on the supplier info tab. </li>
   <li>The system displays the information of the supplier, including Supplier name, Supplier email, Supplier contact, business category, telephone No, and Mailing address. </li>
   <li>The user clicks on the activity logs tab. </li>
   <li>The system displays all the user activities related to the request in a table with fields like User, action, type, and timestamp.</li>
 
   </ol>
   <h2>Alternative Flow</h2>

  <ul>
  <li>4a. If the user wants to view the attachments related to the request, they can skip step 5 and go directly to step 7.</li>
  <li>4b. If the user wants to view the comments related to the request, they can skip step 5 and go directly to step 9.</li>
  <li>4c. If the user wants to view the supplier information related to the request, they can skip step 5 and go directly to step 11.</li>
  <li>4d. If the user wants to view the activity logs related to the request, they can skip step 5 and go directly to step 13.</li>  
  </ul>

   [Figma Link](https://www.figma.com/proto/UKoZ5CtwRdEfwWAQezbpkz/Synectiks-procurement?page-id=2082%3A6113&node-id=5948%3A19947&viewport=394%2C663%2C0.04&scaling=scale-down-width&starting-point-node-id=5948%3A19947)


# Approve Purchase Request
  



