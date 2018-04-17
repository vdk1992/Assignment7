# Assignment7

The Login Problem

There is no restiction on the number of login attempts a user can make in trying to log in to Wordpress. This flaw in design allows a malicious attacker a robust opportunity to try a bunch of different passwords until something works. 

![alt text](https://github.com/vdk1992/Assignment7/blob/master/login.gif)


Admin XSS attack

Let's say an attacker is finally able to get into the wp-admin panel after guessing a 100 passwords and cracking it, they can easily insert an XSS attack into any of the existing posts or even create a new post with an XSS attack in it. This way, any viewer of this site can fall easily into an attack through the hands of the "admin"

![alt text](https://github.com/vdk1992/Assignment7/blob/master/XSS.gif)


Comment XSS attack 

Let's say the attacker is never able to gain access into the wp-admin panel, they can still just as easily implement the attack as a regular user of the site. Why? Because any one can comment on the blog and the comments are also open to XSS attacks. 

![alt text](https://github.com/vdk1992/Assignment7/blob/master/Comment.gif)
