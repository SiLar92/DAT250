# DAT250: Software Technology Experiment Assignment 7
by Sindre Larsen

[Source code here](https://github.com/SiLar92/expass7)

## Technical issues
No technical issues encountered when completing the experiments.

## Experiment 1
No issues installing the software

![](images/expass7/version.png "")
## Experiment 2
Hello world tutorial:\
![](images/expass7/send.png "")

No issue sending or receiving \
![](images/expass7/recv.png "")

Local queue\
![](images/expass7/queue.png "")


## Experiment 3
Work queues tutorial:\
![](images/expass7/NewTask.png "")\
![](images/expass7/Worker.png "")\

adding message acknowledgement we can see that messages are picked up, if the worker is interrupted.
The following screenshot is from worker running after being interrupted with messages in the queue.
![](images/expass7/acknowledgements.png "")\
where we see the worker immidiately starts working on the items in the queue. There were
no issues setting the messages to be durable or using fair dispatch.

## Experiment 4
Publish/subscribe tutorial went great without any issues.

![](images/expass7/emitlog.png "") /
![](images/expass7/receivelogs.png "") /
![](images/expass7/bindings.png "") /


----
No pending issues.