# experiment-13

### Program Codes
1)
~~~ javascript
//Sharvari Murade
//23070123088
#include <iostream>
using namespace std;
//Parent Class
class Car {
public:
    string year;
    void car() {
        cout << "You have a Ford car." << endl;
        cout<<"Please enter year of purchase: ";
        cin >> year;
    }
};
//Child class
class Model : public 
Car {
public:
    void amaze() {
        cout << "Car model is Aspire bought in "<< year <<endl;
    }
};
int main(){
    Model st;
    st.car();
    st.amaze();
    return 0;
}
~~~
2)
~~~ javascript
//Sharvari Murade
//23070123088
#include <iostream>
using namespace std;

class College {
public:
    void college() {
        cout << "College Name: SIT, Pune " << endl;
    }
};

class Branch {
public:
    void branch() {
        cout << "Branch is ENTC" << endl;
    }
};

class Class : public College, public Branch {
public:
    void cLass() {
        cout << "Class is B division" << endl;
    }
};
int main() {
    Class c;
    c.college();  
    c.branch();  
    c.cLass();      
    return 0;
}
~~~
3)
~~~javascript
//Sharvari Murade
//23070123088
#include <iostream>
using namespace std;
class Subject { 
public:
    void speak() {
        cout << "Subject is C++ and Data Structures" << endl;
    }
};
class Experiment : public Subject { 
public:
    void study() {
        cout << "Experiment number is 13" << endl;
    }
};
class Topic : public Experiment { 
public:
    void research() {
        cout << "Topic for experiment is Inheritance" << endl;
    }
};
int main() {
    Topic exp;
    exp.speak();    
    exp.study();    
    exp.research(); 
    return 0;
}
~~~
4)
~~~ javascript
//Sharvari Murade
//23070123086
#include <iostream>
using namespace std;
class Class { 
public:
    char division;
    string name;
    void EB() {
        cout<<"Please enter your class: ";
        cin>>division;
    }
    void names(){
        cout<<"Please enter your name: ";
        cin>>name;
    }
    void display(){
        cout << "Student is in Mech-" << division << endl;
    }
};
class Student1 : public Class { 
public:
    void Name1() {
        cout <<"Student name is "<<name<< endl;
    }
};

class Student2 : public Class {
public:
    void Name2() {
        cout <<"Student name is "<<name<< endl;
    }
};
int main() {
    Student1 d;
    Student2 c;
    d.EB();  
    d.names();
    c.EB();  
    c.names();
    d.display();
    d.Name1(); 
    c.display();
    c.Name2(); 
    return 0;
}
~~~



### Program Outputs
1)<img width="308" alt="Screenshot 2024-09-15 at 9 27 30 PM" src="https://github.com/user-attachments/assets/29d28af4-e250-4426-8cb3-24f76f328aa0"><br>
2)<img width="304" alt="Screenshot 2024-09-15 at 9 34 16 PM" src="https://github.com/user-attachments/assets/d4fff890-ba99-440c-ac40-8a0b1385bb7a"><br>
3)<img width="310" alt="Screenshot 2024-09-15 at 10 20 28 PM" src="https://github.com/user-attachments/assets/3d4cda17-45a2-483c-b991-6fd94ec53210"><br>
4)<img width="317" alt="Screenshot 2024-09-15 at 10 44 14 PM" src="https://github.com/user-attachments/assets/ba6ad5a5-fd9c-499b-9c97-b504390bbde6">


