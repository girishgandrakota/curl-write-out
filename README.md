# curl-write-out

#Usage Syntax:-

curl -o /dev/null -w "@curl_output.txt" [URL to Test]

# Example Command

curl -o /dev/null -ksL -w "@curl_output.txt" https://google.com

# Example Commmand Output

MyShell% curl -o /dev/null -sL -w "@curl_output.txt" https://google.com

===========================================
HTTP Response:-
===========================================

HTTP Return Code:- 200
HTTP Response Code:- 200
HTTP Connect Code:- 200
HTTP Total Response Time:- 3.009756 seconds

===========================================
HTTP Request Details:-
===========================================

Local IP:- 172.28.242.232
Local Port:- 64343
Number of Connects attempts:- 2
Number of URL redirects:- 1
Remote Host IP:- 172.217.6.68
Remote Host Port:- 443

===========================================
URL Redirection:-
===========================================

Redirected Effective URL:- https://www.google.com/
Redirected URL:-  

===========================================
SSL TLS Handshake Status:-
===========================================

Proxy SSL Handshake Status:- 0
SSL Handshake Status:- 0

===========================================
Data Transfer Details:-
===========================================

Total Bytes Downloaded:- 12115 Bytes
Total Header Bytes Downloaded:- 1451 Bytes
Total Request Bytes Sent:- 148 Bytes
Total Bytes Uploaded:- 0.000 Bytes
Average Download Speed BPS:- 4026.000 Bytes per second
Average Upload Speed BPS:- 0.000 Bytes per second

===========================================
URL Times:-
===========================================

DNS Time:- 0.473252 seconds
TCP Connection Setup Time:- 0.985690 seconds
App SSL Connection Setup Time:- 2.221921 seconds
PreTransfer Time:- 2.222118 seconds
Total URL Redirection Time:- 1.345552 seconds
Time for First Byte Download:- 2.955776 seconds
===========================================
Total Time taken:- 3.009756 seconds
===========================================
