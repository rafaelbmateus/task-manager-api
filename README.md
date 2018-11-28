# Rails API

rails s -b 0.0.0.0 -p 3001

# Config Domain test

```
# System32/drivers/etc/hosts

127.0.0.1 api.task-manager.test
```

# Curls
## Show User
curl -v -H "Accpet: application/vnd.taskmanager.v1" http://api.task-manager.test:3001/users/1

