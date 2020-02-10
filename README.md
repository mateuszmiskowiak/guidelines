# guidelines

Don't use preprocessors
Don't use preprocessor syntax, e.g. Sass, Less, or Stylus, in your MDN example code. MDN documents the vanilla CSS language, and using preprocessors only serves to raise the bar to understanding the examples, potentially confusing readers.

Don't use specific CSS methodologies
In the same spirit as the previous guideline, don't write MDN example code using a specific CSS methodology such as BEM or SMACSS. Even though they are valid CSS syntax, the naming conventions can be confusing to people not familiar with those methodologies.

Use flexible/relative units
For maximum flexibility over the widest possible range of devices, it is a good idea to size containers, padding, etc. using relative units like ems and rems, or percentages and viewport units if you want them to vary depending on viewport width. You can read some more about this in our Responsive design building blocks article.

Don't use resets
For maximum control over CSS across platforms, a lot of people used to use CSS resets to remove every style, before then building things back up themselves. This certainly has its merits, but especially in the modern world CSS resets can be overkill, resulting in lots of extra time spent reimplementing things that weren't completely broken in the first place, like default margins, list styles, etc.
