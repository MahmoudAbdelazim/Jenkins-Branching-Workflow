# Jenkins-Feature-Branching
A project for testing Jenkins features and applying CI concepts on GitHub Branches.

The project consists of 3 branches, feature_1, feature_2, and feature_3, with feature_3 being buggy.

This is the Jenkinsfile for configuring the pipepline for each branch:
![image](https://user-images.githubusercontent.com/43009893/197789359-11a380b7-cc5d-47f7-be2c-778b4c4968fc.png)

When the 3 features were pushed to the remote repository, Jenkins scanned the project and ran the pipeline stages on each one:

![image](https://user-images.githubusercontent.com/43009893/197789662-bcf152b8-7833-4f76-bc73-d745e8b8fe6a.png)

Feature 1:
![image](https://user-images.githubusercontent.com/43009893/197789737-c24e3c90-73b4-4eaa-9784-7a982c44a169.png)

Feature 2:
![image](https://user-images.githubusercontent.com/43009893/197789817-bb0f9fdc-df1f-4702-b3f3-0637f98f6b88.png)

Feature 3:
![image](https://user-images.githubusercontent.com/43009893/197789881-8e927d79-aaed-47d7-9a35-5c5c9584e11f.png)

This approach can be used to automate the process of unit testing and integration testing and any other testing or analysis behavior whenever a new feature or and update is added to any branch in the repository, allowing the project owner to make the right decision either to merge the branch into the main branch or not.
