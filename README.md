# Insurance Management System Using MVC in Java

The Insurance Management System (IMS) is a web-based application that allows users to manage their insurance policies. The system provides a centralized location for users to store their policy information, track their claims, and make payments. The IMS also provides users with access to a variety of resources, such as policy documents, claim forms, and customer support information.

The IMS is a comprehensive and user-friendly application that can help users save time and money. The system is easy to use and provides users with a variety of features that can help them manage their insurance policies effectively.

The IMS is a valuable tool for anyone who owns an insurance policy. The system can help users save time and money by providing them with a centralized location to store their policy information, track their claims, and make payments. The IMS also provides users with access to a variety of resources, such as policy documents, claim forms, and customer support information.

Here are some of the features of the IMS:

- Policy management: The IMS allows users to store their policy information, including their policy number, policy type, coverage details, and contact information for their insurance company.
- Claim management: The IMS allows users to track their claims, including the status of their claim, the amount of their claim, and the date their claim was filed.
- Payment management: The IMS allows users to make payments for their insurance premiums.
- Resource center: The IMS provides users with access to a variety of resources, such as policy documents, claim forms, and customer support information.

The IMS is a valuable tool for anyone who owns an insurance policy. The system can help users save time and money by providing them with a centralized location to store their policy information, track their claims, and make payments. The IMS also provides users with access to a variety of resources, such as policy documents, claim forms, and customer support information.

Here are some of the benefits of using the IMS:

- Save time: The IMS can help you save time by providing a centralized location to store your policy information, track your claims, and make payments.
- Save money: The IMS can help you save money by providing you with access to discounts and promotions.
- Peace of mind: The IMS can give you peace of mind knowing that your insurance information is secure and accessible.

If you are looking for a comprehensive and user-friendly insurance management system, the IMS is a great option. The system is easy to use and provides users with a variety of features that can help them manage their insurance policies effectively.

## Requirements

1. IntelliJ IDEA (Ultimate Version) [Install](https://www.jetbrains.com/help/idea/installation-guide.html#toolbox)
2. MySQL Workbench [Install](https://dev.mysql.com/downloads/workbench/)




## Downloading and Running the MVC Application

Follow these step-by-step instructions to download and run the MVC application on IntelliJ IDEA and MySQL Workbench:

1. **Download the ZIP:** Go to the GitHub repository page and click on the "Code" button. From the dropdown menu, select "Download ZIP." This will download a compressed ZIP file containing the repository code to your local machine.

2. **Extract the ZIP File:** Once the ZIP file is downloaded, extract its contents to a desired location on your computer. You can use any extraction tool, such as WinRAR or 7-Zip, to extract the files.

3. **Import the Project:** Launch IntelliJ IDEA and select "Open" from the welcome screen. Navigate to the location where you cloned the repository and choose the project's root directory. Click "Open" to import the project.

4. **Configure the Database:** Before running the application, ensure that you have MySQL Server installed and running on your machine. Open MySQL Workbench and create a new database with a suitable name for your application. The database name that you use here should be the same as the database name that you provide in **applications.properties** file(Check Step 6).

5. **Update Application Configuration:** In the project, locate the application.properties file. Open it and update the following properties according to your MySQL configuration:


```php
# Database Configuration
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost:3306/<database_name>?useSSL=false&serverTimezone=UTC
spring.datasource.username=<database_username>
spring.datasource.password=<database_password>

# Thymeleaf Configuration
spring.thymeleaf.cache=false

# JPA Configuration
spring.jpa.show-sql=true
spring.jpa.hibernate.ddl-auto=update

# Server Configuration
server.port=8080
```
Replace **<database_name>**, **<database_username>**, and **<database_password>** (remove the angular brackets(<>)) with your database's name, username, and password respectively.

6. **Build the Project:** Build the project in IntelliJ IDEA by selecting "Build" from the top menu and then choosing "Build Project." Ensure that the build process completes successfully without any errors.

7. **Run the Application:** Run the application by right-clicking on the main class file (typically named Application or Application.java) and selecting "Run" from the context menu. Alternatively, you can use the "Run" button located in the toolbar.

8. **Access the Application:** Once the application is running, open your web browser and navigate to http://localhost:8080. You should see the home page of the MVC application.

Congratulations! You have successfully downloaded and run the MVC application on IntelliJ IDEA and MySQL Workbench. Feel free to explore the code and make any necessary modifications to suit your requirements.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT]([https://choosealicense.com/licenses/mit/](https://github.com/revanthkalagudi/employee-management-mvc-spring/blob/main/LICENSE))
