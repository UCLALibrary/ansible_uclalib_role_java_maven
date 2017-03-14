UCLALib Ansible Role: Java: Maven [![Build Status](https://travis-ci.org/UCLALibrary/uclalib_role_java_maven.svg?branch=master)](https://travis-ci.org/UCLALibrary/uclalib_role_java_maven)
=========

Installs Apache Maven, a Java-based software build tool.

Requirements
------------

A JDK

Role Variables
--------------

 * maven_major_version: the major version number of the Maven binary you wish to install, defaults to 3.
 * maven_version: the full version number of the Maven binary you wish to install, defaults to 3.0.5

Dependencies
------------

 * [UCLALib Ansible Role: Java](https://github.com/UCLALibrary/ansible_uclalib_role_java)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD
