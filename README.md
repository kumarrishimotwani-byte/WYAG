# WYAG
project_summer
wyag — Write Yourself a Git

--Built a fully Git-compatible VCS from scratch in Python with a modular CLI via argparse, implementing 15 core commands across object storage, commit history, branching, and staging including init, add, commit, log, checkout, status, tag, ls-tree, and rev-parse.

--Engineered Git's content-addressable object storage from first principles — SHA-1 hashing over type-prefixed headers, zlib compression, and binary parsing of blob, tree, commit, and tag objects stored in .git/objects.

--Implemented the complete Git data model — Merkle DAG commit chains with recursive parent traversal for history, recursive tree objects for directory snapshots, and branch/tag management via lightweight file-based refs.

--Parsed Git's binary index file from scratch — extracting per-file SHA hashes, timestamps, inodes, and permission bits — to build the full staging area (add, rm, status), with all commands producing byte-identical output to real Git.
