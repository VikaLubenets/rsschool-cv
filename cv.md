# **Viktoriya Lubenets**

## **Junior Frontend Developer**

*********

## **Contact information:**

**Phone:** +995 599 72 96 13

**E-mail:** lubenetcvika@gmail.com

**Telegram:** @vikalubenets

[LinkedIn](https://www.linkedin.com/in/viktoriya-lubenets-1900a325b/)

**************

## **Briefly About Myself:**

Working 5 years as an international project lawyer, I realized that my big passion is to affect on the result of the project instead of doing documentation to formalize it.

Considering this, I'd decided to test different fields of IT work and chose front-end development as the most interesting and visual job providing endless possibilities for professional growth, using free high-quality resources for self-education.

Surprisingly for myself I found out a lot of common features between front-end development and being a lawyer, including the necessity of long learning, being patient to details, logic and high quality of written work.

Hope my love to learnlearning will help me to develop needed skills and become a proficient Frontend Developer.

************

## **Skills and Proficiency:**
* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code

***********

## **Code example:**
**Lab 1 “Population” from CS50 course:** 

Say we have a population of n llamas. Each year, n / 3 new llamas are born, and n / 4 llamas pass away. Complete the implementation of population.c, such that it calculates the number of years required for the population to grow from the start size (not less than 9) to the end size (determined by user). 

```
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    // TODO: Prompt for start size
    int i;
    do
    {
        i = get_int("Start population: \n");
    }
    while (i < 9);

    // TODO: Prompt for end size
    int j;
    do
    {
        j = get_int("End population: \n");
    }
    while (j < i);

    // TODO: Calculate number of years until we reach threshold
    int years = 0;
    while (i < j)
    {
        i = i + (i / 3) - (i / 4);
        years++;
    }
    // TODO: Print number of years
    printf("Years: %d\n", years);
}

```

**********

## **Courses:**
* Introduction to Front-End Development by Meta on Coursera.org (in progress)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
* CS50’s Introduction to Computer Science from Harvard (in progress)

*************

## **Languages:**
* English – B2
* Russian - Native
* Spanish – A1


