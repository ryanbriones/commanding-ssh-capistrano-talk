# Commanding Your SSH Universe with Capistrano

* **Category/Track**: Languages -> Ruby, System Administration
* **Level**: Beginner (100)
* **Presentations**:
 * OSCON 2008 (Original)

# Short Description

Using Capistrano to automate SSH tasks such as server administration and application deployment.

# Abstract

What could be worse than having to manage and maintain application servers for a team of agile developers? Being on that team as a developer AND the systems administrator. A setup for one application might included a development server, a staging server, a cluster of production servers and one or two servers for version control and continuous integration. The fuse is burning at both ends for you and there is never time to waste. Meet Capistrano. Capistrano enables you to automate your many system administration tasks harnessing the ubiquity of SSH and the simplicity of a Ruby DSL configuration.

During this talk, we’ll take a look a some of my real world usage of Capistrano in my job as a web application developer and system administrator. I’ll demonstrate how to free yourself from the monotony of login-execute-logout method by creating a few simple Capistrano tasks, covering the basics of configuration and usage. We’ll also examine how Capistrano runs a task in parallel on multiple remote servers by creating a simple Rails application deployment using a standard Apache Proxy/Mongrel Cluster setup and touch on a few “advanced” recipes.
