class diagram https://drive.google.com/file/d/1f0P_wkFjw5J9RrKS-dgi708kyUpO7b0h/view?usp=sharing

```
.cw-automated-test
├── readme
├── scripts
├── cypress    
│   ├── e2e        
│   ├── fixtures        
│   ├── support 
│   ├── classes                                          
│   │   ├── account                                    
│   │   ├── ...                                   
│   │   ├── cop
│   │   │   ├── learner
│   │   │   |   ├── folder-family...                          # extends lms/learner/my-learning                       
│   │   ├── lms                 
│   │   │   ├── admin 
│   │   │   ├── learner
│   │   │   |   ├── class-activity
│   │   │   |   |   ├── folder-family...                      # able to use for learner in cop and org lms
│   │   │   |   ├── class-detail
│   │   │   |   |   ├── folder-family...                      # able to use for learner in cop and org lms 
│   │   │   |   ├── course-detail
│   │   │   |   |   ├── folder-family...
│   │   │   |   ├── my-learning
│   │   │   |   |   ├── folder-family...
│   │   ├── lms-admin
           
```

    
