# RPi3-PREEMPT_RT
Latency measurements of RPi3 on default Raspbian Linux and Raspbian Linux with PREEMPT_RT patch

Software (master & slave) modules used to perform real-time performance test of Raspbian Linux (in a RPi), 
in a master-slave schema. 
The Raspberry device under test (slave) is connected to, and communicates with, another Raspberry (master) 
that performs the actual measurements. Measurements include the latency of response tasks in user and kernel space, 
the response at specific periodic rates on execution of periodic tasks in user and kernel space, 
the maximum sustained frequency.
