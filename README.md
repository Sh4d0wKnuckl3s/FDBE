# FDBE
Tool for validate Firebase DB Exposed vulnerability

# Usage:
git clone https://github.com/Sh4d0wKnuckl3s/FDBE.git
<br>cd FDBE
<br>chmod +x fdbe
<br>./fdbe -u example.firebaseio.com -a users (Default /.js) -o myusersexample
<br>or
for n in $(cat domains);do ./fdbe -u $n.firebaseio.com -a users (Default /.js) -o myusersexample;done

# Reference
https://thehackernews.com/2020/05/android-firebase-database-security.html
<br>https://searchsecurity.techtarget.com/news/252474871/Exposed-Firebase-databases-hidden-by-Google-search#:~:text=A%20security%20researcher%20discovered%20that,engines%20--%20but%20not%20Google%27s.&text=json%20to%20the%20end%20of,wrote%20in%20the%20blog%20post
