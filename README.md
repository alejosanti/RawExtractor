# RawExtractor
It's a short Python script that extracts the data from an HTTP request in its raw format, so you can use the resulting dictionaries in a classic Python request.

It was tested only with GET requests, and the raw string should have the following format:
![image](https://user-images.githubusercontent.com/50599731/206590183-e73759b3-c12c-40bf-9a87-bd587e9b8189.png)

- The first line must be the request line
- The second line must have the host
- The third line must have the cookies (if the request has any)
- The rest of the request should be the headers

Please make sure that the format of the request you paste is the same that the picture shows. For example, make sure that you:
- Did not leave blank lines before or after the request in the string
- Left a blank space after the ":" separator in each header
