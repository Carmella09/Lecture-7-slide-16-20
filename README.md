# Lecture-7-slide-16-20-HW

 // Mark my Words
    
    using namespace std;
    int main()
    {
        int grade;
        cout << "Write your Grade: \n" << endl;
            cin >> grade; 

        if (!(grade < 70)) {
            cout << "Your grade is A " << endl; 
        }
         else if (!(grade < 60)) {
            cout << "Your grade is B " << endl;
        }
         else if (!(grade < 50)) {
            cout << "Your grade is C " << endl;
        }
        else if (!(grade < 40)) {
            cout << "Your grade is D " << endl;
        }
        else {
            cout << "Your grade is F" << endl;
        }
        cin.get();
        return 0;
    }

//Starting a Band (I think I did it wrong here and it keeps on giving error when I tried to copy the one on slides 18)
    
    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
      bool musicalFriend = true;
      string friendPlays = "guitar";
      string friendAlso = "drum";

      if (friendPlays == "guitar" || friendPlays == "Guitar") {
        cout << "Strings match" << endl;
      }
        else if (friendPlays == "drum" || friendPlays == "Drum"){
            cout << "Strings match" << endl;
      }
      else {
        cout << "String do not match" << endl;
      }
    }

// Killing time
   
       using namespace std;
        int main()
        {
            bool lessMinute = true;
            bool anotherMinute = false;
            bool haveMoney = false; 

            if (anotherMinute) {
              if (haveMoney)
                {
                cout << "Go buy coffee" << endl;
                }
                else
                {
                cout << "Go for a walk around the town." << endl;
                }
            }
             else {
             cout << "Sit in the food zone and wait." << endl;
           }
        }

//Earthquake 
    
    using namespace std;
    int main()
    {
        double magnitude;
        cout << "Write the Magnitude of the Earthquake: \n" << endl;
        cin >> magnitude;

        if (!(magnitude > 2.0)) {
            cout << magnitude << " is a Micro Earthquake" << endl;
        }
        else if (!(magnitude > 3.0)) {
            cout << magnitude << " is a Very Minor Earthquake" << endl;
        }
        else if (!(magnitude > 4.0)) {
            cout << magnitude << " is a Minor Earthquake" << endl;
        }
        else if (!(magnitude > 5.0)) {
            cout << magnitude << " is a Light Earthquake" << endl;
        }
        else if (!(magnitude > 6.0)) {
            cout << magnitude << " is a Moderate Earthquake" << endl;
        }
        else if (!(magnitude > 7.0)) {
            cout << magnitude << " is a Strong Earthquake" << endl;
        }
        else if (!(magnitude > 8.0)) {
            cout << magnitude << " is a Major Earthquake" << endl;
        }
        else if (!(magnitude > 10.0)) {
            cout << magnitude << " is a Great Earthquake" << endl;
        }
        else {
            cout << "is a Meteoric Earthquake" << endl;
        }
        cin.get();
        return 0;
    }
