FORMAT: 1A
HOST: http://mind.jtwang.me

# aweb-backend

# Group Teacher


## Teacher Register [/register/teacher]

### Register [POST]

+ Request (application/json)

        {
            "teacher_id": "123456",
            "teacher_name": "John",
            "teacher_password": "123456"
        }
        
+ Response 201 (application/json)
        
        {
            "teacher_id": "123456",
            "teacher_name": "John",
            "teacher_password": "123456"
        }


+ Response (application/json)

        teacher with this teacher id already exists

        {
            "error_message":
            {"teacher_id": "123456"}
        }
        
+ Response 400 (appication/json)
        
        {
            "error_message": "wrong role"
        }

## Teacher Login [/login/teacher]

## Teacher Logout [/logout]


