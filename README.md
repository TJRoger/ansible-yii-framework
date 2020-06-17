[![Build Status](https://travis-ci.org/thomaslorentsen/ansible-yii-framework.svg?branch=master)](https://travis-ci.org/thomaslorentsen/ansible-yii-framework)

# Yii framework
Install Yii Framework with Ansible

# Usage
Install the latest version
```yaml
- {role: ansible-yii-framework}
```
Install a different version
```yaml
- {role: ansible-yii-framework, yii_version: "2.0.35", yii_hash: "60a3965"}
```
