# Linux Binary Directories Explanation



On Ubuntu, /bin is a symbolic link (shortcut) pointing directly to /usr/bin to maintain backwards compatibility with older system scripts. The /usr/bin folder is where system-wide programs and commands installed by the operating system package manager (like ls, git, and python3) reside. In contrast, /usr/local/bin is reserved for custom software or scripts added manually by the user or system administrator so they remain separate from system-managed files.
