BANK MANAGEMENT SYSTEM

Context:
With the rapidly expanding technology and customer group, data has become a gem in nearly every field. Especially in the banking sector a reliable, quick and durable Data management is must. This calls for the need to digitalize all the data including everything from offline transactions in bank, to various applications from customer side, the bank investments on management side, and employee details on the administrative side. Also substituting papers and going paperless is always encouraged as data is not lost or ill-practised. Lastly, in a age where nearly everything can be done from the comfort of own's house, customers still have to visit bank branches in many banks for various operations.

Our Project:
We have made an attempt to resolve the above issues so to enhance the data-flow between the clients and the bank, and within the bank. For this we have designed a Rich Database with neccessary level of security and authorization. This database is then supported with a GUI using a web-application. The Customer of the Bank can use this user-friendly interface to perform various operations. Also the employees of the bank are granted with various functionalities and privilages according to their roles.

Description:

Customer-Features:
Breif description of the functionalities of the customer-user:
1.Register new user   :   Gives access to use the web-interface and all subsequent functionalities, can create with unique PAN number.
2.Create new Account  :   Create a Saving, Current, Buisness account from home by submitting neccesary documents in pdf format.
3.Transfer Money      :   Transfer money instantaneously to any account in our bank, or using RTGS/NEFT request in any other bank in limited time.
4.Check Balance       :   Check balance of any account registered with your customer_id.
5.Get Statement       :   Get a statement in a download-able format of your previous transactions(last 3 months).
6.Apply for loan      :   Upload the neccessary documents and apply for loan online.
7.Check Loan Status   :   Veiw all your active loans, pending loans and the denied loans with reason of refusal.
8.Feedback/Complaint  :   Write a feedback or complaint directly in our app instead of mailing or messaging.
9.Get Information     :   Get the ongoing interest rates, and any changes in policies or other announcments from the bank.

Admin-Features:
Every Branch will have a Admin and the branch will be distinguised using a unique IFSC code.
Breif functinalities for the ADMIN:
1.Employee Details      :       Admin can see the details of every employee workin in his branch.
2.Add a Employee        :       Add a new employee with given role.
3.Remove a Employee     :       Remove a employee from bank so he will no longer be able to log-in as employee.
4.Edit Employee Details :       Ability to change employee details.
5.Money Amount          :       See the money in the bank and the total money leased on loan.
6.Update Interest Rates :       Update the rate of interest of loans and FD's, also make some announcements.

Banker-Features:
Banker will be able to veiw all the loan applications to the branch in which he is working.
Appropriately after analyzing the documents of the apllication he can approve or deny a loan optionally with the reason of refusal (if denied).

Cashier-Features:
He has the previlage to perform transaction in account, which will be requested by customer in offline by filling a slip.

Customer_executive-features:
HE will be able to veiw all the feedbacks/complaints send by the customers and has the function to reply to them.

Transaction-Reveiwer:
He will receive the requests for transfering money to other(diiferent) bank's account, which he can do by RTGS/NEFT, and click done once completed.

Main-Focus:
1.Maintaining the employee responsible for each task (replying to particular complain, approving/denying loan, transactions) along with the date and time of action so as to maintain accountability. This can also be used later for assessing the employee performance.
2.All the customer actions are stored with a time-stamp, so in case of any mal-practice or false claim the bank is ready with the details.

OTHER HIGHLIGHTS:
1.Mail OTP verification at the time of registration so as to make sure the bearing of mail, number is using them.
2.Alert Mails when any offline transaction are done by the cashier, so as to make sure the person knows of them.
3.Response to Feedback and complains are automatically mailed to the customer once a customer-executive responds them.
4.Use of transaction and rollbacks throughout the code so as to maintain the integrity and consistency of the database.
5.Two-factor authentiacation to customers using a password to sign-in and account passwords to do various functions.
6.Similar 2-factor security to employees and admin.
7.Storing of the application documents securely on the server.
8.Secure in the sense that no employee including Admin has any access to database or any un-neccessary privilages.

Technology Used:
1.MYSQL database.
2.Flask -python.
3.Flask -mail to send mails.
4.OS module to interact with server OS.
5.Sessions to store cookies.
6.HTML, CSS, Jquery(Javascript).

