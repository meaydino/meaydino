<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&pause=1000&color=00F5D4&center=true&vCenter=true&width=600&lines=Mehmet+Aydın;42+School+Student;System+%26+Low-Level+Dev" alt="Header" />
</h1>

<p align="center">
  <a href="https://instagram.com/mehmetwayd" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-18181B?style=for-the-badge&logo=instagram&logoColor=F43F5E" alt="Instagram"/>
  </a>
  <a href="https://github.com/meaydino" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-18181B?style=for-the-badge&logo=github&logoColor=00F5D4" alt="GitHub"/>
  </a>
</p>

<br/>

```c
/* meaydino.c */
#include <stdio.h>

typedef struct s_developer {
    char *name;
    char *school;
    char *core_stack[3];
} t_dev;

int main(void) {
    t_dev me = {
        .name = "Mehmet",
        .school = "42",
        .core_stack = {"C", "C++", "Unix/Linux"}
    };
    return (0);
}
