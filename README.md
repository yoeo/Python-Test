# Python-Test
A Python technical test

#### Create a Python2 program that:

1. download a big text file from a given URL: https://raw.githubusercontent.com/yoeo/Python-Test/master/userdata.segment
2. split the downloaded file content by ```newsletter_optin``` into different files of 10 000 lines maximum each. ```newsletter_optin``` value **MUST** be 0 or 1

#### What we expect:

1. a **readable** Python script
2. no alteration of ```userdata.segment```, as it could be provide by users, you **MUST NOT** edit it
3. a **pure-Python solution**: No databases, no shell command executed from the Python script, ...
4. a **scalable solution**: the script should works with a small (10 000 lines), a big (100 000 lines) and a very very big file (10 000 000 lines)
5. a text file (.txt, .md, .rst) explaining how the code works and why you implemented it that way, keep it short if possible

#### Bonus:

1. your coding styles will be mostly compatible with PEP8 https://www.python.org/dev/peps/pep-0008/
2. writing unit test is a plus
