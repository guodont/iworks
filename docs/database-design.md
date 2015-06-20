#YoWorks -数据库设计

##Users
* id
* name
* passwd
* email
* phone
* type [ student,teacher]

##UserInfo
* user_id
* sid
* real_name
* school
* class

##Works
* id
* type [1 电子版，2 纸质版，3 ]
* title
* desc
* content
* 

##WorksRecords
* id
* user_id
* work_id
* file_id

##Posts
* id
* user_id
* type
* title
* content

##Shares
* id
* user_id
* content
* tag
* type
* file_id
* 

##Files
* id
* url
* type
* user_id


##Relations
* user1_id
* user2_id
* datetime
 
 
