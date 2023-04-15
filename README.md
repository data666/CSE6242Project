# All-in-one Resale Flat Tool
## Description

This is a holistic tool made in Python and Tableau framework. It helps potential HDB buyers effectively research housing price trends and shortlist suitable flats for purchase all within one portal. In order to use our tool please:
1. Download Tabpy, Pandas libraries
2. Install and activate Tableau desktop
3. Download and install Python version 3.6 or later

Refer to the hyperlinks provided below for more details:

https://pypi.org/project/tabpy/

https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html

https://www.tableau.com/products/desktop/download

## Installation

 To install TabPy on to an environment:

```
pip install tabpy
```

To start TabPy with default setting run the following command in the terminal:

```
tabpy
```
It will take a few seconds to see that the server is running locally on the 9004 port. You can verify it by open it in your web browser (http://localhost:9004/)


## Execution

Connecting to TabPy

Step 1: Make sure your TabPy server is running locally before connecting it with Tableau.  

Step 2: Go to your Tableau desktop and set up the service by click on the Help menu > Settings and Performance > Manage Analytics Extension Connection.

![url image](https://drive.google.com/uc?id=1YZTieMDuWtDjm9t6BauMHLDfKKJ8KoLd)

Step 3: Select the TabPy option in new window.

![url image](https://drive.google.com/uc?id=1DK7hudeNpiyX2svrD7xzgae7ttWsbQFN)

Step 4: Add Hostname as "localhost" and Port to "9004" and press on Test Connection. After passing the test, save the connection configuration. 

![url image](https://drive.google.com/uc?id=1I3PIwSa7dYNNPV2Ge1_E5Y46H6zIIXmJ)

Step 5: Now, you can go to "All in One Flat Tool" dashboard to analyze data.
