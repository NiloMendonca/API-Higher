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
	"name": "String",
	"phone": "String",
        "email": "String",
        "birth_date": "Date",
        "profession": "String",
        "civil_state": "String",
        "rg": "String",
        "doc": "String",
        "nationality": "String (BR)",
        "naturalness": "String",
        "cell_phone": "String",
        "zipcode": "String",
        "ddi": "String",
        "number": "String",
        "complement": "String",
        "public_place": "String",
        "neighborhood": "String",
        "city": "String",
        "state": "String (SP)",
        "country": "String (BR)",
        "american_resident": "Boolean",
        "social_security_number": "String",
        "monthly_income": "String",
        "patrimony": "Number",
        "how_long_transactions": "String",
        "transact_in_others_companies": "Boolean",
        "which_institutions": "String",
        "operated_volume": "Number",
        "how_meet_higher": "String",
        "password": "String",
        "accept_receive_notifications": "Boolean",
        "knowing_site": "Boolean",
        "knowing_social_network": "Boolean",
        "knowing_google": "Boolean",
        "knowing_indication": "Boolean",
        "indications": "String"
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
	"name": "String",
	"phone": "String",
        "email": "String",
        "birth_date": "Date",
        "profession": "String",
        "civil_state": "String",
        "rg": "String",
        "doc": "String",
        "nationality": "String (BR)",
        "naturalness": "String",
        "cell_phone": "String",
        "zipcode": "String",
        "ddi": "String",
        "number": "String",
        "complement": "String",
        "public_place": "String",
        "neighborhood": "String",
        "city": "String",
        "state": "String (SP)",
        "country": "String (BR)",
        "american_resident": "Boolean",
        "social_security_number": "String",
        "monthly_income": "String",
        "patrimony": "Number",
        "how_long_transactions": "String",
        "transact_in_others_companies": "Boolean",
        "which_institutions": "String",
        "operated_volume": "Number",
        "how_meet_higher": "String",
        "password": "String",
        "accept_receive_notifications": "Boolean",
        "knowing_site": "Boolean",
        "knowing_social_network": "Boolean",
        "knowing_google": "Boolean",
        "knowing_indication": "Boolean",
        "indications": "String"
}
```
Return:
```
{
	"status": 200
}
```
### (POST) '/registerByToken':
Header:
```
{
	token: 'secret_token'
}
```
Body:
```
{
	  "token": "token"
}
```
Return:
```
{
	"name": "String",
	"phone": "String",
        "email": "String",
        "birth_date": "Date",
        "profession": "String",
        "civil_state": "String",
        "rg": "String",
        "doc": "String",
        "nationality": "String (BR)",
        "naturalness": "String",
        "cell_phone": "String",
        "zipcode": "String",
        "ddi": "String",
        "number": "String",
        "complement": "String",
        "public_place": "String",
        "neighborhood": "String",
        "city": "String",
        "state": "String (SP)",
        "country": "String (BR)",
        "american_resident": "Boolean",
        "social_security_number": "String",
        "monthly_income": "String",
        "patrimony": "Number",
        "how_long_transactions": "String",
        "transact_in_others_companies": "Boolean",
        "which_institutions": "String",
        "operated_volume": "Number",
        "how_meet_higher": "String",
        "password": "String",
        "accept_receive_notifications": "Boolean",
        "knowing_site": "Boolean",
        "knowing_social_network": "Boolean",
        "knowing_google": "Boolean",
        "knowing_indication": "Boolean",
        "indications": "String",
	"step": "Number"
}
```
### (POST) '/incompleteRegistration':
Header:
```
{
	token: 'secret_token'
}
```
Body:
```
{
	"name": "String",
	"phone": "String",
        "email": "String",
        "birth_date": "Date",
        "profession": "String",
        "civil_state": "String",
        "rg": "String",
        "doc": "String",
        "nationality": "String (BR)",
        "naturalness": "String",
        "cell_phone": "String",
        "zipcode": "String",
        "ddi": "String",
        "number": "String",
        "complement": "String",
        "public_place": "String",
        "neighborhood": "String",
        "city": "String",
        "state": "String (SP)",
        "country": "String (BR)",
        "american_resident": "Boolean",
        "social_security_number": "String",
        "monthly_income": "String",
        "patrimony": "Number",
        "how_long_transactions": "String",
        "transact_in_others_companies": "Boolean",
        "which_institutions": "String",
        "operated_volume": "Number",
        "how_meet_higher": "String",
        "password": "String",
        "accept_receive_notifications": "Boolean",
        "knowing_site": "Boolean",
        "knowing_social_network": "Boolean",
        "knowing_google": "Boolean",
        "knowing_indication": "Boolean",
        "indications": "String",
	"step": "Number",
	"token": "String"
}
```
Return:
```
{
	"token": "String"
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
	  "email": "login"
}
```
Return:
```
{
	"status": 200
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
	"password": "pass",
	"token": "token"
}
```
Return:
```
{
	"message": "Senha atualizada"
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
	"token": "token"
}
```
Return:
```
{
	"data": {
		"token": "String",
		"email": "String",
		"active": "Boolean"
	},
	"user": {
		"name": "String",
		"phone": "String",
	        "email": "String",
	        "birth_date": "Date",
	        "profession": "String",
	        "civil_state": "String",
	        "rg": "String",
	        "doc": "String",
	        "nationality": "String (BR)",
	        "naturalness": "String",
	        "cell_phone": "String",
	        "zipcode": "String",
	        "ddi": "String",
	        "number": "String",
	        "complement": "String",
	        "public_place": "String",
	        "neighborhood": "String",
	        "city": "String",
	        "state": "String (SP)",
	        "country": "String (BR)",
	        "american_resident": "Boolean",
	        "social_security_number": "String",
	        "monthly_income": "String",
	        "patrimony": "Number",
	        "how_long_transactions": "String",
	        "transact_in_others_companies": "Boolean",
	        "which_institutions": "String",
	        "operated_volume": "Number",
	        "how_meet_higher": "String",
	        "accept_receive_notifications": "Boolean",
	        "knowing_site": "Boolean",
	        "knowing_social_network": "Boolean",
	        "knowing_google": "Boolean",
	        "knowing_indication": "Boolean",
	        "indications": "String",
	}
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
