# Title: Azure Data Factory & Logic Apps Integration: Blob Storage to Data Lake Copy with Validation & Email Notifications
Automate file copying from Azure Blob Storage to Data Lake using Azure Data Factory and Logic Apps. Validate file integrity and send email notifications for invalid files. Enhance data integration with monitoring and logging. An efficient solution for seamless file transfer and error handling.

Key Features:

Azure Data Factory Pipelines: ADF pipelines are created to orchestrate the file copying process from Azure Blob Storage to Azure Data Lake. These pipelines leverage pre-built connectors to interact with Blob Storage and Data Lake.

Validation and Error Handling: The solution incorporates validation logic to determine the validity of files. If a file is valid, it is seamlessly copied to the Data Lake. In the case of an invalid file, an email notification is triggered to inform the concerned individuals, providing them with the necessary details.

Integration with Logic Apps: Logic Apps is integrated into the solution to handle the email notification functionality. It listens for trigger events from Azure Data Factory and executes the email notification workflow when an invalid file is detected.

Monitoring and Logging: The project includes monitoring and logging capabilities to track the execution of Data Factory pipelines and Logic Apps workflows. This provides visibility into the process and aids in troubleshooting and performance optimization.

This GitHub repository serves as a practical demonstration of integrating Azure Data Factory and Logic Apps to automate file copying and error handling scenarios. It provides a foundation for similar projects and can be customized to fit specific business requirements.

By exploring this project, you will gain insights into the seamless integration of Azure Data Factory and Logic Apps, learning how to automate file transfers and handle errors effectively. The provided code, pipelines, and workflows serve as valuable references for building robust data integration solutions.

Feel free to explore, contribute, and adapt this solution to meet your specific needs. Your feedback and suggestions are highly appreciated to enhance the project further.

Start automating your file copying process with confidence using Azure Data Factory and Logic Apps. Happy coding!
