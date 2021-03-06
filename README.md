# SiReGen
A CRUD resource generator for Sinatra. Currently supports the creation of generic CRUD controllers given a model name.

## Installation
  This repo contains two files- siregen.rb and raketask. 
  
  * To run the runner file, pass in the model name as ARGV, as in:
  <pre><code> ruby siregen.rb user </code></pre>
  The runner file will generate the controller file with the proper name. It will be up to you to place it in the right directory.

  * To use the raketask, copy and paste its text into your Rakefile. The raketask assumes you have a directory called app/controllers. You may want to namespace the task with any other generation tasks you have, as in
  <pre><code> rake generate:controller NAME=user </pre></code>

  * the task will also work in isolation, as in
  <pre><code> rake controller NAME=user </pre></code>

ENJOY!
