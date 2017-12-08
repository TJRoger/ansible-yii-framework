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
- {role: ansible-yii-framework, yii_version: "1.1.15", yii_hash: "022a51"}
```