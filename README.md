# dynamic-colorprompt
Color bash prompt that changes colors with hostname and privileges

While working in my lab, I've more than once switched to the wrong terminal and started working on the wrong server because all of my hosts have the same looking bash prompt.
To combat this, i've created a dynamic color changing bash prompt that selects a color for the hostname based on the hostname itself.
For the username, a blue username corresponds to a non-root user, and red corresponds to root user.

To use it, simply append the file to your .bashrc:<br>
<code>cat dynamic-colorprompt >> ~/.bashrc</code>
