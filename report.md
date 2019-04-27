# INFSCI 2560 FINAL PROJECT

### Team Member: Yuyao Chen(yuc117), Shuo Jin(shj42)

## 1. Introduction

This project is designed and implemented with our team members: Yuyao Chen and Shuo Jin. The main concept of this project is a blog system, which contains multiple users and several features and functions, including blog, comments, likes, rating, search, image and information aggregation. This project is done with java, spring boots, bootstraps, and javascript. Finally, we set up the entire system and deployed with AWS EC2, rds and MongoDB Altas.

## 2. Objective

 This project is designed for multi-users to write a blog, share their opinion and connect with other users. The admin will focus on user management, and general users can create a blog with image and word content, view other blogs and vote them. They also can write comments for the new blog, and reply to others comments.
In this application, there are several features, including fuzzy search, ranking article, ranking users, group users and article by tag. We want to design and implement a full blog system based on Java and spring boot due to we would love to learn something new beyond the classes and requirements. Also, we tried to combine MySQL and MongoDB instead of only use one for the blog system.

## 3. Contribution

Since we do only have two members for this project, we divided the entire project into two parts. The frontend, which is implemented by Shuo jin, includes the whole user interface and fundamental interactions with users. The frontend provides the function with sign up, log in, and authority for edit specific content of the blog. We are using bootstrap for the entire system with a responsive and consistent design. Because of the different type of user, they will have a different view after login to the system. In the backend, which is implemented by Yuyao Chen, use Java as the primary language for the entire development of backend. In this part, use Gradle instead of maven for better performance, use Elasticsearch for searching in the whole system including user, content and even fuzzy search. Use spring boot JPA for connecting and operate database efficiently. All the system are developed by the local machine and deployed using AWS service.

## 4. Technical Architecture

Since spring boot is the core framework of the entire system, the MVC structure will be based on the spring. In the spring MVC framework, the models are the Dao and bean, which means it is convenient to access the database and make the operation with the database, like the curd operations. The view layer is controlled by the controller layer, which is the servlet in spring framework, using the ModelAndView to combine the models and view layer, and the servlet use view resolver to provide a specific object to the view layer, which help us to display the correct data with right page.


## 5. Challenges

There are three significant challenges since we did a blog system. The first one is the environment, because we want to learn some new things, how to combine these different techniques into one system is the first challenge we faced. Because of the version, we have to solve several bugs which had not seen before. The second challenge is the challenge of data. Because this is a blog,  we do not have so many users. We have to collect data from the website, but it is hard to test for the features like workload balance and other performance. The last big challenge is system performance. We plan to use aws ec2 as the host for the blog system, but while we are testing the function, the ec2 system breakdown because of the limited performance, also, spring boot and Elasticsearch requires too much source of the system. If we do not want to use spring boot in this project, other light-weight frameworks like Flask, bottle are also an excellent choice to be the alternative solution for this project.

## 6. Future Work

In this project, we have complete the following function: sign up, log in, multi-user, write a blog, blog operations, comments, reply, likes, vote, tag, search and group aggregation. Due to the time limitation, we do not make this project as a perfect one. The recommendation system, share function and payment function are the three features we plan to add to our system in the future. If these functions are combined into this blog system, it will be a completed system for people who love to share with others.

## 7. Conclusion

In this web technologies and standards class, we have learned a lot from both readings and activities. It is a great chance to improve our technique in both front-end and back-end. We have not too much experience of javascript before, but since this class, we learned some primary usage of javascript, which is useful. It is believed that the javascript framework could be used in all kinds of the field because of its advantages, such as tensorflow.js which is more light-weight but still robust as the typical tensorflow framework. Others like memory database could also be a great future technology because of the development of the hardware.

## 8 acknologement

Thanks to our instructor, matt, to his teaching and feedback for the entire semester. He has broadened our horizons with many aspects of knowledge of web technology. 

