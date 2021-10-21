# bindecytest
**Please read the NODES.txt file to see the usage of the created images on each node.**


__Table of contents:

  external node folder:
    Contains Dockerfile and start.sh files that builds an image
    to redirect traffic on port 443.
    
  intermeduate node folder:
    Contains the same Dockerfile and start.sh files as the external node folder
    since both the external node and the intermeduate node are redirecting traffic on port 443.
    
  internal node folder:
    Contains Dockerfile and start.sh files that builds an image
    to redirect traffic on port 443.
    
