KEERTHI.N  1KS17CS035
SHRIRAKSHA S KANAGO 1KS17CS102
MEGHANA.H.S 1KS16CS042

EXECUTION:
PROGRAM 4A: done by keerthi
input: ip and max
example:196.30.110.80  16 
output:
network address is:196.30.0.0
every 1oth usable IP address are:
196.30.0.10
196.30.0.20
.......
......
.....
196.30.0.250

DESCRIPTION:
step 1:take two arguments ip and max if there is no input it prints NO or less arguments specified. try again. input should be valid ,otherwise it prints invalid IP address specified.
step 2:here, the Ip address is taken as string and it is converted to binary using Integer.to BinaryString() method.
step 3:netmask is taken as integer type.
step 4:and operation is done between binaryIP and network.
step 5:result is again converted to string.
step 6:later every 10th usable IP address are displayed.

CHALLENGES FACED:
we were unable to take IPaddress and netmask as arguments,so we had to refer some online websites like geeksforgeeks and found answer. we didn't know how to display every 10th usable IPaddress,later we used some online websites and got the output.


PROGRAM 10B: done by meghana hs
step 1:we have declared variable url and fs.
step 2:we have created HTML forms with url "https://wasec.local.7888/".
step 3:a field is created to submit for winning a hummer.
step 4:if query.clear=="on" it prints '302' and cookie is set with expiring condition.
step 5: access the webpage with different path in the url and cookie is not sent in request header is verified.

CHALLENGES FACED:
we were unable to install tcpdump in pc later we had to refer several youtube video and we succeeded in doing it.But we are not used to tcpdump.

PROGRAM 13B: done by shriraksha
input: we have taken an embedded link eg:vtu.ac.in/en to look at the headers.
output:get the headers of the link directly in browser and take differences.

DESCRIPTION:
step 1: we have created a link of vtu.ac.in which has a embedded link of vtu.ac.in/en in HTML code.
step 2: a link is created and go through the headers of that link through network in tools.
step 3: look up the header details of created link (request and response).
step 4: access the same url in the browser to check the details of the header in tools.
step 5: take the differences between both request and response headers of link and url.

CHALLENGES FACED:
we were unable to get the headers received,later we got it through website.
