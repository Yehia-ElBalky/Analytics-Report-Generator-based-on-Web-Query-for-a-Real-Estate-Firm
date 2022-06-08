# Analytics-Report-Generator-based-on-Web-Query-for-a-Real-Estate-Firm

A real estate research and technology firm creates an analytics report for the client’s property based on a web input form and reviews it manually then emails it to the client within 24 hours. They wanted to automate this process so that the analytics report of the client’s property is automatically generated and emailed to the client within a few minutes from the form submission.

I’ve managed to write a python script that does the following:

- Whenever the client requests a report it immediately reads the data the client has inputted in the web input form.

- It uses this data plus external data about properties in the client’s city to derive conclusions about the property’s market value, recent sales comparables, historical sales in the property’s area, active listing the client might be competing against, and more.

- It creates a pdf report with ~30 pages of insights and information in the shape of text, tables, and plots. With the option to change the report’s color, text’s color, used font, and more.

- It sends an email to the client with the generated report attached.

And I have uploaded the script with all the necessary files to AWS Cloud so that the firm can run it 24/7.
