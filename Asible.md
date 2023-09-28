---


---

<ol>
<li>
<p>Introduce Ansible</p>
</li>
<li>
<p>Deploy Ansible</p>
<ol>
<li>BUILDING AN ANSIBLE INVENTORY</li>
<li>MANAGING ANSIBLE CONFIGURATION FILES</li>
</ol>
<ul>
<li>The ansible package provides a base configuration file located at /etc/ansible/ansible.cfg. This file is used if no other configuration file is found.</li>
<li>Ansible looks for a .ansible.cfg file in the user’s home directory. This configuration is used instead of the /etc/ansible/ansible.cfg if it exists and if there is no ansible.cfg file in the current working directory</li>
<li>If an ansible.cfg file exists in the directory in which the ansible command is executed, it is used instead of the global file or the user’s personal file. This allows administrators to create a directory structure where different environments or projects are stored in separate directories, with each directory containing a configuration file tailored with a unique set of settings.</li>
</ul>
</li>
<li>
<p>List item</p>
</li>
</ol>

