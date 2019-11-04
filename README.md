Rendering with Asynchronous Actions
========================

This is the back-end portion of the _Rendering with Asynchronous Actions_ blog example.

## Description
Rendering with Asynchronous Actions is a code example for Samuel Guo's [blog](https://medium.com/@guosamuel1114). This is specific to the blog titled _Rendering with Asynchonous Actions_. This is the back-end portion of the example for the sole purpose of demonstrating potential bugs where rendering is dependent on data from the results asynchronous actions.

## Framework
Built with [Ruby on Rails](https://rubyonrails.org/)

## Installation
1. Fork and clone this repository into your local computer.
2. Navigate to the directory where it was cloned and run the following command: `bundle install`
3. When the `bundle install` command completes, run the following command: `rails db:migrate`

## How To Use
To run the back-end, run the following command: `rails s -p 4000`

***Note:*** For the back-end, the port needs to be assigned to port 4000 because port 4000 is the default port the front-end will refer to.

## Front-End Installation
After successfully installing the back-end, please refer to the [Rendering with Asynchronous Actions Front End repository](https://github.com/guosamuel/rendering_with_asychronous_actions_front_end) for instructions on how to install the front-end as well as using the application.
