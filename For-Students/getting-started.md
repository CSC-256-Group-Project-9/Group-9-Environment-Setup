# Getting Started (Work In Progress)

<hr>

**DEV NOTE:** This document should be converted to a word document before being delivered to students!

<hr>

This document will guide students through the first time setup of their lab environment.

## 1. Install python

**Note:** If you already have a new (3.10+) version of python installed oon your system, you may skip this step.

Navigate to [python.org](https://www.python.org/downloads/) and download and install the newest version of python for your system.

Veify installation with the following command:

    python --version

## 2. Create Labs Folder

Create a new folder on your hard drive to work from for the upcoming labs.

Example: <code>C:\\users\\your_username\\Documents\\CSC-256-Labs</code>

Open a terminal window and navigate to this folder.


## 3. Activate Virtual Environment
This will create a virtual environment in the current directory which can be used to install new python modules.

    python -m venv venv

The virtual environment needs to be activated after being created.

<hr>

**For PowerShell:**

If you have already enabled script execution for your system, or if you use a terminal other than PowerShell, you may skip the following step, otherwise, in an elevated PowerShell terminal (administrator privileges) run the following command:

    set-executionpolicy remotesigned

Type "Y" into the following promt and press enter.

    Execution Policy Change
    The execution policy helps protect you from scripts that you do not trust. Changing the execution policy might expose you to the security risks described in the about_Execution_Policies help topic at https:/go.microsoft.com/fwlink/?LinkID=135170. Do you want to change the execution policy?
    [Y] Yes  [A] Yes to All  [N] No  [L] No to All  [S] Suspend  [?] Help (default is "N"):  

This will enable scripts to run on your system which is required to activate the virtual environment.

<hr>

Run the following command to activate the virtual environment:

    .\venv\Scripts\Activate

At this point you should see <code>(venv)</code> at the beginning of each prompt.

Example: <code>(venv) C:\Users\username></code>

