---
- hosts: all
  tasks:
  - name: create a directory
    file:
	    path: ~/hello
	    state: directory