# Description
This is a simple url shortener (duh) written in Javascript that gets the URL mappings from the `mapping.json` file
# Installing and running
To install the dependencies, do:
`npm install`
then run by using
`npm start`

# JSON mapping format
Example:
`yourdomain.com/very/long/url` will map into `mapping.json` as: 
`"very/long/url"`<br><br>
**Make sure to always specify *https* or *https* in the destination url**
```json
{
  "shortUrl1" : "http://longUrl1",
  "shortUrl2/cool" : "https://longUrl2"
}
```
