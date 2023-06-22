# Scalable, Fault Tolerant File Management System

This GitHub repository implements the RAFT protocol to ensure server fault tolerance during client communication. The file storage functionality is achieved by dividing files into blocks and assigning them hash values. When performing download operations, the consistent hashing algorithm is utilized to locate the relevant blocks.
