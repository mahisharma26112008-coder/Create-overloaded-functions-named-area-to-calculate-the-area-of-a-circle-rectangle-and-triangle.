# Create-overloaded-functions-named-area-to-calculate-the-area-of-a-circle-rectangle-and-triangle.

#include<iostream>
using namespace std;

    void area(float r){
        cout<<"area of circle :"<<3.14*r*r<<"\n";
    }
    void area(int length, int breadth){
        cout<<"area of rectangle :"<<length*breadth<<"\n";
    }
    void area(float base, float height){
        cout<<"area of tringle : "<<1/2*base*height<<"\n";
    }
    int main(){
        
        area(4);
        area(20,20);
        area(20,30);
    
    return 0;
}
