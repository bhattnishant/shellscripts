# shellscripts

*curl*

```
curl -v --header "Connection: keep-alive" "https://google.com";
```

*Looping curl within minute / use for cronjob*

```
for ((i=1;i<=60;i++)); 
  do  curl -v --header "Connection: keep-alive" "https://google.com";
  sleep 1; 
 done
 ```
