# CSS Specificity Issue: Nested Elements Overwriting Width
This repository demonstrates a common CSS issue where nested elements with the same class can lead to unexpected layout behavior due to specificity issues. The problem arises when an inner element's style declaration overrides the outer element's style declaration, resulting in the inner element inheriting its width, which is different from that of the outer element.  This example showcases how to resolve this issue by using more specific selectors or by adjusting the CSS specificity using IDs or more precise classes.

## Bug Description
Nested elements using the class `container` cause the outer container's width to be affected unexpectedly by the inner container's width. The solution avoids this behavior.