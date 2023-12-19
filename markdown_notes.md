# heading
## heading 2
### heading 3
_Italic_ 

**strong**
~~1000~~ **999**

Links
[visit Website](https://www.google.com "google link")


images
![google](google.png)

use `loop` here

<button class="copy-button" onclick="copyToClipboard()" style="background-color: #4CAF50; color: white; border: none; padding: 5px 10px; font-size: 16px;  cursor: pointer;" >Copy</button>


```yml

---
- name: Command Line Variable Example
  hosts: RHEL
  become: true
  tasks:
      - name: Adding user and applying the password
        user:
            name: "{{ user_name }}"
            state: present
            password: "{{ password }}"
...

```


table

|h1|h2|h3|
|:---|:---|:---:|
|one | two | three|
|one | two | three|

> keep smiling and work harder

--- 
1. list one 
2. list two 
1. list three
+ list four
    1. one

***


this is paragraf  
how to insert new line

this is 

==highlighted==

- [ ] check box 
- [x] checked check box 
