# Description

The factory is hiding things from all of its users. Can you login as logon and find what they've been looking at? `https://jupiter.challenges.picoctf.org/problem/13594/` or `http://jupiter.challenges.picoctf.org:13594`

# Solution

After logging in, we can see that there's a cookie named `admin` which is set to `False`. Setting it to `True` and refreshing the website will give us the flag.
