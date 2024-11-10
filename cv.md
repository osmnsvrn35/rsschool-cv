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


  






