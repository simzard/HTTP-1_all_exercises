# HTTP-1_all_exercises

## Exercise 1 comments ##

It seems that the status number returned when I update (press F5) is 304 redirection, when it first was 200 OK.

Explanation of what I see:

General:
- Remote Address:127.0.0.1:8084 - this gives me the location of where the response is sent from (127.0.0.1 is localhost)
- Request URL:http://localhost:8084/MonitoringHTTPHeaders_1/index2.html - where the url is
- Request Method:GET - we have used the GET method
- Status Code:304 Not Modified - the status code means the document hasn't been changed since the update 

Response Headers:
- Date:Mon, 31 Aug 2015 12:35:52 GMT - the date the response is sent
- ETag:W/"446-1441024529000" - some internal cache in relationen to the client and server
- Server:Apache-Coyote/1.1 - the TomCat's server is the apache server

Request Headers:
- Accept:text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8 - what it accepts
- Accept-Encoding:gzip, deflate, sdch - what it accepts
- Accept-Language:en-US,en;q=0.8 - what it accepts
- Cache-Control:max-age=0 - when should this session die out? Immedeately
- Connection:keep-alive - keep the connection alive
- Host:localhost:8084 - the host and port 
- HTTPS:1 - use secure version of HTTP
- If-Modified-Since:Mon, 31 Aug 2015 12:35:29 GMT
- If-None-Match:W/"446-1441024529000"
- User-Agent:Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Ubuntu Chromium/44.0.2403.89 Chrome/44.0.2403.89 Safari/537.36

