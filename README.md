# Ubuntu 20.04
## Setup
- Install the module globally

```
npm install -g pm2
```

```
pm2 start /var/www/html/project/location.js
```

```
pm2 save
```

```
pm2 list
```

```
pm2 startup
```

- after `pm2 startup`, copy the code
- running the code in terminal
- done

## Managing Processes
```
pm2 list
```

```
pm2 restart app_name
```

```
pm2 reload app_name
```

```
pm2 stop app_name
```

```
pm2 delete app_name
```
