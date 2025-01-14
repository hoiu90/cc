**exercise 1**

``bash
ls | grep '^[A-Z]'
``

**exercise 2**

``bash
ls ~/.[!.]* ~/?*
``

**exercise 3**

``bash
ls | grep '^.' |wc -l
``

**exercise 4**

``bash 
ls | grep '^[A-Za-z]'
``

**exercise 5**

``bash
ls | grep '^[^A-Z]*$'
``

**exercise 6**

``bash
ls | grep -v '\.[A-Za-Z0-9]\{3\}$'
``

**exercise 7**

``bash
ls /etc | grep '^c.*y$'
``

**exercise 8**

``bash
ls /etc | grep 's\{2\}'
``

**exercise 9**

``bash
^.[A-Z].[A-Z].e$
``

**exercise 10**

``bash
ls | grep '^[A-Za-z0-9]\{4\}$'
``

**exercise 11**

``bash
ls /var/log | grep '\.log$'
``
