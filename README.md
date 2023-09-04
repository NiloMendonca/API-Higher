# API-Higher

base URL: https://higher-solucoes-backend.herokuapp.com

## PESSOA FÍSICA:
### (POST) '/login':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/register':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (PUT) '/register':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (GET) '/register':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/completeRegistration':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/recoveryPassword':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/updatePassword':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/userDataByRecoveryToken':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/resendDoc':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/verifyDataByDoc':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```

## PESSOA JURÍDICA:
### (POST) '/pj/login':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/pj/register':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (PUT) '/pj/register':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (GET) '/pj/register':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/pj/completeRegistration':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/pj/recoveryPassword':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/pj/updatePassword':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/pj/businessDataByRecoveryToken':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
### (POST) '/pj/verifyDataByDoc':
Header:
```
{
    token: 'secret_token'
}
```
Body:
```
{
	  "email": "login",
	  "password": "pass"
}
```
Return:
```
{
	"user": {
		"email": "email@teste.com",
		"name": "NomeDoUsuario",
		"doc": "00000000000"
	},
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InNzb3JwcmVzb0BnbWFpbC5jb20iLCJpYXQiOjE2OTM4NTY3MzAsImV4cCI6MTY5Mzg1NzMzMH0.nFL5rQPmmCv-mbBWNvITLQoB9mDtNBmjpMjX0s4oGQ4"
}
```
