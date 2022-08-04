# Golang_Ecko_RestFull

### GET POST PUT DELETE methods
```
curl http://127.0.0.1:2000/courses
```

Reponce:<br>
```
[{
		Id:   1,
		Name: "Data 1",
	},
	{
		Id:   2,
		Name: "Data 2",
	},
	{
		Id:   3,
		Name: "Data 3",
}]
```

#### And another urls in ```server.go``` file.


## Install

```
git clone https://github.com/azizovrafael/Golang_Ecko_RestFull 
cd Golang_Ecko_RestFull
```
```
go mod init api
go get github.com/labstack/echo/v4
```
