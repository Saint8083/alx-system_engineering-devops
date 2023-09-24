# ** SSH config file for OpenSSH client **

Public authentication is used for passwordless logins between systems. It is often used for automated processes, such as backups, configuration management, and file transfers. It is also used by sophisticated end users and system administrators for single sign-on. See the public key authentication for configuring it.

When a user has created more than one SSH key for authentication, the -i command line option may be helpful for specifying which key to use. In the client configuration file, this can be specified using the IdentityFile options.

The ssh_config client configuration file has the following format. Both the global /etc/ssh/ssh_config and per-user ~/ssh/config have the same format.

* Empty lines and lines starting with '#' are comments.

- Each line begins with a keyword, followed by argument(s).

+ Configuration options may be separated by whitespace or optional whitespace and exactly one =.

* Arguments may be enclosed in double quotes (") in order to specify arguments that contain spaces.
