# HADOOP Cheat Sheet

## Working with HDFS from the command line
`$HADOOP_PATH/bin/hadoop dfs <CMD>`

### Inspect files	
+ `-ls <path>`:: list all files in `<path>`
+ `-cat <src>`:: print `<src>` on `stdout`
+ `-tail [-f] <file>`:: output the last part of the `<file>`
+ `-du <path>`:: show `<path>` space utilization

### Create/remove files	
+ `-mkdir <path>`:: create a directory
+ `-mv <src> <dst>`:: move (rename) files
+ `-cp <src> <dst>`:: copy files
+ `-rmr <path>`:: remove files

### Copy/Put files from a remote machine into the HADOOP cluster
+ `-copyFromLocal <localsrc> <dst>`:: copy a local file to the HDFS
+ `-copyToLocal <src> <localdst>`:: copy a file on the HDFS to the local disk

### HELP
+ `-help [cmd]`:: hopefully this is self-describing

