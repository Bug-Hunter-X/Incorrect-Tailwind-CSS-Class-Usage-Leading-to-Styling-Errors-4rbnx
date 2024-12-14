# Incorrect Tailwind CSS Class Usage

This repository demonstrates a common error encountered when using Tailwind CSS: using incorrect class names or forgetting to include necessary plugins.  The `bug.js` file shows an example of this, while `bugSolution.js` provides the corrected code.

## Bug Description
Incorrectly using Tailwind CSS classes, like typos or using classes that don't exist in your configuration, can lead to unexpected styling or no styling at all.  This issue frequently arises from simple mistakes that are easily missed.

## How to Reproduce
1. Clone this repository.
2. Run the code in `bug.js` within a React or similar application that uses Tailwind CSS.
3. Observe the unexpected styles or errors.  Then run `bugSolution.js` to see the correct version.

## Solution
Carefully review the Tailwind CSS documentation to ensure the class names are used accurately. Double-check for typos and make sure the classes exist in your Tailwind configuration.  Utilize your IDE's autocompletion features to help avoid this issue.