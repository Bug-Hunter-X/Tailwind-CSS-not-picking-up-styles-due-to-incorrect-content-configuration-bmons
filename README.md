# Tailwind CSS Content Configuration Error

This repository demonstrates a common error encountered when using Tailwind CSS: the styles are not being applied because the `content` array in the `tailwind.config.js` file is incorrect or missing.

The problem occurs when Tailwind cannot find the source files containing your classes.  This prevents Tailwind from correctly generating the CSS needed to apply your styles.

**Solution:** Correct the `content` array to properly point to your source files.