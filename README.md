# Get Started

# Micro-services
<p>
  Microservices, in simple terms, are a way of designing and building software applications as a collection of small, independent, and specialized components that work together to provide a complete service or application. Imagine these components as tiny, self-contained building blocks that can be developed, deployed, and scaled independently.

Each microservice is responsible for a specific function or feature of the application, such as handling user authentication, processing payments, or managing user profiles. These individual microservices communicate with each other through well-defined interfaces or APIs (Application Programming Interfaces).
</p>

# Why 
<h3>Scalability</h3>
<p>
  it's easier to handle increased demand for specific functionalities without affecting the entire application
</p>
<h3>Flexibility</h3>
<p>
  Different teams can work on different microservices simultaneously, using different technologies and programming languages if needed
</p>
<h3>Fault Isolation</h3>
<p>
 If one microservice fails, it doesn't necessarily bring down the whole application. The impact is limited to that specific functionality.
</p>
<h3>Innovation and Speed</h3>
<p>
 Teams can develop and deploy new features independently, allowing for faster innovation.
</p>

<img src="https://content.altexsoft.com/media/2016/11/the-difference-between-the-monolithic-and-microser.png"/>

<ul>
  <li>
    <p>
      Micro-services are run as separate process
    </p>
  </li>
  <li>
    <p>
      Consequently, we have to setup a separate project/repo  for each services  and configure  a xlient  for any  process that would  like  to use  the services
    </p>
  </li>
</ul>

# Using TCP 
<img src="https://miro.medium.com/max/4508/1*VhwC_8dSe3m0T06hh2yT8g.jpeg"/>

# Client Nest Project
<p>This is the front-end or user interface of your application. It's what users interact with directly. It could be a web application, a mobile app, or any other user-facing interface.</p>

#  Microservices Nest Project
<p>This is the backend of your application, built using the microservices architecture with the Nest.js framework. In this architecture, different microservices handle specific functionalities, such as user authentication, data processing, and more.</p>




