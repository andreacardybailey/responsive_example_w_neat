A simple example of a responsive layout using Bourbon Neat. 

This is an adaptation of https://github.com/andreacardybailey/responsive_example, which uses no grid.

Notes:

**To setup this project, beginning from the structure found here: https://github.com/andreacardybailey/responsive_example...

You must install neat and sass, as follows:**

$ gem install neat
$ gem install sass
$ cd styles
$ neat install

**Then, within your new responsive-base.scss stylesheet:**

@import "neat/neat";

**Then, from your project root:**

$ sass --watch styles/responsive-base.scss:styles/compiled/responsive-base.css