# engagecode
engagecode.com

# 在scaffolding目录下
npm start

# mongo
# 在mongo安装路径下
mongod --dbpath D:\project\engagecode\scaffolding\data\

use nodetest1
db.usercollection.insert({ "username" : "testuser1", "email" : "testuser1@testdomain.com" })
db.usercollection.find().pretty()
newstuff = [{ "username" : "testuser2", "email" : "testuser2@testdomain.com" }, { "username" : "testuser3", "email" : "testuser3@testdomain.com" }]
db.usercollection.insert(newstuff);

#stylus

stylus -w style.styl -o style.css