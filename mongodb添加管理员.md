type: "MARKDOWN_NOTE"
folder: "4f27d4a94b23f8106ba4"
title: "添加管理员"
content: '''
  添加管理员
  ```
  use admin
  db.createUser({user:"admin",pwd:"password",roles:["root"]})
  db.auth("admin", "password")
  ```
  
  添加数据库用户
  ```
  db.createUser({user:"test", pwd:"test", roles: [{role:"dbOwner", db:"test"}]})
  ```
  
  登录mongodb
  ```
  mongo -u "admin" -p "985211" --authenticationDatabase "admin"
  mongo -u "gamble" -p "985211" --authenticationDatabase "test"
  ```
'''
tags: []
isStarred: false
isTrashed: false
createdAt: "2017-09-22T16:05:41.292Z"
updatedAt: "2017-09-22T16:20:41.421Z"
