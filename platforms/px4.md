You have to have broad knowledge in embedded system in order to master the PX4 system, ranging from bare metal development on MCU, to Linux, C++ programming.

src/systemcmds	some handy commands can be used in Nuttx shell, they are defined by the need of the target application (px4 developers).

In short, NuttX is nothing but a small Linux operating system, in this case it's customized for PX4 needs and very suitable for flight control systems.
Again, but not overspeak, we need understand the system architecture, know what are the meanings of folders/modules in the system, because one cannot simply understand the whole files, every line of code without spending too much time. I take an example, you won't have to bother understanding what the heck is NuttX doing, all of its code and some weird programming stuctures, rather than that, you should understand where NuttX's files are, what are the roles of NuttX in this sytem, how to use NuttX effectively (like its features, commands that are obvious useful in developing the system). You know that when working to develop a embedded product, device driver developers have the same philosophy in their minds, because the Linux kernel is fucking large.

Let's dig into the main part, most of the time, researchers want to implement their own algorithms to the Pixhawk-PX4 system, how do they would do this? I think with the decent amount of time, and previous knowledge on embedded control system, they will eventually know how to by some heuristic methods and critical thinking.

This won't be too hard.

Also, if you're not doing something new, then probably there're a lot of people have done that, do the research, literature review, collect the documents and source code, study them, read academic papers.
I guess a lot of thesis have used matlab + develop the algorithm -> implement to PX4 system successfully.
