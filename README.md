# React Router Dom Bug: Unexpected Route Behavior

This repository demonstrates a common issue encountered when using React Router Dom: unexpected route behavior.  This bug manifests in various ways, including missing routes, incorrect path matching, or unexpected redirects.

## The Bug

The provided `App.js` file contains a basic React Router setup. The issue arises when the user attempts to navigate to a route that is not explicitly defined in the `Routes` component, resulting in unexpected behavior, such as rendering nothing, rendering an unexpected component, or an infinite redirect loop. The specific symptom depends on the application's configuration and other related code.

## The Solution

The solution addresses the bug by adding the missing route in the `Routes` component for the missing `/contact` path.   This ensures that the `Contact` component is correctly rendered when the user navigates to this path.

## How to Reproduce

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies: `npm install`
4. Run the application: `npm start`
5. Observe the unexpected behavior when attempting to access the `/contact` path. Then, examine the solution and observe the correct behavior. 