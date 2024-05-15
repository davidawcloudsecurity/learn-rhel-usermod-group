# learn-rhel-usermod-group
How to create/add/remove user to a group
Add user to an exisitng group
```ruby
usermod -a -G examplegroup exampleusername
```
Change Primary group name
```ruby
usermod -g groupname username
```
Change Secondary group name
```ruby
usermod -G groupname username
```


Resource - https://www.howtogeek.com/50787/add-a-user-to-a-group-or-second-group-on-linux/
