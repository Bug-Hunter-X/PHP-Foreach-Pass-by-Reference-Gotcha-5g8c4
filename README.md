This repository demonstrates a subtle bug in PHP related to pass-by-reference within foreach loops. The `bug.php` file contains the problematic code, while `bugSolution.php` offers a corrected version.  The issue arises from how PHP handles references within the loop; modifications inside the loop affect the original array directly, potentially leading to unintended side effects.  The solution shows how to avoid this issue by creating a copy of the array element before modification.