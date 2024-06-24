# Scrum Note Automation

This repository contains Google Apps Script code for automating team scrum notes.

## Project Overview

This project aims to automate the creation and maintenance of scrum notes for the team. The scripts handle the generation of scrum tables on a daily basis, excluding weekends and specific holidays, and also automate the archiving of notes at the end of each month.

## Files

### 1. table_generator.json

This script generates the scrum table every day except Friday, Saturday, Sunday, and holidays in Mexico.

### 2. auto_archive.json

This script runs on the last day of each month. It performs the following tasks:
- Automatically copies the scrum note document.
- Inserts the URL of the copied document under the 'Archive' heading of the original document.
- Cleans up all existing work logs in the original document to ensure it remains fast and light.
