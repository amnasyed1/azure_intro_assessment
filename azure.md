# **Storage** 

**Identify & List Services:**

Azure Blob Storage and Azure Files


**Service Description:**
<p> Azure Blob Storage can be utilized for storing large amounts of unstructured data, including images, videos, and files; which can be accessed from essentially anywhere at a large scale in block blobs. For example, it can store data for future backup and restore, archiving and disaster recovery. It also can store data that would be analyzed by an Azure hosted service. Anything in Blob Storage can be accessed through an Azure Storage client library, Azure Storage REST API, Azure Command-Line Interface (CLI), and Azure PowerShell. </p>
<p>Azure Files allows users to share files in the cloud that are fully managed and can be accessed through the Server Message Block (SMB) protocol (which is the industry standard), Azure Files REST API, and Network File System (NFS) protocol. A benefit of using Azure Files is it allows for the simplification of new cloud development projects and projects can be shared easily and in a timely manner.</p>

**Python Interaction:** 
<p>Azure Blob Storage offers libraries for users building applications with Python. Utilizing this service will be beneficial when working with Python because I can securely store any data that I want to analyze in the future on Azure Blob Storage. In addition, this service allows for the installation of Python packages such as pandas, and works conjunctively to analyze any stored data. </p>
<p>Python can be used to develop apps that use Azure Files to store their data. For instance, apps can be written that utilize Azure Storage SDK for Python using Azure Files REST API to communicate with Azure Files. Additionally, Azure Python SDK can be used to upload files from local storages into Azure Files. </p>

# **Compute**

**Identify & List Services:**

Azure App Service and Azure Functions

**Service Description:** 
<p>Azure App Service is a platform as a service (PaaS) that allows one to build and host web applications, backends for mobile applications, and RESTful APIs by utilizing any programming language such as Python, .NET, and Java. The applications can be run and scaled in Linux and Window environments and it allows for automated deployments from any Git repository, Github and Azure DevOps. </p>
<p>Azure Functions offers serverless computing, to allow users to write less code to deploy and run their code without managing and maintaining the server. Azure Functions automatically maintains and manages the infrastructure. </p>

**Python Interaction:**
<p>Azure App Service: I can develop and deploy Python Flask or FastAPI web applications on Azure App Service. To host applications in Azure, first one must create an Azure App Service web app by using Azure portal, Azure Tools extension pack, VS Code, or Azure CLI. After creating an app through, for example, Azure CLI, one can run commands from their Python code to manage their apps and deploy Python code. Through Azure SDK one can manage the resources provided from Azure App Services pertaining to creating or working on their web apps. </p>
<p>I can create, deploy, and run functions using Python in Azure Functions’ serverless environment utilizing Visual Studio (VS) Code, which would be able to respond to HTTP requests, aiding in creating and building any web applications in the future. </p>

# Database Services

**Identify & List Services:**

Azure Database for PostgreSQL

**Service Description:**
<p>Azure Database for MySQL is a fully managed cloud based relational database service on the MySQL community edition. The two deployment modes it’s available through are Single Server or Flexible Server. The Single Server is better to be utilized by pre-existing apps because it provides limited customization. The Flexible Server allows for much more flexibility over customization, configuration settings, and database management functions. The Flexible Server is best suited for developing apps. </p>
<p>Azure Database for PostgreSQL is a fully managed cloud based relational database on the open source Postgres database engine. Similar to Azure Database for MySQL, Azure Database for PostgreSQL also has two deployment modes, Single Server and Flexible Server. A benefit of the Flexibile Server is that it automatically generates server backups and stores the backups for future retrieval. </p>

**Python Interaction:**
<p>Python can be used to connect and query in the Flexible Server for Azure Database for MySQL. After connecting Python to the server, one can easily manipulate data by using SQL statements to query, update, insert and delete data in the respective database. </p>
<p>Similar to Azure Database for MySQL, Python can be utilized to connect and query data in the Flexible Server for Azure Database for PostgreSQL. In Python, one must install python libraries for PostgreSQL, psycopg2, to connect, query data, and perform database operations. /p>
