# Geodesic Graph Access Guide

This guide provides detailed instructions on how to access and interact with the Geodesic Graph within EDA, accessible through both the User Interface (UI) and programmatically.

## Local Machine Configuration

Before accessing the EDA, ensure your local machine is properly configured:

1. **Create Configuration Directory**: Create a directory at `C:\Users\[YourUsername]\.config\geodesic` on your local machine, replacing `[YourUsername]` with your actual username.

2. **Configuration File**: Place the provided configuration file in this directory to enable authentication.

3. **Azure Tenant Login**: Make sure you are logged into the Goamerigeo Azure tenant prior to accessing EDA, as it oversees all authentication processes.

## EDA Homepage Navigation

To navigate the EDA homepage and access the graph:

1. **Access Graph Apps**: Visit the EDA homepage and select the 'Graph Apps' icon.

2. **Initialize Account**: Choose the 'EDA Knowledge Graph' application on the subsequent page to initialize your user account in the system backend.

3. **Notify for Access**: Notify us post account creation to escalate your privileges and grant access to various graph projects.

## Graph UI Access and Global Graph

After setting up your account:

1. **Graph UI**: Access the graph UI, where a dropdown menu lets you select and view different graph projects you have access to.

2. **Basic Searches**: Use the text-based query box for basic searches. Initially, you'll have access to the 'Global Graph', which contains metadata for a variety of datasets.

3. **Global Graph as a Directory**: The 'Global Graph' acts as a directory or index to these datasets, hosted externally and does not directly contain the datasets.

4. **Querying Data**: Query this raw external data using the geodesic API directly from the command line. Instructions are provided in both the notebooks and the online API documentation.

## Development Environment Setup

For development environment setup:

1. **IDE Selection**: Choose your preferred Integrated Development Environment (IDE), like Visual Studio Code, and run `pip install geodesic-api[all]`. The Jupyter notebooks might offer an easier navigation option.

2. **Explore Notebooks**: Visit the GitHub repository at [`seerai/GeodesicExamples`](https://github.com/seerai/GeodesicExamples) for examples of authentication and programmatic access methods. For the latest versions, refer to the zip file of notebooks included.

## Methodologies and API Documentation

To get started with methodologies and API documentation:

1. **Quickstart Guide**: Consult the Quickstart section at [geodesic-python-api main documentation](https://seerai.space/geodesic-python-api) for detailed guidance.

2. **Usage Tips**: Visit the 'How to Use This' section under the documentation at [geodesic-python-api main documentation](https://seerai.space/geodesic-python-api) for practical tips and examples.

## Additional Information

The graph data is organized into various projects like 'Janes Data' and 'Crosshairs', with access provided accordingly. While there are numerous projects currently created, a comprehensive list can be obtained if desired.

Remember, the 'Global Graph' serves as a foundational layer of currently integrated external data sources, marking the beginning of accessing and querying a broad array of external datasets. This integration facilitates extensive data analysis and exploration via the geodesic API.
