# PHP Type Juggling in Comparisons

This repository demonstrates a common issue in PHP related to type juggling during comparisons. Loose comparison (`==`) can lead to unexpected behavior when comparing strings and numbers.  The example shows how strict comparison (`===`) provides a safer and more predictable way to compare values.

**Bug:** The provided `bug.php` file contains code that utilizes loose comparison to compare a string and an integer.  This results in unexpected behavior based on PHP's automatic type conversion.

**Solution:** The `bugSolution.php` file presents the corrected code, using strict comparison (`===`) to compare values of different types correctly.

This demonstrates the importance of understanding PHP's type handling and employing strict comparison when precise type matching is required.