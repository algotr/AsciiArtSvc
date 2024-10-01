# AsciiArtSvc

A web api service for using Figgle library

## Usage
`dotnet run`

### Example

after running the webapi project visit the this url for listing all fonts

`http://localhost:5015/`

or you may limit the fonts using the url

`http://localhost:5015/?take=10`

`http://localhost:5015/?take=10&skip=10`

getting the fonts that support right to left

`http://localhost:5015/?dir=RightToLeft&take=10`

### Display the figgle text
`http://localhost:5015/Hello,World`

`http://localhost:5015/Hello,World?font=Sweet`