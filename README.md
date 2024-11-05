# Mobile Application
Welcome to the MediPlat Mobile Application, a powerful tool designed to streamline the sales process of medical products using the Kivy and KivyMD frameworks alongside Python. This application is tailored for healthcare professionals, making it easier to manage sales data efficiently.
## Project Overview
In my previous role at a medical product sales company, I noticed a significant challenge: employees spent excessive time filling out Excel files with crucial product information. Each product was identified by a REF number and a Batch/Lot number, and every sale required extensive documentation, including:

Product REF number
Product description
Batch/Lot number
Quantity sold
Customer name
Sale date
This time-consuming process motivated me to develop the MediPlat Mobile Application to simplify and automate these tasks for our sales team.
![Markdown symbol](https://github.com/nikosgri/MediPlat_Mobile_Application/blob/master/charges.png)https://github.com/nikosgri/MediPlat_Mobile_Application/blob/master/charges.png) 
## Application Features
### Real-Time Database Integration
The MediPlat application connects to a real-time Firebase database, securely storing product codes and descriptions in JSON format. Only valid company email addresses can access this database, ensuring data integrity and security.
### User-Friendly Profile Setup
Upon creating a profile, users can quickly generate Excel files by scanning the Data-Matrix QR codes associated with the products. The process is straightforward:

Enter essential details, such as the clinic name, date of sale, and patient name.
Use the camera to scan the QR code, which decodes the GS1-128 structure to identify the product.
If scanning fails, users can manually input product details.
### Seamless Excel File Generation
Once the necessary information is collected, the application automatically generates a uniquely named Excel file for each transaction based on the provided data.
### Effortless Submission to Back Office
Users can easily send the generated Excel file to the appropriate back office for billing. When ready to submit, simply click on the file label, and a pop-up will prompt the user to select a location—Athens or Larisa. The application will then send the file to the designated email address corresponding to the chosen city.
### Enhanced Search Functionality
The application includes a convenient search bar, enabling users to quickly locate specific Excel files, further enhancing usability and efficiency.

## Conclusion
The MediPlat Mobile Application is designed to eliminate the inefficiencies of manual data entry in medical sales, providing a streamlined and user-friendly experience for employees. By automating the sales documentation process, we empower our team to focus more on customer service and less on paperwork.
