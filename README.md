# CSS Specificity Surprise: !important overridden by a more specific selector

This repository demonstrates an uncommon edge case in CSS where the `!important` declaration is unexpectedly overridden.

The `bug.css` file contains CSS code showcasing the issue. The `bugSolution.css` file offers a solution and explanation.

The core issue lies in the interplay between `!important` and CSS specificity. While `!important` generally has high precedence, it can still be superseded by a more specific selector.  The example highlights this behavior which might be unexpected for some developers.

The solution provides an approach to handle such situations and promotes better understanding of CSS specificity.