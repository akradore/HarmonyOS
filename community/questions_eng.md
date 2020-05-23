#### When did you start researching and developing Hongmeng?



Huawei started exploring Hongmeng 10 years ago. Now the manpower input is close to 5000 people, and the entire system must be improved in a short time, so the workload is very large.

#### What does the name Honghong System mean?



Hongmeng may have the meaning of 'opening the earth' in Chinese. The closest English word is Genesis, which means opening the earth. Expressing Hongmeng in Pinyin is too difficult to pronounce. It is named Harmony, hoping to bring more peace and convenience to the world.

#### What are the main features of Hongmeng OS?



Four characteristics: distributed architecture, natural fluency, kernel security, and ecological sharing. Hongmeng OS implements modular decoupling on a distributed architecture, allowing flexible deployment of different devices. The distributed soft bus core technology is used to simplify the presentation layer, session layer, transport layer and network layer into one layer, which can improve the payload. It also improves IPC performance in many ways and improves communication efficiency between processes by a factor of five.

#### What is a full scene?



According to the design of Hongmeng OS architecture, the system can run on various devices such as smart screen, wearable, car, stereo, watch, mobile phone, PC and so on. 

Through a set of systems, an OS realizes modular decoupling, which can be deployed flexibly corresponding to different devices. No matter the hardware capabilities are strong or the hardware capabilities are weak, a set of operating systems can be used to load and deploy on different hardware platforms.

At the same time, the application of powerful and flexible unified deployment capabilities, our set of OS can run on different hardware capabilities for deployment, adapt to a rich operating system in the era of Internet of Things IoT era capabilities.

#### Can the Hongmeng system be used on smartphones?



Hongmeng is fully commercialized and mobile phones of the Hongmeng system can be shipped at any time. We are also fully prepared. But we still hope to continue to use the global open mobile operating system and ecology. In other words, an open Android system and ecology are still our first choice. Hongmeng can be used in wearable devices, car machines, and PCs in the future.

#### What is a distributed architecture?



At present, all of our current mainstream OS architectures are centralized, that is, the OS of your mobile phone and the OS of your smart TV are independent of each other. Apart from sharing the data in the background, there is no connection.

For example, even if you open an app on your mobile phone and smart TV at the same time, the current implementation is running separately. The operation of your mobile phone will not affect the operation of the APP on the smart TV unless the data saved in the background is changed.

And Huawei's distributed OS can achieve collaborative processing of applications. Your operation on the mobile phone can be reflected on the APP interface of the smart TV at the same time. When the mobile phone closes the APP, the APP on the TV also closes. This is the collaborative processing of multiple terminals. Hongmeng OS can manage multiple terminals in a unified manner and jointly implement a certain function.

#### What is a microkernel and what are its characteristics?



The so-called microkernel is of course relative to the macrokernel.

The microkernel is a simplified version of the kernel that provides the core functions of the operating system. The microkernel only provides basic system running capabilities and provides a message interaction mechanism for different programs / processes.

The macro kernel is equivalent to a big supervisor, providing very comprehensive system operation functions, such as time management, memory management, file management, network management, etc. Android is a macro kernel OS.

 

The advantage of the microkernel is that the system runs efficiently, the system is more robust, and it is not prone to problems. The biggest problem of the microkernel is that the efficiency of message interaction between processes is not high. If there are many messages interacting at the same time, there may be message loss and retransmissions that cause the system to slow down.

The macro kernel does not have the message communication problem of this process interaction. The system function of the macro kernel resides in the kernel and memory, and the execution efficiency is indeed higher. However, the more and more functions of the macro kernel will make the system more and more redundant, and the requirements for the system hardware are very high, and the internal modules are too redundant, and maintenance and debugging are becoming more and more difficult.

Therefore, the macro kernel OS system is not suitable for some lightweight applications, such as the Internet of Things. Google is also researching the OS of the microkernel itself. In order to create a unified OS for the interconnection of all things, the OS of the microkernel is necessary. But Huawei's Hongmeng OS is faster than Google's Funchsia, because Hongmeng will soon be commercialized on the Honor Smart Screen.

#### How does Hongmeng OS achieve low latency and high performance?



Hongmeng OS solves the problem of insufficient performance of existing systems through the use of two technologies: deterministic delay engine and high-performance IPC. As we said earlier, the microkernel OS may have a large number of inter-process message communication. When a large number of inter-process messages swarm up, a large number of messages are blocked and the system performance is degraded.

 

This feature of Hongmeng OS is to solve this problem. Hongmeng OS internally prioritizes different process messages, uses professional scheduling algorithms to reasonably schedule communication messages between processes, high priority applications are guaranteed priority, and low priority applications are queued.

This mechanism makes the communication between the microkernel processes orderly, without the phenomenon of message loss caused by everyone swarming. In fact, this scheduling mechanism based on priority messages has long been used in Huawei's high-end communication equipment, such as router equipment, but this mechanism is only used in Hongmeng OS.

#### Why is Hongmeng OS more secure?



 

Hongmeng OS adopts micro-kernel design, the micro-kernel itself is much more robust and secure than the macro kernel. The basic idea of ​​microkernel design is to simplify kernel functions, so there is no coupling with system functions, making the entire system relatively robust.

The macro kernel integrates many system functions. The more complex the function, the more complex the system. Although the communication efficiency of the system functions has been improved, the complexity of the coupling makes the system's failure rate higher, which is the characteristic of the macro kernel OS.

 Huawei's Hongmeng OS is based on a microkernel, so it can make the entire system more robust without affecting the stability of the entire system because of attacks on system functions. At the same time, Huawei's advanced verification test algorithm can ensure that the entire OS is more secure and the system is more stable when it is attacked.

#### How does Hongmeng OS improve development efficiency?



Hongmeng OS supports multi-terminal development IDE and multi-language unified compilation. That is, developers can generate APPs running in different types of terminals at one time. This strategy is closely related to Hongmeng's strategy of deploying across multiple terminals. If different terminals of the same application need to be recompiled and adapted, then this is typically unfriendly to developers.

 

That is to say, if the developer's application needs to be used in mobile phones, vehicles, and Internet of Things routers at the same time, if you use Hongmeng OS plus Shangzhou compiler, you only need to compile once, so that multiple terminals can be deployed and shared

Huawei's Ark compiler can compile high-level languages ​​into the underlying machine language of the system for developers in the development environment. The execution efficiency of machine language is higher, and it can also shield the differences of different virtual machines.

#### What are the conditions for Hongmeng to be open source?



Hongmeng Open Source is a comprehensive open source. For technical secrecy and core things, there are some places that are open sourced in rhythm, and eventually will be open sourced.
