![example workflow](https://github.com/fourth-idiot/test/actions/workflows/main.yml/badge.svg)

# Ira : The e-learning platform
Course project for the graduate level course CEN5035 - Software Engineering.

## Team Members
* Bodke, Gauri Pandharinath
* Hadkar, Prasad Ramakant
* Lawande, Swara Jitendra
* Saoji, Nikhil Mukesh

## Project Topic and Motivation
Ira will be an e-learning platform. Name of the platform *Ira* comes from the name of Hindu goddess Saraswati (Goddess of wisdom and knowledge). Using this platform, instructors can share their knowledge with the world without worrying about the difficulties involved in hosting a platform of their own. On the other hand, students can learn at their own pace, have lifetime access to the courses, select courses from the plethora of available options, and can gain knowledge about wide range of topics as per their interests.

## User Roles and Corresponding Functionality:
### Guests (Without login):
* Can view course information page and watch introductory video
* Can view instructor information page
* Search a particular course using keywords
* Filter courses according to course type, difficulty level, course duration, etc.
* Sort courses according to price, rating, number of enrollments, etc.

### Students
* Can update their personal details
* Can view the list of enrolled courses and corresponding progress
* Add courses to the wishlist/cart
* Purchase courses added in the cart

### Instructors
* Can update their personal details and information page details
* Can view the list of draft/published courses. For the list of published courses, they can view the course statistics in terms of student enrollements, revenue generated from the course, etc.
* Create a course. A course will have a course content made using the combination of three components (Video/Text/Quiz), a list of external resources for each module, and a discussion page
* Apply a promo code for the course

### Administrator
* Total number of users (student + instructor) of the application
* Number of requests served

## Technology Stack
* Backend : Golang
* Frontend : Angular 2+
