# Geodesic_Graph_Access
Here are the steps to access and interact with the graph within EDA, available through both the User Interface (UI) and programmatically.

 

Local Machine Configuration:

1.       Create the directory C:\Users\[YourUsername]\.config\geodesic on your local machine, substituting [YourUsername] with your actual username. 

2.       Place the provided configuration file in this directory to enable authentication.

3.       Ensure you are logged into the Goamerigeo Azure tenant prior to accessing EDA, as it manages all authentication processes.

 

EDA Homepage Navigation:
1.       Visit the EDA homepage and select the 'Graph Apps' icon.

2.       Choose the 'EDA Knowledge Graph' application on the subsequent page to initialize your user account in the system backend.

3.       Notify us post account creation to escalate your privileges and grant access to various graph projects.

 

Graph UI Access and Global Graph:

1.       After setting up your account, access the graph UI. A dropdown menu at the top allows you to select and view different graph projects you have access to.

2.       Use the text-based query box for basic searches. Initially, you'll have access to the 'Global Graph', which contains metadata for a variety of datasets.

3.       The 'Global Graph' serves as a directory or index to these datasets, which are hosted externally. It does not directly contain the datasets.

4.       You can query this raw external data using the geodesic API directly from the command line. Instructions for these queries are provided in both the notebooks and the online api documentation.

 

Development Environment Setup:

1.       Choose your preferred Integrated Development Environment (IDE), like Visual Studio Code, and run pip install geodesic-api[all]. Or open one of the following notebooks. The jupyter notebooks are a bit easier to navigate.  See next.
2.       Explore a collection of notebooks on GitHub at seerai/GeodesicExamples for different authentication and programmatic access methods. For the most recent versions, refer to the zip file of notebooks I’ve included. LINK:   seerai/GeodesicExamples: A public repository for users to view examples of Geodesic and its components (github.com)

 

Methodologies and API Documentation:

1.       Consult the Quickstart section at geodesic-python-api main documentation for detailed guidance. LINK:  Quickstart — geodesic-python-api main documentation (seerai.space)
2.       Visit the 'How to Use This' section under the documentation at geodesic-python-api main documentation for practical tips and examples. LINK: How to Use This — geodesic-python-api main documentation (seerai.space)

 

Additional Information:

·         The graph data is organized into different projects like 'Janes Data' and 'Crosshairs', and access can be provided. There are a number of projects currently created.  I don’t have the comprehensive list as they don’t all pertain to me. However I Can get that if desired.

Remember, the 'Global Graph' is essentially a foundational layer of currently integrated external data sources. It marks the beginning of accessing and querying a wide array of external datasets. This integration paves the way for extensive data analysis and exploration via the geodesic API. 

 
