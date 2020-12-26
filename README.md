
```cpp
#include <iostream>
using namespace edwin;

class About{

  private:
    string name;
    char location[20] = "Nairobi, Kenya;

    void setName(string name){
      name = "edwinmwiti";
    }

  public:
    string current_project = "competitive programming";
    char technologies[5] = {"C", "C++", "Python", "Javascript", "PHP"};
};

class Others{
  char other_technologies = {"Arduino", "IOT", "ROBOTICS"};

  void reachMe(){
  string use_email = "emwiti658@gmail.com";
 }

};

int main(){
    About me;
    me.setName();
    
    return success;
}
```

💬 _Did you know:_ There are two ways to write error-free code. Only the third works!

