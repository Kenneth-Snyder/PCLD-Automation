# PCLD-Automation
A browser extension that automates various internal office tasks, compatible with both Chrome and Edge.

This is a public landing page for the repository. To access the files, go to https://github.com/intel-sandbox/PCLD-Automation. If you need and don't have access to the main repo, please request it. 

Overview

The PCLD Automation browser Extension is designed to streamline asset management processes by automating interactions with various Intel web services. This extension facilitates the retrieval and processing of asset records, service tasks, incident tickets, and custodian information, enhancing efficiency and accuracy in asset tracking and management.

Features

Automated Asset Record Search: Initiates a search for asset records using serial numbers and WWIDs. Service Task Retrieval: Fetches service tasks associated with specific serial numbers and WWIDs. Incident Ticket Retrieval: Collects incident tickets related to given serial numbers. Custodian Information: Retrieves custodian details from Intel's worker database. LEHN Status Check: Determines the LEHN status of assets. Duplicate Record Detection: Alerts users to duplicate asset records. Asset History Access: Opens and appends relevant information to asset history pages.

Usage

Search Asset Records: Use the clipboard to copy asset details (date, serial number, and WWID) and click the button added by the extension to initiate the search. View Results: The extension will open new tabs to fetch service tasks, incident tickets, and custodian information data. Check for Duplicates: The extension will alert you if duplicate records are detected. Access Asset History: Navigate to the asset record's history list, and append the collected data.

Permissions

The extension requires the following permissions: activeTab: To interact with the currently active tab. tabs: To create and manage tabs. scripting: To inject scripts into web pages. clipboardRead: To read data from the clipboard. storage: Previously used as a method to store temporary data. These features are now deprecated and will be removed in the next update. webNavigation: To monitor and react to web navigation events.

Files

background.js: Handles background tasks and message passing between content scripts and the extension. content.js: Contains logic for interacting with web pages, retrieving data, and appending elements. manifest.json: Defines the extension's metadata, permissions, and scripts.


