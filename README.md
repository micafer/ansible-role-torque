Torque ansible role
=========================

Installs and configure Torque/PBS LRMS in a cluster of nodes.
How to use it:

In the "Worker Nodes"
```yml
  roles:
  - { role: 'micafer.torque', torque_server: 'localhost', torque_type_of_node: 'mom' }
```

In the "Front-end Node"
```yml
  roles:
  - { role: 'micafer.torque', torque_server: 'localhost', torque_type_of_node: 'server' }
```
