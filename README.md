# IntuneObjectExplorer
(an attempt at an) Microsoft Intune object model, in a single HTML file.

## Overview
tl;dr an attempt at visualising Intune

Force-directed graph visualization of Intune components and their relationships. Maps the connections between users, devices, groups, policies, and other objects that constitute the Intune management system. 

![Screenshot](/screenshot.jpg)

## Usage

1. Clone or download the repository
2. Open `index.html` in any modern browser
3. Explore:
   - Toggle component categories
   - Select objects to focus on specific relationships
   - View relationship details in the side panel

## Implementation

- Pure client-side implementation using React and D3.js
- Self-contained: All dependencies loaded via CDN
- Responsive: Adapts to viewport dimensions

## Data Model

The visualization represents 25+ Intune components and 45+ relationship types, capturing the full administrative hierarchy, resource access patterns, and policy enforcement flows.

## Feedback

If you notice inaccuracies, missing components, or have suggestions for improvements, please open an issue or submit a PR. This is a technical representation developed through system observation rather than official documentation.
