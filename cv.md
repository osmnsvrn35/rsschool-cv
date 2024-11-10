# Osman Can SAVRAN
## Contact
**Email:** osmancansavran@gmail.com\
**LinkedIn:** [https://www.linkedin.com/in/osman-can-savran-bb90721ba](https://www.linkedin.com/in/osman-can-savran-bb90721ba)  
**Phone:** +48 575 065 xxx
## Summary
- Passionate about becoming a full-stack developer with a strong interest in the architecture and design of web applications.
- Engaged in learning both front-end and back-end technologies to understand the full development process.
- Enjoy solving algorithmic problems on LeetCode, sharpening my skills in data structures and efficient coding.
- Driven to build efficient, scalable applications by deepening my knowledge of technology stacks and software architecture.
## Skills
- C, C++, C# PROGRAMMING LANGAUGES
- Python
- Html, CSS, Javascript
- React 
- Django
- Git
- Java
- Azure
- REST API
- MS SQL Server
- PostgreSQL
## Code Examples
```cpp
    vector<int> topKFrequent(vector<int>& nums, int k) {
        
        vector<int> res;

        if(nums.empty()){
            return res;
        }

        priority_queue<pair<int,int>, vector<pair<int,int>>, greater<pair<int,int>>> pq;
        unordered_map<int,int> m;
        for(auto num : nums){
            m[num]++;
        }

        for(auto &item : m){
            pq.push({item.second, item.first});
            if (pq.size() > k) {
                pq.pop();
            }
        }        
        
        while(!pq.empty()) {
            res.push_back(pq.top().second);
            pq.pop();
        }

        reverse(res.begin(), res.end());
        return res;
    }
```

## Experience

### Bulba
- **Position**: Software Engineer Intern
- **Duration**: August 2024 - October 2024

#### Key Experiences:
- Developed a **machine learning data pipeline**, fetching and structuring user data using Instagram Graph API to enable meaningful insights.
- Created and managed a **PostgreSQL database** to store and process large volumes of public Instagram user data, employing ad hoc methods to optimize data retrieval and storage.
- Gained hands-on experience in **data design** and **production code** development, enhancing my skills in database management and data-driven applications.


### Agent Systems Project: Agent Coalitions
- Developed a self-organized system using agent-based methodologies with the JADE framework.
- Gained hands-on experience in Java programming and software development methodologies, such as GAIA.

### Bike Reservation Web Application
- Built a web application for managing bike reservations using Django.
- Enhanced front-end skills with HTML and CSS, contributing to a seamless user interface.

### Flat Renting Mobile Application
- Created a mobile application with backend support and an admin page to facilitate flat rentals.
- Utilized React Native for front-end development.
- Integrated various APIs, marking my first experience with backend interactions and API handling.

### AI-Based Face Detection and Age Prediction Project
- Designed a convolutional neural network (CNN) model using Keras and TensorFlow for facial image classification.
- Preprocessed a large dataset, addressed class imbalance with SMOTE, and improved model performance through data augmentation.
- Developed a GUI with Tkinter and OpenCV for real-time face detection and age prediction.


## Education

**Warsaw University of Technology**  
*2020 - 2025*  
Bachelor of Computer Science and Information Technology  
- Studied core programming concepts and software development methodologies.
- Completed elective courses on:
  - **Multilayered Applications**: Focused on using React for frontend development.
  - **Mobile App Development**: Covered full-stack mobile development principles.
  - **Web Application Development**: Learned HTML, CSS, JavaScript, and Django for building responsive web applications.
  - **Machine Learning**: Gained foundational skills in ML algorithms and data preprocessing.
  - **Agent Systems**: Explored agent-based systems and autonomous systems design.

**Additional Online Courses and Certifications**  
- **Azure Cloud Fundamentals** (Online Learning)  
  - Acquired foundational skills in cloud computing and Azure services.

- **Hands-on Software Engineering Course** – Kreativstorm  
  - Developed practical software engineering skills, focusing on hands-on projects and industry practices.

- **Node.js Development Course** – RS School (I did not complete)  
  - Gained in-depth knowledge of back-end development using Node.js, with hands-on experience in building scalable server-side applications.

  ## Languages

- **Turkish**: Native language
- **English**: C1 level
  - Cambridge KET Certificate (2014)
  - Vistula University B2 Certificate (scored 88%)
  - TOEIC: 845/990
  - Studied university courses in English
  - Passed Politechnica Warszawska C1 Exam
- **German**: A1 level 
  - Studied German for 1 year in high school
  - Completed a 30-hour German course at university
- **Polish**: A1 level
  - Completed a 90-hour Polish course at university











