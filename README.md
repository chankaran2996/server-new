


This Api is use for register admin 
Method: Post
URL : https://server-new-4wya.onrender.com/api/v1/auth/register-admin

req_data: {
    "name":"sample", 
    "email":"sample_email", 
    "password": "sample", 
    "phone": 12345678, 
    "adminCode": "sample"
}

res_data : {
    "message": "Admin registered successfully",
    "user": {
        "id": "MongoDBID",
        "name": "admin",
        "email": "sample_email",
        "phone": 12345678,
        "role": "admin"
    }
}

status code : 
200 - success 
201 - created
400 - Already exist
401 - Unauthorized
403 - invalid code
500 - server Error


