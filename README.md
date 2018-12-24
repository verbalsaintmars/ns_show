# ns_show
ns_show from IOCTL_NS(2) 

Usage: ns_show /proc/[pid]/ns/[file] [p|u]

Display the result of one or both of NS_GET_USERNS (u) or NS_GET_PARENT (p)
for the specified /proc/[pid]/ns/[file]. If neither 'p' nor 'u' is specified,
NS_GET_USERNS is the default.
