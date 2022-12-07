# Vitaliy Rudakovskiy

## Contacts 

* **Discord**: SkorpiON_4Eg
* **E-mail**: vitalikrud03@gmail.com
* **Phone**: +375 (29) 905-72-32
#

## About me

I am 19 years old, I study at the university. The studying seems to be simple and I have a desire to gain some useful experience in my leasure time. Working with the field of front-end developing unlocks great opportunities, and what is more important, it requires not only technical skills but some creativity too. 

_My strengths that can help during studying:_
   - Ability to learn quickly
   - High concentration
   - Craving for new knowledge
#
## Skills

- HTML (basic knowledge)
- Git, GitHub
- C++ (Fundamentals, OOP)
- C# (Fundamentals, WinForms)
- MySQL (basic knowledge)
#
## Code example

An example from the project connected with the realization of **String** class in **C++**. The function _overloads an operator_ '>>'. 
```
std::istream& operator >>(std::istream& in, String obj)\
{
	char* buffer = new char[101];
	in.getline(buffer, 100);
	delete[] obj.my_string;
	obj.length = strlen(buffer);
	obj.my_string = new char[obj.length + 1];
	strcpy(obj.my_string, buffer);
	delete[] buffer;
	return in;
}
```
#

## Education

- ***University***
   - Belarusian State University of Informatics and Radioelectronics***
      - Faculty of Computer-Aided Design
- ***Courses***
   - \#SimpleCode C++
   - \#SimpleCode C#
#

## Languages

- **Russian** - native speaker
- **English** - between B1 and B2 (according to [EFSet](www.efset.org) online test)
- **French** - A1