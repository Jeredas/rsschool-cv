# Uladzimir Kamarou #  
### 27 years old ###  


*Contacts:*  

Leningradskaya street 18,apt 16, Vitebsk 210001, Rebuplic of Belarus, 
efioss93@mail.ru , +375(29)-210-72-16 , https://vk.com/funny_dude  

---
*Education* :  
**Polotsk State University**, Novopolotsl,Repuplick of Belarus.   *2015-2020*.  
**Builder-engineer**,Bachelor of Industrial and Civil Building.(PGS in russian)  

**Vitebsk State Technical Collage**, Vitebsk , Republick of Belarus.   *2009-2013*  
**Technician** of Industrial and Civil Building.(PGS in russian)  

---
*Military service*:  
Air Defence Troops 2013-2015  

---
*Work experience*:  

**Optic-fiber splicer** in LCC"Promenergostroy", 2016-2018  
**Foreman GC** in LCC "Plissastroy",2018~...  


---
*Qualifications :*  
Python, JavaScript, HTML, CSS, React.js, Redux, Node.js, Git.
In august 2020 started to learn Python by free online courses. Made some easy pet projects such as weather bot for telegram, and cosole games.
In December 2020 started to learn HTML, CSS, JavaScript, Node.js React, Redux. Now developing social network on React.js for getting experience.
English level is B2(upper-intermediate).  

---
*Objective :*
Main objective is to switch my profession and get real experience in front-end development.  

---
*About myself:*  
Sociable - easily find a common language with anybody, responsible - having large expirience beeing foreman(worked with customers, inspections and regulatory authorities,
material reports), punctual, motivated. 

--- 

*Code examples:* 

Coded on Python 

Сhecks if a class inherits from another using graphs 
```from collections import deque
def search(list):
    if list[0] == list[1]:
        return True
    search_queue = deque()
    if list[1] not in graph:
        graph[list[1]] = []
    search_queue += graph[list[1]]
    searched = []
    while search_queue:
        parent = search_queue.popleft()
        if not parent in searched:
            if is_parent(parent):
                return True
            else:
                search_queue += graph[parent]
                searched.append(parent)
    return False
def is_parent(name):
    if k[0] in name :
        return True
    else:
        return False
n = int(input())
graph = {}
for i in range(n):
    s = input().strip().split(':')
    if len(s) > 1:
        if s[0].strip() in graph:
            s[1] = s[1].replace(' ','')
            for i in range(len(s[1])):
                graph[s[0].strip()].append((s[1][i]))
        else:
            graph[s[0].strip()] = s[1].split()
    else:
        graph[s[0]] = []
j = int(input())
for i in range(j):
    k = input().split()
    if search(k) == True:
        print('Yes')
    else:
        print('No')```
