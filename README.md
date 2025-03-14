# Rapido-Automation

Rapido Contact Form Automation using Selenium

Overview

This project automates the process of filling out the contact form on the Rapido Contact Page using Java and Selenium WebDriver.

Prerequisites

Ensure you have the following installed and configured before running the script:

Java Development Kit (JDK) 8 or higher

Eclipse IDE (or any preferred IDE)

Selenium WebDriver

ChromeDriver (compatible with your Chrome browser version)

Project Setup

Install Java and IDE: Ensure you have Java installed and set up in your system.

Download Selenium WebDriver:

Add the Selenium JAR files to your project’s build path.

Download ChromeDriver:

Place chromedriver.exe inside a Driver folder in your project directory.

Update the System.setProperty path accordingly in the script.

Code Explanation

The script automates the following steps:

Launches the Chrome browser and navigates to the Rapido Contact page.

Maximizes the browser window.

Fills in the required details:

Name

Email

Mobile number

Customer type dropdown selection

Query type dropdown selection

Comment section

Submits the form.

Scrolls down and clicks the 'Done' button.

Closes the browser (optional).

Running the Script

Open the project in Eclipse or any Java-supported IDE.

Ensure ChromeDriver is correctly set up.

Run the rappido.java file as a Java application.

Expected Outcome

The script will automatically complete and submit the contact form on the Rapido website.

It will then click on the ‘Done’ button after submission.

Notes

Ensure your internet connection is stable.

Update ChromeDriver if the browser version changes.

Modify the XPath if the website structure changes.

Troubleshooting

Element not found errors: Verify the XPath of the web elements.

ChromeDriver compatibility issues: Ensure that ChromeDriver matches your browser version.

Timeout issues: Increase Thread.sleep() duration or use WebDriver wait mechanisms instead.

Author

Bagavathi
