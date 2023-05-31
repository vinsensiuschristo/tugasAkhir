# API Register, Login, Logout, dan Lihat Data #
Route yang tersedia :
| Method | Route | Deskripsi |
| --- | --- | --- |
| GET | /api/users/me | Melihat data diri dari akun yang sudah login |
| POST | /api/auth/register | Membuat user baru |
| POST | /api/auth/login | Login User |
| GET | /api/auth/refresh | Refresh akses token |
| GET | /api/auth/logout | Logout user |

```
/api/auth/register      :       {
                                    "email":"xxxx",
                                    "name":"xxxx",
                                    "password":"xxxx",
                                    "confirmPassword":"xxxx",
                                    "photo":"xxxx",
                                }

/api/auth/login         :       {
                                    "email":"xxxx",
                                    "password":"xxxx",
                                }                                
```