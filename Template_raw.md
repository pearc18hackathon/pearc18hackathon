# PEARC 2018 Hackathon Template

## Contributors
 * Name
   * Institution
   * Contact Information
 * Name
   * Institution
   * Contact Information
 * Name
   * Institution
   * Contact Information
 * Name
   * Institution
   * Contact Information

## Project
  The name of your project goes here!

## Project Description
  A short introduction to the project - can be a copy of project description provided by Hack leaders.

## Description of Installation 
  Where is this to be installed or deployed? Any general information that would help relate this to other builders?

## Known dependencies
   Any known requirements for deploying - OS, libraries needed, versions, etc.

## System Information
  * Operating System
  * Flavor/version/build/kernel
    * Mac - Check the Apple -> About this Mac
    * Windows - Start -> 
    * Linux - 
      ` cat /proc/version`

CPU info 

  `cat /proc/cpuinfo | grep -m 1 "model name"`

Number of cores

  `cat /proc/cpuinfo | grep "model name" | wc -l`

CPU Microarchitecture

  For finding issues specific to certain compiler optimizations

  `gcc -march=native -Q --help=target|grep march`

Available RAM

  This is helpful for comparing performance or 'runnability' of certain scripts on which machines

  `free -m -h`

File system info

  This may be relevant for issues that pertain specifically to network file systems, solid state drives, etc
  * `df`
  * `mount`
  * `diskutil list #on Mac `

File system space

  How much disk space is available where the project will be deployed? 

Resource manager/ Job Scheduler

  I.e., SLURM, Torque, Grid Engine, and version thereof


C/C++ Compilers
  * `icpc -v`
  * `echo $CC`
  * `icpc -v`

Programming Language builds and versions
  * python --version 
  * conda --version
  * perl -v 
  * javac -version
  * php, etc

Software environment

  Other details, such as relevant libraries and software stack

  * Docker/singularity
  * Modules/softenv/etc

Other system details?

# Implementation/Deployment

## Steps taken
This may be as verbose as you like, but it should be sufficient in detail to allow a person who is relatively familiar with the environment you are deploying in to follow your steps successfully. Do not leave out important middle steps even if they seem obvious to you. Do not include dead-ends; place information about what did not work in the Troubleshooting section.

## Troubleshooting
This section is for pain points, trip-ups, failures due to missing dependencies, permissions, etc. Anything you would expect another developer to run into, place here. Organize each pain point in terms of when in the process it was encountered, what errors you saw, and how to solve it.

## Other notes/flailing/tips/tricks.
