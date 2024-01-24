[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name: Leoniide Tael
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: 
#include <iostream>
#include <string>

class Car {
private:
    std::string model;
    int year;
    std::string color;

public:
    void setModel(std::string m) {
        model = m;
    }
    std::string getModel(){
        return model;
    }

    void setYear(int y) {
        year = y;
    }
    int getYear() {
        return year;
    }

    void setColor(std::string c) {
        color = c;
    }
    std::string getColor() {
        return color;
    }

    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }
};

int main() {
    Car myCar;

    myCar.setYear(2018);
    myCar.setColor("Blue");
    myCar.setModel("Honda");

    myCar.displayDetails();

    return 0;
}


#include <iostream>
#include <string>

class Car {
public:
    std::string model;
    int year;


    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }
};

int main() {
    Car myCar;


    myCar.displayDetails();

    return 0;
}

```
