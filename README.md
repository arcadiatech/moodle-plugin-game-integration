# Moodle Native URL Plugin

This Moodle plugin was designed to providing native URL integration for external content in Moodle.

However, this modified version extends its capabilities to establish a secure connection with a WebGL Unity app. The primary goal is to facilitate a seamless and secure integration between Moodle and the Unity app through the use of JWT (JSON Web Token) and secure communication with Moodle web services.

## Changes Made

- Added JWT (JSON Web Token) support to secure the URL integration.
- Create a custom table in the database to store user scores.
- Implemented web services to retrieve the maximum score and save scores within the plugin.

## Why Create a Full Custom Plugin?

While modifying existing plugins can be efficient for certain modifications, creating a full custom plugin offers several advantages:

- Complete control over functionality, design, and integration.
- Avoids potential conflicts with future updates and changes to the original plugin.
- Enables tailored solutions to meet unique requirements and use cases.