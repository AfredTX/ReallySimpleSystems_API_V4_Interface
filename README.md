# ReallySimpleSystems_API_V4_Interface
I work for a non profit organization that uses a CRM called Really Simple Systems. When I took up the position of Data Manager I found that the staff was keeping track of our clients by copying and pasting information hosted on the website into various spreadsheets. Rather than doing all this manual data entry and copy and pasting I've created a program to automate the collection of client data. 

Really Simple Systems (as it is used by the NPO) hosts client data in Accounts and Activities. An Account is created for each client, storing a couple dozen data fields. After their account is created, updates and client developments are tracked by recording "Activities" which can hold 10 customized fields including a description text box.

Really Simple Systems offers the ability to download Account and Activity data through their "Data Managment" tools. However, accessing their API allows us to both a) automatically update csv files whenever Accounts or Activities are created or modified, and b) store our client data in relational databases. It also serves as a starting point for the NPO to start conducting more in depth analysis.

I've looked around and haven't seen anyone else posting about how to access Really Simple Systems' API, so hopefully this project is useful to someone else looking to automate their data collection from the platform.
