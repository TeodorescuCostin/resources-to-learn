# Introduction

#### Basic Structure of Computers

In this part of our documentation we will discuss the design and the functions of digital computers that store and process information.

Mostly we will discuss computer hardware and computer architecture. This means that we will learn about electronic circuits, a topic that is already familiar to us ( due to the [Reasoning an Logic](broken-reference) documentation ) magnetic and optical storage devices, displays, electromechanical devices but also about communication facilities.

While discussing the specifications and the concepts of a good architecture it will also be nice to keep in mind both hardware and software.

#### Computer Types

They were introduced in 1940 and since then digital computers have evolved into many different types of computers to satisfy our different needs. The differences may vary widely in size, cost, computational power and intended use.

Now that we've clarified the differences we should start looking at the types of computers:

* Supercomputers and Grid Computers
  * They usually offer the highest performance
  * They are usually used for high computations, usually for forecasting, engineering design and scientific work
  * They combine a large number of personal computers by evenly distributing the computational workload across the grid
* Server and Enterpries systems
  * This type of computers are tipically larger than Personal compuers
  * They are meant to be shared by multiple people that use a personal computers
  * They usually host databases or large applications&#x20;
* Personal Computers
  * This type of computers are intended to be used in every domain and by anyone
  * They support a variety of applications
  * They are classified by theier specifications:
    * Desktop Computes serve general needs but are not portable
    * Workstation Computers offer higher computational power and not portable
    * Portable and Notebook computers provide basic features and they are portable
* Embedded Computers:
  * This type of computers are the ones that are integrated into a larger device or system to automatically control and monitor its behaviour.
  * They are used for something specific and made efficient for only one use case
  * Some examples of electronics that contain this type of computers or products are:
    * Cars
    * Microwaves
    * Washing Machines
    * etc.

#### Functional Units

A computer consists of five functionally independent main parts: input, memory, arithmetic and logic, output and control units.

<figure><img src="../.gitbook/assets/FunctionalUnits.png" alt=""><figcaption></figcaption></figure>

The information recived it is either stored either in computer's memory for later user or for imediate used by the arithmetic and logic unit (ALU). The steps are specified by a program that is also stored in memory.

Informations handled by computer are treated either as instructions or data. Instrunctoins or machine instructions are explicit commands that:

* Govern the transfer of information within a computer
* Specify the arithmetic and logic operations to be performed

The program will be stored in the memory from where the processor will fetch it. The instruction that are in the program are going to be fetched one after the other and the processor will perfom them. The computer  is controlled by this program, except for possible external interuptions from I/O ( Input / Output ). Data is also going to be stored in the memory.

Computers can accept code informations through the input units. Keyboard is  good example, which sends the corresponding binary digit for the key pressed. There are many other input units, another example would be the touchpad which is included in most of the laptops.

Another input path would be the network. Through this a computer can recive data from another computer.&#x20;

In the past years computers had advance rapidly. Now all of the computers have two different types of memory units. This was specifically made due to the fact that they have different tasks.

One type of memory is Primary Memory, which can also be called main memory. This type of memory is very fast and because of this programs need to be stored on it while they are executed. The memory is made out of a large number of semiconductor cells more specifically ( semiconductor storage cells) each capable to store on bit. The storage cells are grouped in words so that they can called and changed much more efficient. The most common word lengths are:

* 16 bits
* 32 bits
* 64 bits

To facilitate easy access to the memory to any word a different address is asociated with each word location. Addresses are consecutive numbers starting from 0, that identify succesive locations. Usually a word is accessed by simply specifing its address.

