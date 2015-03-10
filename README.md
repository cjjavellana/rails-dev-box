Rails Development Environment in an Instant
==================================

### Requirements
1. Vagrant - https://www.vagrantup.com/
2. Virtual Box /  VMWare - https://www.virtualbox.org/

### How to

1. Checkout this repository
  ```
  git clone https://github.com/cjjavellana/rails-dev-box.git
  ```

2. Navigate to the project directory
3. Download the Virtual Machine
  ```
  vagrant init
  ```
4. Provision the Virtual Machine - Install the dependencies
  ```
  vagrant provision
  ```

5. SSH to your newly configured machine

  ```
  vagrant ssh
  ```
