! This repo is now deprecated. See [Karta](https://github.com/teodosin/karta) for the monorepo. 


# File System Graph

Library for adding metadata to the file system. Allows files and directories to be arbitrarily connected to each other and for additional attributes to be stored in both the nodes and the edges in the system. [AGDB](https://github.com/agnesoft/agdb) is used as the database backend storing all the metadata. 

Originally developed for [Karta](https://github.com/teodosin/karta) as the backend storage layer. Separating it into a standalone crate has the goal of maintainability, and allowing the data created and edited by Karta to be potentially used in other applications.
