# Deferred feedback with explicit validation question behaviour

This Moodle question behaviour was created by Tim Hunt of the Open University.

It is like the standard deferred feedback behaviour, but with the addition of
a 'Check' button that the student can click to get Moodle to check the syntax
of their response. This question behaviour was created for use with STACK
https://github.com/sangwinc/moodle-qtype_stack/

To install using git, type this command in the root of your Moodle install
<pre><code>    git clone git://github.com/timhunt/moodle-qbehaviour_dfexplicitvaildate.git question/behaviour/dfexplicitvaildate
    echo question/behaviour/dfexplicitvaildate >> .git/info/exclude</code></pre>

Then download the zip from
    https://github.com/timhunt/moodle-qbehaviour_opaque/zipball/master
unzip it into the question/behaviour folder, and rename the new
folder to dfexplicitvaildate.
