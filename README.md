# ECE444-F2020-Lab2
Student Name: ZIAN HU

This repo is a clone of https://github.com/miguelgrinberg/flasky

## Activity 1 Screenshot:
<p align="center">
  <img src="./screenshots/Activity1Screenshot.png" />
</p>

## Activity 2 Screenshot:
<p align="center">
  <img src="./screenshots/Activity2Screenshot.png" />
</p>

## Activity 3: Briefly summarize what are the Flask context globals
Flask context globals help to prevent cluttering new functions with a lot of arguments that may or may not needed. Lots of
relevant information can be grouped into one context variable, enabling more concise code. 
One key feature of these context globals is that in a multithreaded server, they can temporarily make certain objects globally accessible in a thread-safe way without interfering with
the other threads. There are two types of contexts in Flask: the application context, which includes 
`current_app` and `g`, and the request context, which includes `request` and `session`.