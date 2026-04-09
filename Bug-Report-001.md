 # Bug Report: Search Functionality Crash on Special Characters

**Status:** Open
**Severity:** Major (System Hang)
**Priority:** High

## Description
The application becomes unresponsive and the UI freezes when a user attempts to search after inputting special characters in the search bar.

## Environment
- **Browser:** Google Chrome (Latest)
- **OS:** Windows 11 / macOS
- **URL:[** https://www.apps_homepageurl.com]

## Pre-conditions
- User is on the Home Page.

## Steps to Reproduce
1. Navigate to the 'Search bar' in the header of the home page.
2. Type the following characters: **'~!@#$%()?:"|\__'+'.**
3. Press the 'Enter' key or click the search icon button by the search bar.

## Expected Result
The system should either sanitise the input and show "No results found" or display a validation message: "Invalid characters entered".

## Actual Result
The browser tab freezes completely. The page becomes unclickable, requiring a hard refresh of the browser.

## Attachments
*Note:(In a real job, you would attach a screenshot or a screen recording here)*


