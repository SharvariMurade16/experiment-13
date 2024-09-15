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





### Program Outputs
1)<img width="308" alt="Screenshot 2024-09-15 at 9 27 30 PM" src="https://github.com/user-attachments/assets/29d28af4-e250-4426-8cb3-24f76f328aa0"><br>
2)<img width="304" alt="Screenshot 2024-09-15 at 9 34 16 PM" src="https://github.com/user-attachments/assets/d4fff890-ba99-440c-ac40-8a0b1385bb7a">

