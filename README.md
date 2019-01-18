# Spring-Boot-RestServices-Microservices-All-Examples
Different scenarios of all RestServices using Spring Boot and Microservices


REST stands for REpresentational State Transfer. REST specifies a set of architectural constraints. Any service which satisfies these constraints is called RESTful Service.
The five important constraints for RESTful Web Service are
Client - Server : There should be a service producer and a service consumer.
The interface (URL) is uniform and exposing resources.
The service is stateless.
The service results should be Cacheable. HTTP cache, for example.
Service should assume a Layered architecture. Client should not assume direct connection to server - it might be getting info from a middle layer - cache.
=====================================================================================================================================
Rest Services in this Guide
In this guide, we will create three services using proper URIs and HTTP methods:
@GetMapping("/students/{studentId}/courses"): You can ask the courses a specific student has registered for using request method Get and example uri /students/Student1/courses.
@GetMapping("/students/{studentId}/courses/{courseId}"): You can ask a specific course for a specific student using request method Get and example uri /students/Student1/courses/Course1.
@PostMapping("/students/{studentId}/courses") : You can register a student for a course by sending a POST request to URI /students/Student1/courses
