# OS_LINUX
# Operating System:

**Introduction**
- OS functions & goals
- Types of OS (batch, multiprogramming, time-sharing, real-time, distributed, embedded, mobile)
- OS structure (monolithic, layered, microkernel, hybrid, modular)
- System calls
- Kernel mode & user mode
- Interrupts & traps
- Bootstrapping
- Virtual machines

**Process Management**
- Process concept & states
- Process Control Block (PCB)
- Context switching
- Process creation & termination (fork, exec, wait)
- Inter-process communication (pipes, message queues, shared memory, sockets)
- Threads (user-level, kernel-level)
- Multithreading models
- Zombie & orphan processes

**CPU Scheduling**
- FCFS
- SJF, SRTF
- Priority scheduling
- Round Robin
- Multilevel Queue
- Multilevel Feedback Queue
- Scheduling criteria (turnaround, waiting, response time, throughput)
- Real-time scheduling (RMS, EDF)
- Multiprocessor scheduling

**Process Synchronization**
- Critical section problem
- Race condition
- Peterson's solution
- Hardware solutions (Test-and-Set, Compare-and-Swap)
- Mutex locks
- Semaphores (binary, counting)
- Monitors
- Classical problems (Producer-Consumer, Readers-Writers, Dining Philosophers)

**Deadlocks**
- Necessary conditions
- Resource allocation graph
- Deadlock prevention
- Deadlock avoidance (Banker's algorithm, safe state)
- Deadlock detection
- Deadlock recovery
- Starvation

**Memory Management**
- Logical vs physical address
- Address binding
- Swapping
- Contiguous allocation (fixed, variable partitioning)
- Fragmentation (internal, external)
- Compaction
- Paging
- Page table structures (hierarchical, hashed, inverted)
- TLB
- Segmentation
- Segmented paging

**Virtual Memory**
- Demand paging
- Page fault handling
- Page replacement (FIFO, Optimal, LRU, LFU, Clock)
- Belady's anomaly
- Frame allocation
- Thrashing
- Working set model
- Copy-on-write
- Memory-mapped files

**File System**
- File concepts & attributes
- File operations
- Access methods (sequential, direct, indexed)
- Directory structures (single-level, two-level, tree, acyclic graph)
- File allocation (contiguous, linked, indexed, FAT, inode)
- Free space management (bitmap, linked list)
- File protection & permissions
- Mounting
- File system implementation
- Journaling
- Disk caching

**I/O & Disk Management**
- I/O hardware
- I/O techniques (polling, interrupt-driven, DMA)
- Device drivers
- Buffering, caching, spooling
- Disk structure
- Disk scheduling (FCFS, SSTF, SCAN, C-SCAN, LOOK, C-LOOK)
- Disk formatting
- Boot block & bad blocks
- Swap space management
- RAID levels

**Protection & Security**
- Goals of protection
- Access matrix
- Access control lists
- Capability lists
- Authentication
- Encryption basics
- Threats (virus, worm, trojan, buffer overflow)
- Firewalls
- Intrusion detection

**Distributed Systems**
- Distributed OS concepts
- Remote Procedure Call (RPC)
- Distributed file systems
- Clock synchronization
- Distributed mutual exclusion
- Distributed deadlock
- Election algorithms

**Case Studies**
- Linux
- Windows
- Unix
- Android
- macOS

**Numerical Practice Topics**
- Scheduling Gantt charts
- Banker's algorithm problems
- Page replacement problems
- Paging & segmentation address translation
- Disk scheduling problems
- Effective memory access time
- Semaphore-based synchronization problems

# Linux OS Topics

**Basics**
- Linux distributions (Ubuntu, Fedora, Debian, Arch, RHEL, CentOS)
- Installation & dual boot
- Boot process (BIOS/UEFI, GRUB, kernel, init/systemd)
- Runlevels & targets
- Shell types (bash, zsh, sh)

**File System**
- Directory structure (/, /etc, /var, /home, /usr, /bin, /tmp)
- File types
- Navigation commands (cd, ls, pwd)
- File operations (cp, mv, rm, touch, mkdir)
- Links (hard & soft)
- Inodes
- Mounting & unmounting
- fstab
- File systems (ext4, XFS, Btrfs, NTFS)

**File Viewing & Editing**
- cat, less, more, head, tail
- vi/vim, nano
- diff, cmp

**Searching & Text Processing**
- find, locate, which, whereis
- grep, egrep
- sed, awk
- cut, sort, uniq, wc, tr

**Users & Groups**
- useradd, usermod, userdel
- groupadd, groupmod
- passwd, chage
- /etc/passwd, /etc/shadow, /etc/group
- sudo & sudoers
- su

**Permissions & Security**
- chmod, chown, chgrp
- umask
- Special permissions (SUID, SGID, Sticky bit)
- ACLs (setfacl, getfacl)
- SELinux, AppArmor
- Firewall (iptables, firewalld, ufw)
- SSH keys & hardening
- fail2ban

**Process Management**
- ps, top, htop
- kill, killall, pkill
- Foreground/background (bg, fg, jobs)
- nohup
- nice, renice
- cron, at
- systemctl, service
- Signals

**Package Management**
- apt, dpkg (Debian/Ubuntu)
- yum, dnf, rpm (RHEL/Fedora)
- pacman (Arch)
- snap, flatpak
- Repositories
- Compiling from source

**Disk & Storage**
- df, du
- fdisk, parted
- mkfs
- LVM (PV, VG, LV)
- RAID
- Swap
- Disk quotas

**Networking**
- ip, ifconfig
- ping, traceroute
- netstat, ss
- nslookup, dig
- curl, wget
- Static & DHCP configuration
- hostname
- /etc/hosts, /etc/resolv.conf
- SSH, SCP, rsync
- NFS, Samba
- Network bonding

**Services & Servers**
- Apache, Nginx
- FTP (vsftpd)
- DNS (BIND)
- DHCP
- Mail server (Postfix)
- MySQL/MariaDB
- NTP/Chrony

**Shell Scripting**
- Variables
- Conditions (if/else, case)
- Loops (for, while)
- Functions
- Command-line arguments
- Input/output redirection
- Pipes
- Exit status
- Cron jobs with scripts

**Archiving & Compression**
- tar
- gzip, bzip2, xz
- zip, unzip

**System Monitoring & Logs**
- /var/log
- journalctl
- dmesg
- vmstat, iostat, sar
- free, uptime
- lsof

**Environment & Configuration**
- Environment variables
- PATH
- .bashrc, .bash_profile
- Aliases
- /etc/profile

**Kernel & Modules**
- uname
- lsmod, modprobe, insmod, rmmod
- Kernel parameters (sysctl)
- Kernel upgrade

**Backup & Recovery**
- rsync
- dd
- tar backups
- Recovery/rescue mode
- Root password reset

**Advanced**
- Virtualization (KVM)
- Docker/containers
- Ansible basics
- Git basics
- Performance tuning
